## One Rule to Rule Them All • Pragmatic Dave Thomas • GOTO 2023

URL: [https://www.youtube.com/watch?v=ug8XX2MpzEw](https://www.youtube.com/watch?v=ug8XX2MpzEw)

 * The speaker presented the rule "make it easier to change" as a guiding principle in software development
* They emphasized that this is not a hard and fast rule, but rather a value that can help guide decision-making
* The speaker discussed their experiences with refactoring code and how they've learned to trust their intuition when estimating the cost of change
* They encouraged the audience to observe and learn from their own experiences in order to improve their estimation skills
* The speaker also emphasized the importance of making software development a fun and enjoyable process.


## Programming's Greatest Mistakes • Mark Rendle • GOTO 2023

URL: [https://www.youtube.com/watch?v=Y9clBHENy4Q](https://www.youtube.com/watch?v=Y9clBHENy4Q)

 * The title of the talk is "Computers are stupid"
* The speaker argues that computers cannot be trusted with important decisions because they lack common sense and can only do what they are programmed to do
* They are prone to errors, especially when dealing with ambiguity or unexpected situations
* Examples of computer failures include:
	+ A computer-guided missile missing its target by 10 miles during the Gulf War
	+ The Therac-25 radiation therapy machine overdosing patients and causing their deaths
	+ Amazon's AI-powered hiring tool discriminating against women
	+ Google's image recognition algorithm labeling black people as gorillas
* The speaker also mentions that computer algorithms are often biased because they are based on data created by humans, who are themselves biased
* The speaker concludes that computers are not intelligent and should not be trusted with important decisions, especially when human lives are at stake.


## Building Owly: An AI Comic Video Generator for My Son • Agustinus Nalwan • YOW! 2023

URL: [https://www.youtube.com/watch?v=jkHCI4XCOg4](https://www.youtube.com/watch?v=jkHCI4XCOg4)

 - The speaker presented a project using the stable diffusion model to generate comics based on user input.
- The stable diffusion model is a text-to-image generation model that can create images from text descriptions.
- The speaker used the model to generate images for each panel of a comic, with the text for each panel provided by the user.
- The project also included features such as off-riding existing concepts and enhancing engagement through storytelling.
- The speaker encouraged audience members to reach out to them for more information or to connect.



## Data - The Land DevOps Forgot • Michael Nygard • YOW! 2023

URL: [https://www.youtube.com/watch?v=459-H33is6o](https://www.youtube.com/watch?v=459-H33is6o)

 * Data mesh is a new paradigm in data management
* It allows for decentralized production and consumption of data
* Governance in the data world will be a big focus, but it needs to be federated through tooling
* Vendors have high motivation to get you on board right now, so it's important to be mindful of their motivations



## Cultivating Instinct • Katrina Owen • YOW! 2023

URL: [https://www.youtube.com/watch?v=4As7GDQ8EYg](https://www.youtube.com/watch?v=4As7GDQ8EYg)

 - The talk is about the importance of perceptual expertise in programming.
- Perceptual expertise is the ability to quickly and accurately recognize patterns, which allows experts to focus on higher level thinking.
- Programming requires a high level of perceptual expertise because it involves processing many different dimensions at once.
- The brain has to figure out which dimensions are important and how to categorize them, which can be overwhelming for new programmers.
- Over the past 50 years, the number of programmers in the world has doubled roughly every five years.
- Many new programmers may not be exposed to good patterns, useful distinctions, or signal that would help them develop perceptual expertise.
- Compressing these lessons can help new developers waste less time on mechanics and focus more on solving meaningful problems.


## Is Software Engineering Real Engineering? • Hillel Wayne • YOW! 2023

URL: [https://www.youtube.com/watch?v=CmIGPGPdxTI](https://www.youtube.com/watch?v=CmIGPGPdxTI)

 * The speaker discusses their experience of entering the software industry from a non-traditional background.
* They emphasize the importance of learning and adapting in order to succeed in a new field.
* They encourage others to seek out people with diverse backgrounds and experiences in order to learn from them.
* They suggest that there is much to be gained from learning about other fields and how they intersect with software engineering.
* The speaker encourages the audience to talk to people who have entered software from unusual directions in order to learn from their experiences.


## How to Do Embedded Development with Rust • Steve Klabnik • GOTO 2023

URL: [https://www.youtube.com/watch?v=7lHtXkYnip8](https://www.youtube.com/watch?v=7lHtXkYnip8)

 - Low-level programming is writing code that runs directly on the hardware, without an operating system or virtual machine.
- It can be useful for tasks such as embedded systems and kernel development.
- Rust is a good language for low-level programming because it allows for fine control over memory management while also providing safety features to prevent common errors.
- The ARM Cortex-M4 microcontroller is a popular choice for low-level programming, due to its wide availability and powerful capabilities.
- When working with low-level programming, it's important to have access to the datasheet and reference manuals for the hardware being used.
- Low-level programming can be challenging but rewarding, as it allows for greater control over the hardware and more efficient use of resources.


## Have I Been Pwned? • Troy Hunt • GOTO 2023

URL: [https://www.youtube.com/watch?v=pxPEdUFdayA](https://www.youtube.com/watch?v=pxPEdUFdayA)

 - The talk was about the Genesis Market, a darknet marketplace that sold access to compromised machines.
- The presenter discussed how the FBI took down the site and arrested its administrators in Operation Cookie Monster.
- The FBI used binary code and hoodies as imagery in their operations, which the presenter found amusing.
- The presentation ended on a positive note, highlighting the FBI's sense of humor.


## Plain Text • Dylan Beattie • GOTO 2023

URL: [https://www.youtube.com/watch?v=4mRxIgu9R70](https://www.youtube.com/watch?v=4mRxIgu9R70)

 - Pike Matchbox is a text encoding tool that optimizes plain text files for different cultural and linguistic contexts.
- It supports several encodings, such as ASCII, UTF-8, and UTF-16.
- It also considers language-specific features, such as Danish spelling reform, Norwegian orthography, Finnish alphabet, Swedish alphabet, and big and little endian conventions.
- The tool can be used in different operating systems and text editors.
- Pike Matchbox was developed to address the issues of unpredictability in plain text files and to ensure that the text is displayed correctly across different platforms and devices.
- The history of teleprinters and their encoding conventions also played a role in shaping Pike Matchbox's design.
- The talk encourages developers to consider cultural and linguistic contexts when working with plain text files and to use tools like Pike Matchbox to optimize them for their intended audience.


## Hot Deploying Low-Latency Services for 24/7 Operation • Martin Thompson • YOW! 2022

URL: [https://www.youtube.com/watch?v=_KvFapRkR9I](https://www.youtube.com/watch?v=_KvFapRkR9I)

 - Real-time systems require coordination between different components
- Aeron is an open-source project for building clusters that can handle fault tolerance and low latency
- Coordination is done through messaging, where components send messages to each other to communicate
- Components must be versioned to keep track of conversations between them and ensure compatibility
- Background tasks are used to perform time-consuming computations without pausing the system
- Customers have driven the development of Aeron towards supporting 24/7 operation and hot deployment.


## Scaling Python for Machine Learning: Beyond Data Parallelism • Holden Karau • GOTO 2023

URL: [https://www.youtube.com/watch?v=IX3300umebg](https://www.youtube.com/watch?v=IX3300umebg)

 - Dask is a flexible library for parallel computing in Python.
- It can be used to process large datasets that do not fit into memory by breaking them down into smaller chunks and processing them in parallel.
- It can also be used to parallelize existing code and scale up computations on multi-core machines or clusters of machines.
- Dask is designed to be used with Pandas, Numpy, and Scikit-learn, so it integrates well with existing scientific computing workflows in Python.
- It includes a number of built-in algorithms for common data processing tasks, such as sorting, filtering, and aggregating data.
- Dask can be used to parallelize machine learning models and perform distributed training.
- It is also useful for performing exploratory data analysis on large datasets by allowing users to write interactive code that scales up to handle larger datasets.
- Dask has a number of built-in visualization tools for monitoring the progress of computations and diagnosing performance issues.
- The speaker recommends using Dask with Jupyter notebooks for interactive data processing and exploration.
- Dask is not a replacement for existing parallel computing libraries such as MPI or Hadoop, but rather it is designed to be used alongside these libraries to provide additional functionality and flexibility.


## Using Semantic Metadata to Create an Automated Microservice Data Mesh • Marty Pitt • YOW! 2022

URL: [https://www.youtube.com/watch?v=wnydtt2lTQk](https://www.youtube.com/watch?v=wnydtt2lTQk)

 - Started by showing a GraphQL API built using Prisma
- Showed how to run a query in the playground and explained what it does
- Added a new field `reviews` to the schema, which returns an array of reviews for a given post
- Explained that this requires making changes to both the schema and the resolver
- Modified the GraphQL schema by adding the `reviews` field to the `Post` type
- Updated the database model in Prisma's `schema.prisma` file to include a relation between posts and reviews
- Redeployed the API using `prisma deploy`
- Showed how the new field can now be queried in the playground
- Added a mutation for creating new reviews
- Modified the `getPost` resolver function to make use of the new review data
- Explained that this required changing the contract of the `getPost` function to include review information
- Deployed changes and tested in the playground


## Why Is My App SLOw? Defining Reliability in Platform Engineering • Jez Humble • GOTO 2023

URL: [https://www.youtube.com/watch?v=es3DNd5Qipg](https://www.youtube.com/watch?v=es3DNd5Qipg)

 * The talk is about using statistical methods to model and predict system behavior in Site Reliability Engineering (SRE).
* The presenter, David Blank-Edelman, emphasizes the importance of understanding system behavior as a prerequisite for effective SRE.
* He introduces the concept of "stationarity," which refers to the idea that certain characteristics of a system remain constant over time.
* By identifying and modeling these stationary characteristics, SREs can make more accurate predictions about system behavior and respond more effectively to incidents.
* Blank-Edelman also discusses a technique called "time series analysis" for analyzing stationary data and predicting future behavior.
* He then describes how Google has implemented this approach at scale using a tool called "Borgmon," which can process large volumes of time series data in real time.
* The presenter emphasizes the importance of statistical modeling and prediction in SRE, and encourages practitioners to explore these techniques further.
* He also mentions that there are resources available on the sre.google website for those who want to learn more about this topic.


## An Introduction to Functional Imperative Programming in Flix • Magnus Madsen • GOTO 2023

URL: [https://www.youtube.com/watch?v=2LSOqikNqxM](https://www.youtube.com/watch?v=2LSOqikNqxM)

 - Flix is a functional, imperative, and logic programming language.
- It was developed by more than 50 people, including the speaker's research group.
- The language allows writing functions with some logic programming inside them.
- Flix has several unique features:
	+ Strong typing
	+ Pattern matching
	+ Higher-order functions
	+ Type inference
	+ Logic programming
	+ Side effects (through monads)
- Flix is designed for building scalable and efficient applications, particularly in the area of data analytics.
- The language has a visual studio code extension, documentation, and a playground available on its website.
- It is fully open source.