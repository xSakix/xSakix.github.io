# How to Run Gemma-7b-it Locally Using llama.cpp and GGUF

## Prerequisite

Some basic knowledge of how to build with CMake and how to clone a repository using Git is required.

Python3 must be installed on your local machine.

A prerequisite for this tutorial is having llama.cpp built on your local machine. If not, please go [here](https://github.com/ggerganov/llama.cpp) and follow the guides there. Don't forget to install requirements for Python scripts using the `requirements.txt` file.

## Download Gemma-7b-it

To download the Gemma-7b-it model, go to Hugging Face and clone the repository.
The repository is located [here](https://huggingface.co/google/gemma-7b-it/tree/main).

Follow these instructions to clone:
```
git lfs install
git clone https://huggingface.co/google/gemma-7b-it
```

Depending on your Linux distribution, you might need to install Git and Git-lfs. Note that Git LFS (Large File Storage) is dependent on the distribution.

## Prompt Format

For Gemma, you can use the following prompt template:
```
<bos><start_turn>user
{prompt}<end_turn>
<start_turn>model
```

## Use the Provided fp32 GGUF

You can use the provided fp32 file in the repo, e.g., `gemma-7b-it.gguf`. This is an fp32 model.

To run it via the main program, navigate to your build directory in llama.cpp and from the `bin` directory, run:
```
./main -m <path to gemma dir>/gemma-7b-it.gguf -ngl <number of layers to offload to gpu> -c <context size, max is 8192> -p <prompt>
```

To run it as a server:
```
./server -m <path to gemma dir>/gemma-7b-it.gguf -ngl <number of layers to offload to gpu> -c <context size, max is 8192>
```

To simulate a client, you can use curl:
```
curl -X POST "http://localhost:8080/completion" -H "Content-Type:application/json" -d '{"prompt":<your prompt>, "n_predict":<number of tokens to predict>, "temperature":<temperature>}' | jq .content | xargs echo -e
```

## Convert Model to fp16 from Repo Safetensors

To convert it to fp16, use the following Python command from the root llama.cpp directory:

```
python3 convert-hf-to-gguf.py <path to gemma root dir>/gemma-7b-it --outtype f16 --outfile "<path where you want to store your gguf>/gemma-7b-it-f16.gguf"
```

## Quantize fp32, fp16 to Q8_0

To quantize fp32, navigate to the llama.cpp build directory and from the bin directory:
```
./quantize <path to gemma directory>/gemma-7b-it.gguf <output path>/gemma-7b-it-q8.gguf Q8_0
```

Similarly, to quantize fp16, navigate to the llama.cpp build directory and from the bin directory:
```
./quantize <path where you stored your fp16 gguf>/gemma-7b-it-f16.gguf <output path>/gemma-7b-it-q8.gguf Q8_0
```

## Issues

### HF Authorization

You might encounter issues when cloning the repository. To gain access, you must accept the license from Google first. Then, when cloning, you might face an authentication challenge. A helpful solution was to use the Hugging Face Hub CLI and authorize using a Hugging Face token.

### Quality

In general, the quality ranking is f32 > f16 > Q8 > Q...

### Speed

Generally, the speed ranking is Q2 > Q3 > ... > Q8 > f16 > f32