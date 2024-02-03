## USENIX ATC '23 and OSDI '23 Joint Keynote Address - Sky Computing

URL: [https://www.youtube.com/watch?v=AuNfxVLdo0A](https://www.youtube.com/watch?v=AuNfxVLdo0A)


- The speaker is discussing "Sky Computing", a new lab at their university.
- They believe Sky Computing will happen, and are trying to answer three questions: why Sky will happen, what it looks like, and their early experience with it.
- The speaker references the first internet demo in 1977, where packet data was sent between two continents using different network technologies. They draw a parallel to Sky Computing, where they want to abstract away the differences in cloud technologies for users.
- The goal of Sky Computing is to allow users to run applications across multiple clouds, which can provide benefits such as data sovereignty, better hardware matching for specific tasks, cost reduction, and avoiding lock-in with a single cloud provider.
- They mention previous efforts at creating portability layers between clouds, but believe these have not been successful due to the complexity of reimplementing services at a higher layer.
- Instead, they propose a two-sided market approach, where services are implemented across multiple clouds and applications can choose which cloud to use based on their needs and preferences.
- They mention the issue of service incompatibility between clouds, and provide examples of open source and proprietary services that may be incompatible.
- The speaker then provides a simple example of a machine learning pipeline running on Sky, which can abstract away the cloud and choose the best option for the task based on requirements such as data confidentiality and cost minimization.
- They mention the use of an intercloud broker to map application requirements to available services in different clouds, and the importance of billing in a multi-cloud environment.
- The speaker believes that Sky will happen due to growing compatibility sets, market forces, and the desire of cloud providers to participate in these sets. They also mention the potential impact of Sky on research and innovation.


## USENIX ATC '23 - Bifrost: Analysis and Optimization of Network I/O Tax in Confidential Virtual...

URL: [https://www.youtube.com/watch?v=E47Jgd6zXW8](https://www.youtube.com/watch?v=E47Jgd6zXW8)


- The transcript is from a university talk about data security in cloud computing.
- Confidential VMS (CVMS) and CVN Hardware are proposed for secure cloud computing, providing OS level confidential computing with memory isolation and hardware encryption.
- Traditional VMS have been compromised, leading to disclosed sensitive data in Real Estate Services and Financial Services.
- GDPR has established and enforced data security regulations.
- CVMS provide good compatibility and transparency for application workloads.
- The growth of mobile network devices and ethernet speed is discussed.
- End-to-end encryption, POS forced dial data, and enhanced performance with extended filter are mentioned.
- The impact of end-to-end network performance on 3BM's network IO intensive application benchmark is evaluated.
- A serial attack scenario is described, focusing on CPU time spent on security protection intrinsic Network IO procedure.
- The non-red component histogram shows that the cvms comparison Baseline overhead mainly comes from um access tax and technical setting text.
- Synthetic protection secure state instance happens transiently, consuming large CPU cycles when receiving clear register add in CBM.
- Next Generation ethereum Hardware with bounce buffer is analyzed for traditional rear memory shared hypoider headquarters copy package directly to shared memory.
- The Rainbow Bridge north mythology metaphorically represents secure Rapid iodta transfer Syrian Ultra or share threat model existing cvms TCB.
- Design goals include performance, negative text largely reduced future hardware focus reducing bounce power tax, technically processing tax much possible time, maintaining level security guarantee, and practicality.
- The proposed defrost CVMS design focuses on zero copy encryption deduplication and eliminates payload bouncing.
- A backend-focused architecture is suggested to improve network performance by addressing the challenge of fully loaded CPUs.
- The prototype has low code complexity and achieves large performance improvement, but it cannot outperform the Baseline in certain scenarios.


## USENIX ATC '23 - SecretFlow-SPU: A Performant and User-Friendly Framework for Privacy-Preserving...

URL: [https://www.youtube.com/watch?v=X20APC8c9pQ](https://www.youtube.com/watch?v=X20APC8c9pQ)


- The transcript is from a conference presentation about the Secret Flow SPU project.
- The presenter discusses the importance of data privacy and security in machine learning.
- Secure Multiple Party Computation (MPC) is introduced as a solution to protect sensitive data during processing.
- A demo is shown to illustrate how MPC works, with three parties (Alice, Bob, Charlie) calculating the sum of their salaries without revealing individual amounts.
- The presenter then introduces Privacy-Preserving Machine Learning (PPML), which allows multiple parties to train machine learning models without exposing individual training data.
- MPC and PPML are distinct fields with different priorities, but integrating them is a challenge.
- Existing frameworks attempt to bridge this gap, either as general-purpose NPC compilers or by encapsulating cryptographic primitives in customized machine learning APIs.
- The presenter then introduces the Secret Flow SPU framework, which contains a compiler that converts ML model bytecodes into instructions for a high-performance runtime operating on a specific MPC protocol.
- The goal of Secret Flow SPU is to be user-friendly, extensible, and high-performance.
- The presenter concludes by mentioning the importance of GPT2 inference in the context of PPML.


## USENIX ATC '23 - Portunus: Re-imagining Access Control in Distributed Systems

URL: [https://www.youtube.com/watch?v=J50rieOdMRQ](https://www.youtube.com/watch?v=J50rieOdMRQ)


- Tanya is discussing Fortuna, a geographical key management system built using attribute-based encryption variant of public key cryptography.
- The system allows access control and keeps customer key knowledge hidden.
- It's an alternative to the usual strategy of using a central party or arbiter for access control in distributed systems.
- TLS termination is discussed as a problem where the infrastructure provider needs access to the customer's private key.
- Fortuna's solution involves a globally synchronized key value store (Quicksilver) that distributes customer configuration to edge machines.
- The challenge is to provide edge lower latency, high availability, fault tolerance, and comply with regulations like keeping the key accessible within the EU.
- Three options are discussed: centralizing access control logic, sending the key to an EU-based data center, or using public key crypto.
- The chosen solution involves key rotation and a variant of ABE that uses ciphertext policy for expressing access control.
- The system includes a key generation authority, an edge machine, and a machine provisioning database.
- The edge machine validates the set attribute and terminates the handshake if it can decrypt the data.
- The talk also discusses the challenge of decryption performance and the solution involving symmetric key crypto.
- The speaker mentions that the use of ABE is not widespread and lacks standardization.


## USENIX ATC '23 - GLogS: Interactive Graph Pattern Matching Query At Large Scale

URL: [https://www.youtube.com/watch?v=qF17EMpEog4](https://www.youtube.com/watch?v=qF17EMpEog4)


- The transcript is from a conference presentation about the design of an interactive graph query system called "geologs".
- The system is designed to handle large-scale graphs and support complex graph pattern matching queries.
- It aims to simplify the trial-and-error process typically involved in such queries, especially for non-expert users.
- Features of the system include:
- Support for a collaborative language called Grammy Cipher.
- Automatic optimization for performance tuning.
- Expected support for distributed execution across a cluster.
- The presentation compares geologs with existing solutions like Neo4j and TigerGraph, highlighting their strengths and weaknesses.
- The speaker introduces a new 4G Tech graph database that supports Cypher and GraphQL but lacks automatic optimization and distributed execution features.
- The speaker discusses the challenges in designing an igpm system and proposes solutions to overcome them.
- The proposed Glog system consists of three modules: user frontend, backend, and graph specifier.
- The system is designed to optimize GPM execution plans using higher-order statistic patterns stored in the innovative Glog structure.
- The distributed data flow engine in the backend module organizes executors corresponding to nodes in the cluster and partitions large graphs across clusters for efficient query processing.
- The graph specifier module is responsible for specifying the original large graph as a smaller one that maintains accuracy in pattern frequency estimation.
- The speaker highlights the importance of performance in the GPM system and compares execution plans generated by geologs, Neo4j, and Dulux, showing geologs' superiority in intermediate result size.


## USENIX ATC '23: Cyclosa: Redundancy-Free Graph Pattern Mining via Set Dataflowi

URL: [https://www.youtube.com/watch?v=ooJvvgOIk34](https://www.youtube.com/watch?v=ooJvvgOIk34)


- The transcript is from a presentation at Tru Huad University Science Technology.
- The presenter introduces the Research Graph Pattern Mining System, which aims to solve redundant computation problems in graph mining.
- The system uses an embed-centric paradigm, which avoids storing subgraphs and intermediate isomorphism checks by using pattern structure to guide exploration.
- This approach reduces the workflow significantly and avoids unnecessary partial instances.
- Redundant computation exists even in optimal search spaces due to repeated set intersections. The presenter identifies two categories of redundant computation: explicit (performed between neighboring subgraphs) and implicit (performed within search paths).
- The proposed solution is a new abstraction at the operator level, rather than the set formula level, which allows for better tracking and prediction of redundant computations.
- The system uses a data reuse possibility set data flow directed graph to indicate set transfer between operators, enabling fine-grained pattern analysis and decoupling of set operators from operators.
- The presenter introduces the Cyclosa prototype system, which has three major tasks: analyzing user input patterns, generating efficient set data flows, and scheduling set data flows for operator execution.
- Cyclosa supports three basic set operators (range-based data flow graph, time-based execution engine, and set manager) and uses a two-phase pattern analysis approach that considers pattern data graph features and symmetry breaking.
- The system uses dual IDs to identify sets and operators, ensuring correctness and saving memory space.
- Cyclosa has been tested for efficiency and outperforms other works in handling explicit and implicit redundancies. It also supports fine-grade load balancing and shading among sets.


## USENIX ATC '23 - SOWalker: An I/O-Optimized Out-of-CoreGraph Processing System for Second-Order...

URL: [https://www.youtube.com/watch?v=g7JD1TppoBY](https://www.youtube.com/watch?v=g7JD1TppoBY)


- The transcript is from a conference about using second order random work in graph processing systems.
- Second order random work is powerful for extracting information from graphs, as it considers recent work history and previous vertex selection.
- Traditional random work uses first order markup model, assuming transition probability depends only on the current vertex, not previous information.
- Encouraging results have been obtained with second order random work, showing its necessity in considering higher order structure of real world data.
- AutoCore graph processing systems are proposed to make it cheaper and easier to analyze large graphs.
- Current systems load all work for a block into memory when loading the block, leading to extra IO for updatable works.
- The transcript suggests two factors to improve second order random work efficiency: avoiding loading nonupdatable works and loading many updateable works.
- A concept of work Matrix is introduced, which represents the dimensionality Matrix with numbered blocks created or updated based on work state elements.
- The system uses a succinct data structure to encode work in 128 bits for compact organization.
- The existing block scheduling model is limited as it ignores dependencies between blocks, leading to nonoptimal block scheduling and low utilization.
- Simulated annealing method provides an approximate solution much simpler than linear programming methods for solving the problem.
- The system's managed work block granularity restricts work updating, which hinders efficient work updating.
- An experiment is conducted using two representative second order random work based algorithms (ASO worker and graph worker) on a test bed with two graphs.
- Results show that the graph worker achieves significant performance improvement compared to the ASO worker.
- The left figure shows average IO utilization, where the graph worker has the highest utilization and work updating rate.
- The right figure demonstrates similar performance trends for both algorithms in terms of speedup.


## USENIX ATC '23 - Light-Dedup: A Light-weight Inline Deduplication Framework for Non-Volatile...

URL: [https://www.youtube.com/watch?v=dQzjK--oikw](https://www.youtube.com/watch?v=dQzjK--oikw)

1. TC talks about memory-based storage methods, such as Intel's Optane DC Persistent Memory, which are expensive but can enlarge logical space and reduce cost through basic workflow duplication in the file system.
2. Cisco's persistence data duplication file system performs identification first, calculates hash data fingerprints for duplicated files, and uses a metadata table to determine redundant data.
3. The system increments the reference count for non-redundant data and simply writes data with a reference count of 1.
4. Two methods of calculating fingerprints are discussed: using noncryptographic hash access (faster, less safe) and cryptographic hash functions like SHA256 (slower, more secure).
5. The text discusses the potential benefits of using non-crypto hash in byte container comparison for MDM software I/O bottleneck reduction.
6. Existing works often focus on exploiting I/O asymmetry and using noncryptographic hash for byte content comparison but fail to fully utilize their benefits.
7. The text highlights five common features that could impact MVM deduplication file systems: data distribution, update frequency, metadata overhead, access patterns, and software-defined storage.
8. The author focuses on two important components of duplication file systems: redundant identification management and deduplication methods.
9. A naive hash-based file system is introduced for comparison, but it incurs much higher latency compared to the Nova system due to synchronous latency hidden by fingerprint calculation.
10. The text proposes using memory prefetch instructions or hardware prefetching to hide high read latency and improve performance.
11. A speculative cross-block prefetch method (CBPP) is introduced, which pre-fetches the next block based on a hint field in metadata, potentially achieving full parallelism in IO operations.
12. The authors evaluate CBPP's effectiveness, showing it reduces overall time spent on container comparison.
13. A light redundant block identifier (LRBI) component is proposed, which uses noncryptographic hash-based approaches for speculative privilege-based content comparison.


## USENIX ATC '23 - TiDedup: A New Distributed Deduplication Architecture for Ceph4

URL: [https://www.youtube.com/watch?v=UhRRTgebFqE](https://www.youtube.com/watch?v=UhRRTgebFqE)

1. The speaker is discussing a data duplication system using fingerprint indexing for efficient backup in the YouTube system.
2. They mention a previous proposal of a centralized architecture, but express concern that application fingerprint indices may conflict with their philosophy.
3. The speaker highlights two main issues with existing systems:
   - Different applications have different data types, making it difficult to uniformly handle all data.
   - Previous duplication methods can disrupt the normal operation of the system due to locking mechanisms.
4. They propose a new architecture called D2 that addresses these issues:
   - It uses selective level crossover and crawling for efficient deduplication.
   - It introduces an event-driven architecture that reacts to external APIs without background work.
   - It implements content-defined chunking and a wide shared reference system to minimize generic messages.
5. The speaker concludes by mentioning they have conducted experiments showing the reasonableness of their proposed design's performance, and that the source code is available in a personal repository for feedback.


## USENIX ATC '23 - LoopDelta: Embedding Locality-aware Opportunistic Delta Compression in Inline...

URL: [https://www.youtube.com/watch?v=OAHFt4KCyr0](https://www.youtube.com/watch?v=OAHFt4KCyr0)

1. The transcript is from a conference presentation on the topic of data reduction techniques in backup systems.
2. Two common methods are mentioned: data deduplication and data compression, each with their own limitations.
3. Data deduplication removes duplicate chunks based on fingerprints but cannot remove redundancy among non-duplicates or highly similar chunks.
4. Data compression reduces storage cost by eliminating redundant data, but its effectiveness depends on the sketch indexing technique used.
5. The presentation introduces a challenge related to low compression ratio in existing sketch indexing approaches and proposes a solution called Loop dirt.
6. Loop dirt is a locality-aware sketch indexing technique that detects similar chunks based on logic and physical locality, improving data compression.
7. The presenter also discusses the challenge of low backup throughput caused by extra I/O reading in typical duplication-based backup systems.
8. Loop dirt is proposed to improve backup throughput by reducing xgios reading based chunk operations.
9. Another challenge mentioned is potential miss similar chunks during writing, which Loop dirt aims to address with a locality-aware filter.
10. The presentation concludes with an outline of the data sets used for performance evaluation and results indicating improved compression ratio and restore performance using Loop dirt.


## USENIX ATC '23 - TC-GNN: Bridging Sparse GNN Computation and Dense Tensor Cores on GPUs

URL: [https://www.youtube.com/watch?v=Et-kBEnry5Y](https://www.youtube.com/watch?v=Et-kBEnry5Y)


- The speaker is a fifth-year PhD student from UCSB.
- They are presenting their work on TCGN, a system that bridges Sports Gene computation with dense tensor core GPUs.
- Graphs are everywhere in daily life and are used to analyze social networks, friend recommendations, financial services, power grid failure detection, molecular biology property production, etc.
- TCGN operates in two parts: 
    1. Basic computation flow: It follows the graph-like operation of PageRank to get information from neighbors and then updates the node itself using the information from its neighbors.
    2. Basic operators used: Gene general first one is labor aggregation, which follows sparse Matrix multiplication (spmm).
- The second computation node feature computation follows sampled tense dense matrix multiplication (node embedded Matrix transpose).
- The speaker discusses the trend in parallel kind development algorithms that leverage powerful units like tensor cores in recent GPUs for deep learning acceleration.
- They highlight the challenge of bridging the gap between basic Gene operations and high-performance GPU units, which is still a challenging task.
- The speaker identifies several challenges:
    1. Existing Frameworks like PyTorch and TensorFlow support Deep learning but many focus on dance gym operation optimization.
    2. The irregular nature of gene computation makes it hard to harvest real performance as it lacks efficient sparse operators.
    3. There exists a sports library dedicated to developed vendors like Nvidia that leverages CUDA cores for acceleration, but it underutilizes resources in existing GPUs.
- The speaker then discusses two directions to address these challenges:
    1. Trying to let sparse GN fit dense Gene computation on GPU.
    2. Letting the GPU face GNNs by profiling basic operations and optimizing the sparse kernel.
- The speaker concludes that applying separate operations in either direction could hardly work and suggests a holistic optimization approach for better utilization of GPU resources.


## USENIX ATC '23 - Legion: Automatically Pushing the Envelope of Multi-GPU System for Billion-Scale...

URL: [https://www.youtube.com/watch?v=_5EXingIu1U](https://www.youtube.com/watch?v=_5EXingIu1U)


- The transcript is from a well known conference presentation.
- The presenter discusses their work on applying graph neural networks (GNNs) to large-scale DNS work at Alibaba group and Chuchang University.
- They highlight the challenge of handling billion-scale graphs with current GPU capacity, which often reaches its limit with real-world datasets.
- The presenter introduces Legion, a system designed for training large-scale graphs in a practical way using sampling-based methods.
- Legion consists of three key stages: rough sampling, feature extraction model training, and example typical graph stage.
- The Gene model, used in Legion, typically involves two-hop sampling to extract subgraphs and generate mini-batches for filling the model.
- A key issue with traditional GNN systems is that CPU sampling cannot catch up with GPU tuning, leading to a bottleneck.
- To address this, researchers have proposed cash-based systems like Quiver Gene Lab, which use GPU feature caches to minimize CPU-GPU data transform volume and overcome the CPU sampling bottleneck.
- Legion aims to fully explore hardware capability in modern multi-GPU systems for training billion-scale graphs.
- It proposes a hierarchical graph partitioning design to solve the poor multi-GPU cache stability issue, minimize overlap among partitions, and improve load balance.


## USENIX ATC '23 - Bridging the Gap between Relational OLTP and Graph-based OLAP

URL: [https://www.youtube.com/watch?v=QVZfKw4XyB0](https://www.youtube.com/watch?v=QVZfKw4XyB0)


- Speaker from Shanghai Jon University and Alibaba group presents at a conference.
- They introduce the use of graph-based AP for processing dynamic data in various scenarios, such as social media networks.
- Two existing solutions for dynamic graph analytical processing are discussed: 
    - ETL process with relational data stored in a graph system. This method provides good TP performance but has poor data freshness due to costly and lengthy data transformation processes.
    - Graph database systems that store data natively as a graph, offering better freshness but slower performance for transactional data management.
- A new computing model called Hybrid Transactional Analytical Processing (HTAP) is introduced, which provides the capability for real-time querying of data generated by transactions, achieving high performance and data freshness.
- The speaker presents their solution, HDJP, based on the HTAP model, addressing two unique design goals:
    - Preventing users from rewriting TP/JP requests by decoupling interfaces using a data menu population model convention.
    - Ensuring efficient dynamic graph storage with high performance and data freshness using local replayers to update graph data and supporting concurrent reading and writing operations.
- The HDJP system is designed to handle three key problems in existing general-purpose dynamic graph storage:
    1. Topology storage (CSR) that supports efficient edge scanning but is immutable, making new edge insertion costly.
    2. Multi-version concurrency control (MVCC) that introduces overhead and breaks temporary locality during updates.
    3. Efficient property storage models for JP workloads with almost fixed access patterns.
- The HDJP system redesigns dynamic graph storage, focusing on topology storage, MVCC poverty, and efficient property storage models.
- An evaluation of the HDJP system is conducted through experiments on two machines serving as both OLTP and OLAP servers, extended from standard benchmarks like LDBC-SD and TPC-C to accommodate HTGP workloads.
- The HDJP system is compared with offline solutions combined with state-of-the-art OLTP systems and graph systems, as well as an online solution using a graph database called Neo4j. The HDJP system achieves comparable performance to the online solution, outperforming the offline solution by an order of magnitude due to efficient graph storage and freshness.
- The speaker thanks the audience for listening and notes that the source code for the experiment is also available.


## USENIX ATC '23 - Comosum: An Extensible, Reconfigurable, and Fault-Tolerant IoT Platform for...

URL: [https://www.youtube.com/watch?v=E7L5lP1EmrI](https://www.youtube.com/watch?v=E7L5lP1EmrI)


- The speaker is GL Bamba, a PhD candidate in computer science at Allrell University.
- They are discussing Kamasan, an extensible and reconfigurable platform for digital agriculture.
- The project is a joint work with M Cornell, Shang Wan, Chin Sail, Atatu Muid, Reman Jose Martinez, Hakim Wepon, and other team members.
- The project aims to convert data into actionable insights to support decision making in farming.
- The speaker highlights the challenges of massive data collection, storage, and analysis in digital agriculture.
- They mention the need for a system that can tolerate equipment failure and unreliable power, which are common in rural areas.
- The speaker also discusses the challenge of vendor locking, where farmers are dependent on a single provider for their data and insights.
- Kamasan is designed to be flexible and adaptable, able to work with different sensors, networks, and geographies.
- The system uses a software-defined networking (SDN) approach, with a data plane for sensor data generation and transmission, and a control plane for configuration and analytics.
- The speaker also mentions the use of RPC protocol to ensure module network agnostic communication.
- They present three case studies: water guard for water stress alert in crops, vineyard disease detection, and cow fitness monitoring.
- The system has been deployed in various farms, including apple orchards, hemp corn strawberry tomato growing experiments, and a dairy farm.
- The speaker also mentions the challenge of cloud-based systems, which can be complex to configure and manage, and can suffer from deprecated APIs.
- They conclude by acknowledging the contributions of various individuals and organizations in the project.


## USENIX ATC '23 - Oakestra: A Lightweight Hierarchical Orchestration Framework for Edge Computing

URL: [https://www.youtube.com/watch?v=tdwTqPh8lH0](https://www.youtube.com/watch?v=tdwTqPh8lH0)


- Transcript is from a presentation on Orchestra, a lightweight hierarchical orchestration framework for Edge Computing.
- The presenter discusses the challenge of managing applications on constrained Edge devices, which may have heterogeneous hardware and network connectivity.
- A toy example of a microservice application (AR pipeline) is used to illustrate the concept of orchestration. This application consists of three services: camera, object detection, and tracking.
- The presenter compares the traditional approach of using a centralized orchestration platform like Kubernetes with Orchestra's hierarchical approach.
- Orchestra is designed as a three-tier system: worker node, cluster orchestrator, and root orchestrator. Each tier has specific components and responsibilities.
- The worker node consists of a node engine (for maintaining application state), net manager (for networking processes), and execution runtime (for running applications).
- The cluster orchestrator manages worker nodes within a geographical area, keeping track of their status and scheduling decisions. It communicates with worker nodes via MQTT.
- The root orchestrator provides an interface for application deployment and manages multiple clusters. It uses delegated scheduling to distribute workloads across clusters based on their capabilities and constraints.
- The presenter also mentions the concept of aggregation services, which can be balanced across instances in a cluster using different policies (like round robin or closest).
- The implementation of Orchestra is open-source and modular, with a focus on lightweight design. It has been tested to perform better than Kubernetes in terms of resource consumption.
- A use case of an AR application is used to demonstrate the benefits of using Orchestra, showing improvements in footprint and processing time compared to running the application natively without any orchestration platform.


## USENIX ATC '23 - Explore Data Placement Algorithm for Balanced Recovery Load Distribution

URL: [https://www.youtube.com/watch?v=I9WrwbNS6pM](https://www.youtube.com/watch?v=I9WrwbNS6pM)


- Video transcript from a conference about data placement algorithm for distributed storage systems.
- Explore Data Placement Algorithm is the title, presented by Junction Laboratory of Qingwai University.
- The research focuses on balancing recovery load distribution in HDFS and GFS systems.
- Recovery process can be paralyzed when dealing with multiple placement groups, leading to slower recovery times.
- Fingerprinting technique is suggested for distributing sufficient numbers of data units across various nodes to balance the recovery load.
- The research question revolves around finding a data placement algorithm that balances recovery load distribution.
- A 3D data placement algorithm is proposed to achieve optimal recovery load distribution, but it's an NP-hard problem.
- The study highlights the importance of balanced recovery load distribution and its impact on overall system performance.
- Recovery load distribution can affect the system expansion process, and a greedy data placement algorithm can help reduce recovery time.
- The transcript suggests that there is still room for exploration in discovering potentially more efficient algorithms.


## USENIX ATC '23 - Luci: Loader-based Dynamic Software Updates for Off-the-shelf Shared Objects

URL: [https://www.youtube.com/watch?v=h9-vHlND9ZY](https://www.youtube.com/watch?v=h9-vHlND9ZY)


- Lucy loader is a dynamic software update tool for off-the-shelf software.
- Existing approaches to dynamic software updates often require changes at the source level or use custom compilers, which can restrict the programming language used.
- Lucy's approach uses relocatable object files and doesn't require handcrafted patches, resulting in binary patch files.
- The approach is designed to be generic and applicable to multiple applications in user space.
- Lucy has been used to dynamically update the Apache web server, which has many external dependencies.
- A common example of a library that would benefit from dynamic updating is the expat XML parser, which had 17 vulnerabilities last year, many of which were severe.
- Lucy's Dynamic Software Update (DSU) capability can perform updates on dynamically linked libraries.
- Lucy uses the dynamic linker to load required chat libraries and performs necessary relocations at runtime.
- Lucy's approach doesn't modify machine instructions, making it safer and simpler.
- Lucy has been used to update the expert Library, which had 81 severe vulnerabilities since 2010.
- Lucy can hide old code and install a user page fault handler to detect access to the old code.
- Lucy uses a designated relocation interface and modifies code in place, making it easier to handle multiple shared object versions in memory.
- Lucy's approach can prevent execution of old library code if an incompatibility is detected.
- Lucy has been tested with the official release of a single patch built for a standard environment and was able to automatically update the library without manual intervention.
- Lucy can perform updates even in stable phases of a distribution, as demonstrated by tests on Debian Buster and Ubuntu LTS versions.


## USENIX ATC '23 - MELF: Multivariant Executables for a Heterogeneous World

URL: [https://www.youtube.com/watch?v=bkkwaur2GCk](https://www.youtube.com/watch?v=bkkwaur2GCk)


- Dominic Turner is a PhD student at Lapis University in Hanover.
- He presented the melf approach, which uses Mighty variant executables for profiling in a heterogeneous world.
- The motivation behind this approach is to address issues such as slow service and high latency faced by software engineers when dealing with databases.
- The melf approach allows for function-level granularity in profiling, enabling the profiling of individual functions within an application.
- This is achieved through the use of an overlay manager that allows for the concurrent use of multiple variants across the application.
- The overlay manager uses a synchronized address-based view concept, ensuring consistency and allowing for fast communication between processes.
- The melf approach has been evaluated through four case studies, including performance isolation and profiling maps.
- The Mighty variant elf format is used to incorporate multiple compile-time variants into a single executable file.
- This is done by compiling the source code twice, once with and once without the compiler transformation for profiling.
- The linker then builds an executable that includes both object files, placing the function sections in separate output files.
- A virtual address technique called memory overlaying is used to exchange sections at runtime, ensuring that function pointers remain valid.
- The overlay manager applies the exchange mechanism, allowing for the selection of the appropriate variant at runtime.
- The first case study presented involves performance isolation profiling using memkashd, where the melf approach was able to reduce the performance penalty payed when switching between connections.
- The second case study involves a heterogeneous ISO setup, where two core groups execute different ISA extensions to increase performance.
- The third approach combines the melf approach with thread pool awareness, allowing for the optimal dispatching of jobs to the appropriate core group.


## USENIX ATC '23 - APRON: Authenticated and Progressive System Image Renovation

URL: [https://www.youtube.com/watch?v=aZn8UMDuzfw](https://www.youtube.com/watch?v=aZn8UMDuzfw)


- The transcript is from a Microsoft researcher's presentation on Apron, an authenticated proactive system for secure and efficient physical device recovery.

- The system aims to address issues like system corruption due to file storage errors, software or hardware faults, or postponed updates.

- The recovery process involves five stages:
    1. Detection of system corruption.
    2. Learning from internal/external signals like telemetry.
    3. Recognition of the need for a reset.
    4. Solution implementation, such as entering a recovered environment for repair.
    5. System recovery using a reference image downloaded from a remote or local location.

- Criticism of existing recovery methods includes:
    - Large system image files that require long download times.
    - Recovery environments that lack meaningful applications.

- The proposed Apron system aims to address these issues by:
    1. Differential recovery of only the necessary data blocks.
    2. Performing program-specific recovery to minimize system downtime.
    3. Implementing an interposed storage access strategy for secure device management.

- The Apron system works in preparation and runtime phases, with a measurement server calculating H3 image metadata and signing the root hash value. This prevents low-rate attacks and ensures data integrity.

- Evaluation of the system shows improved recovery times compared to full recovery methods, especially in high-latency network environments.


## USENIX ATC '23 - zpoline: a system call hook mechanism based on binary rewriting

URL: [https://www.youtube.com/watch?v=aC_X0WU-tGM](https://www.youtube.com/watch?v=aC_X0WU-tGM)


- The transcript is from a conference presentation about system code and user space programs.
- The speaker discusses the use of system code to intercept and redirect execution of user space programs.
- They mention a hook mechanism that can be used to apply user-defined functions transparently to existing applications.
- The speaker mentions DPDK, a user space networking stack, which achieves five times better performance compared to the standard Linux TCP stack.
- They discuss a system configuration mechanism called P Trace, which uses three signaling techniques and SQL for user dispatch.
- The speaker notes that high performance penalty and flux can be issues with certain binary writing approaches.
- They explain the basic binary writing approach for x86 CPUs, using Cisco C Center instructions to trigger system calls.
- The speaker introduces a calling convention loop that defines how system code is invoked and executed in user space programs.
- They mention the use of trampoline code addresses and sampling code to manage address ranges.
- The speaker discusses the need to handle null access termination values and suggests a solution involving three types of memory access: write, execute, and read.
- They mention an execution check during the binary writing phase, which can be done using a bitmap overhead check.
- The speaker compares the measured overhead of their system with that of other systems, noting a smaller overhead for their system.
- They present a summary of their presentation, highlighting the benefits of their system configuration mechanism on existing CPUs.


## USENIX ATC '23 - Sponge: Fast Reactive Scaling for Stream Processing with Serverless Frameworks

URL: [https://www.youtube.com/watch?v=mhx0aWhzP6w](https://www.youtube.com/watch?v=mhx0aWhzP6w)


- Speaker is Mohammed, discussing Sponge, a distributed system for fast and reactive scaling in stream processing.
- Goals of modern stream processing engines: low latency, high throughput, correctness, resource efficiency.
- Real-time data stream processing can be tricky due to irregular and unpredictable data.
- Existing works struggle with scaling stateful operators, which keep state and perform Shuffle operations.
- Sponge aims to provide fast adaptation scaling for both stateless and stateful operators.
- Uses serverless frameworks for rapid handling of problematic situations, balancing stability and fast startup time.
- Challenge: large initialization overhead for network connection in serverless instances.
- Sponge design: composed of compiler and runtime, with the compiler setting data paths and the runtime providing fast reactive scaling.
- Runtime synchronization workload progress compilation phase is much shorter than dynamic optimization methods.
- Uses router operator to redirect data flow between operators, and transient operator for stateful operators.
- Aims to scale system within one second, overcoming challenges of incurring large overhead.
- Implemented in various open-source projects, including Apache Beam and Apache Nemo.
- Supports AWS Lambda service framework and helps manage instance valuation in a cluster.
- Shows performance improvement compared to baseline scaling using VM based scale with VM initialization overhead.
- Able to cover different real-world environment input data patterns, as shown in representative experiments.
- Cost analysis shows Sponge can be more cost effective than provisioned cases, especially during bursts of traffic.


## USENIX ATC '23 - On-demand Container Loading in AWS Lambda

URL: [https://www.youtube.com/watch?v=Wden61jKWvs](https://www.youtube.com/watch?v=Wden61jKWvs)


- The transcript is from a conference talk about AWS Lambda.
- AWS Lambda was launched in 2015 and initially supported deploying code via a zip file or raw code file.
- The platform initially supported a 50MB code limit, which was later raised to 250MB.
- The speaker discusses the challenge of increasing the package size without increasing cold start latency.
- The speaker mentions that customers started asking for more complex deployment methods as they tried to bring a broader range of applications to serverless.
- AWS Lambda increased the code file limit to 10GB, which is a 40x increase from the initial limit.
- This increase allowed customers to use standard container toolkits and chains for creating artifacts for deployment.
- The speaker mentions that the cold start is primarily contributed by downloading the package, and increasing the package size makes the cold start longer.
- AWS Lambda has built a pipeline for handling larger container images, including breaking them into chunks, calculating their hashes, and storing them in S3 using content-addressable storage.
- This allows for deduplication, which can significantly reduce the amount of data that needs to be moved around.
- The speaker also mentions that they've built an on-demand loading container system, which can accelerate container loading by up to 15x.
- They've seen a huge deduplication effect with container images, with up to 100x benefits when customers upload containers.
- The speaker also discusses the use of convergent encryption to allow for deduplication while maintaining security.
- AWS Lambda uses consistent hashing and Erasure coding in their cache design for fault tolerance and high data availability.
- They've built a tiered cache system with L1 local cache, L2 data center level distributed cache, and L3 S3.
- The speaker mentions that they've launched Lambda Snapstart caching distribution to reduce cold start times for Java applications.


## USENIX ATC '23 - Decentralized and Stateful Serverless Computing on the Internet Computer Blockchain

URL: [https://www.youtube.com/watch?v=y4rVM_dXD5s](https://www.youtube.com/watch?v=y4rVM_dXD5s)


- The speaker is discussing the Internet Computer platform, a decentralized system for efficient computation.
- The platform is composed of a collection of replicated state machines, each running on independent server machines in partitioned subnets.
- Canister smart contracts, written in languages like Rust, Python, JavaScript, or Motoko, are run on this platform.
- Canisters can send messages to other canisters or make exterior HTTP calls.
- The system is divided into four layers: networking, consensus, message routing, and canister.
- Canisters can make two types of calls: updates (slow, persistent changes) and invocations (fast, non-persistent computations).
- The Internet Computer differs from blockchains in several ways, including its Byzantine fault tolerance, geographical distribution, and self-governance.
- The speaker then focuses on the efficiency of the execution environment, discussing two main challenges: statefulness and deterministic scheduling.
- Statefulness is achieved through a system that maps memory pages on demand and checkpoints canister state at regular intervals.
- Deterministic scheduling is maintained by charging based on instruction count rather than time, and by using instruction-level slicing to ensure fairness.
- The Internet Computer uses context switching and instruction slicing to maintain high throughput.
- The speaker concludes by mentioning the production readiness of the Internet Computer and its growing adoption since May 2021.


## USENIX ATC '23 - Pinolo: Detecting Logical Bugs in Database Management Systems with Approximate...

URL: [https://www.youtube.com/watch?v=mirh27_Pwmw](https://www.youtube.com/watch?v=mirh27_Pwmw)


- The transcript is from a conference presentation about database management system (DBMS) testing.
- The speaker mentions the importance of DBMS, as it is used by many companies worldwide and even caused 9,000 flight delays when it sparked in January 2023.
- A specific type of bug, called a logical bug, is discussed. This bug causes the DBMS to return an incorrect result set given a SQL query.
- An example of a logical bug is provided, where two subqueries are used instead of one, causing inconsistency in the overall result statement.
- The speaker mentions that discovering and fixing logical bugs is challenging because the system may run normally but still produce wrong results.
- Three main lines of work are discussed for improving DBMS testing: differential testing, article guided synthesis, and metamorphic testing.
- Differential testing compares the results of a SQL query from different DBMS implementations. If there is a difference, at least one implementation contains a logical bug.
- Article guided synthesis generates a table containing data and constructs specific SQL statements to test for logical bugs.
- Metamorphic testing tries to construct two input/output pairs that satisfy a given metamorphic relation. If the number of outputs does not equal, at least one query triggers a logical bug.
- The speaker mentions limitations in existing techniques and proposes an advanced version of metamorphic testing that generates a generalized equivalence relation to detect deeply hidden bugs.


## USENIX ATC '23 - AutoARTS: Taxonomy, Insights and Tools for Root Cause Labelling of Incidents in...

URL: [https://www.youtube.com/watch?v=sGsDeJTuhEI](https://www.youtube.com/watch?v=sGsDeJTuhEI)


- The transcript is from a conference presentation about automating root cause labeling for incident postmortem reports in Microsoft Azure.
- The goal is to analyze and extract insights from past incident reports to reduce future incidents by identifying common root causes.
- Currently, the process of labeling postmortem reports is manual, ambiguous, and often prone to errors due to different taxonomies used by different teams.
- A new tool called Autoarts has been developed to automate this process using a comprehensive root cause taxonomy and machine learning techniques.
- The Autoarts system includes a hierarchical structure for the taxonomy, which facilitates easy navigation and helps in identifying contributing factors behind incidents.
- The system consists of two main tasks: root cause classification and context extraction from postmortem reports.
- The root cause classification module uses a multilabel text classification approach to identify contributing factors based on the taxonomy.
- The context extraction task involves identifying key contexts from the postmortem report to justify the chosen root cause tag.
- Autoarts has been trained using 2000 incident reports and 450 services in Microsoft Azure, with a focus on ensuring quality labeling by involving team incident domain experts for review.
- The system is open-source and continuously evolving, aiming to address issues caused by missing or ambiguous contributing factors in past incidents.
- Manual root cause labeling is still error-prone, while manual analysis can be expensive and not scalable for cloud environments. Autoarts addresses these concerns by automatically labeling given postmortem reports with contributing factors from the hierarchical taxonomy.


## USENIX ATC '23 - Avoiding the Ordering Trap in Systems Performance Measurement

URL: [https://www.youtube.com/watch?v=h3CM16m_Jq4](https://www.youtube.com/watch?v=h3CM16m_Jq4)


- The transcript is from a conference presentation.
- The speaker talks about a "watering trap" in performance measurement, where the order of benchmark execution can affect results.
- They share an example of a study where memory performance on newer servers was three times worse than on older ones, due to unbalanced memory page allocation.
- The speaker emphasizes the importance of considering system state changes and factors like cache data layout and RAM disk in performance testing.
- They mention a survey of 56 papers from top computer systems conferences, finding that only 7% specified, ran, and discussed an inner experiment reset procedure.
- The methodology they propose for avoiding the "watering trap" involves defining a baseline order, implementing a state reset procedure, and running tests in fixed or random orders.
- They suggest using a nonparametric statistical test like the Wilcoxon-Mann-Whitney test, and correcting for multiple comparisons with the Bonferroni correction.
- The speaker also discusses a long-term performance data set they collected, finding that order can have a significant effect on results in many cases.
- They conclude by emphasizing the importance of considering order when conducting rigorous performance analysis.


## USENIX ATC '23 - AWARE: Automate Workload Autoscaling with Reinforcement Learning in Production...

URL: [https://www.youtube.com/watch?v=gnOmCb1CG1s](https://www.youtube.com/watch?v=gnOmCb1CG1s)


- The transcript is from a conference presentation about Auto scaling in Cloud systems.
- The speaker discusses the use of Reinforced Learning (RL) for workload Auto scaling.
- The RL model is trained using data from modern Cloud systems, which generate abundant data through monitoring and measurement.
- The RL agent is designed to optimize specific workloads in a Cloud system, such as small jobs with low load and periodicity.
- The RL agent consists of two parts: policy training and policy serving.
- The speaker highlights the challenge of bridging the gap between the model's advancement and its deployment in production.
- The speaker then focuses on a concrete example of Cloud Resource Management, specifically Auto skating workload.
- The RL agent is modeled as a Markov decision process, with the artificial agent interacting with the environment in a step-by-step fashion.
- The speaker identifies three main challenges in implementing IO-based controllers in real production systems.
- The speaker proposes solutions for each challenge, including reliable Exploration, online serving policy, and model adaptation.
- The speaker introduces the concept of meta learning to address the model adaptation challenge.
- The speaker concludes by presenting the Aware framework, which aims to tackle three challenges in Cloud systems: providing fast adaptation through meta learning, reliable IO Exploration through bootstrapping, and robust online performance.


## USENIX ATC '23- Nodens: Enabling Resource Efficient and Fast QoS Recovery of Dynamic Microservice...

URL: [https://www.youtube.com/watch?v=YKkyh6oAqEY](https://www.youtube.com/watch?v=YKkyh6oAqEY)


- The transcript is from a conference discussing the complexity of medical service applications.
- Current architecture is monolithic, shifting towards microservices for better distribution and deployment in data centers.
- Challenges include managing dependencies among microservices and handling dynamic load changes.
- A study was conducted on 3000 medical service applications, observing load variation and choreographed proportion variation over time.
- Two types of dynamics were identified: predictable (based on historical data) and unpredictable.
- Current benchmarks support dynamic graph build, but struggle with handling unpredictable dynamics.
- Proposed solution is a runtime system called 'Node' that enables fast skill recovery while maintaining result efficiency.
- Node uses a traffic-based load monitor, an execution blocking graph, and an actual load updating mechanism.
- The system aims to allocate enough resources quickly to handle dynamic changes, reduce long kill recovery times, and maintain high result efficiency.


## USENIX ATC '23 - Lifting the veil on Meta’s microservice architecture: Analyses of topology and...

URL: [https://www.youtube.com/watch?v=vfsdGdVAwag](https://www.youtube.com/watch?v=vfsdGdVAwag)


- The transcript is from a conference presentation about microservice architecture.
- The speaker highlights the increasing popularity of microservices, with over 10,000 papers published last year alone.
- A fundamental change in the development landscape, microservices allow for independent team work and quick development of different functionalities.
- The speaker emphasizes that a service unit should be fine-grained enough to schedule, scale, route, and observe different entities.
- An example of a social network application is given, where frontend, stateless services, feed, friend, ad, and database work together to form the application.
- The speaker notes that there is a shared understanding in current literature about microservices, including assumptions about service granularity, deployment, scaling, observability, and topology.
- There is ongoing research into various aspects of microservice architecture, such as topology, request workflow, resource management, and performance profiling.
- The speaker presents the findings of a study on meta microservice architecture, focusing on topology and request workflow.
- The study found that the assumption of service granularity being sufficient for management tasks is true.
- However, the belief that topology is relatively static was found to be false, with significant daily churn in deployed services.
- The study also found that services are simpler than believed, but request workflows are wider and shallower than expected.
- The speaker notes that there is a lot of observability research, especially into deeper traces, and introduces the concept of 'depth' as a reliable metric for predicting characteristics of request workflows.
- The study also found variation in concurrency dependency within child calls.


## USENIX ATC '23 - Tectonic-Shift: A Composite Storage Fabric for Large-Scale ML Training

URL: [https://www.youtube.com/watch?v=F1ffpj8NkzE](https://www.youtube.com/watch?v=F1ffpj8NkzE)


- Mark is a visiting researcher at Meadow.
- He talks about Tectonic, a file system used for storing data in the data center.
- The system is composed of a metadata layer and a linearly scalable chunk store made up of hard drive based storage nodes.
- Recently, there has been an explosion in demand for AI applications, which require larger and more complex models to be trained.
- This requires scaling the ML infrastructure, both in terms of storage capacity and IOPS (Input/Output Operations Per Second) read bandwidth.
- The traditional approach of using a single server or rack for training is no longer sufficient. Instead, a cluster of thousands of accelerators is needed to train these models.
- The same applies to the storage infrastructure. The traditional approach of provisioning enough storage capacity to store the data set is not enough. There is also a need for enough IOPS read bandwidth to handle the increased demand.
- Mark discusses the idea of a composite storage system, which uses hard drives for storage and SSDs for serving IOPS.
- He mentions that they have built a transparent flash tier, called Tectonic Shift, designed specifically for industrial ML workloads.
- This tier is designed to be transparent to the end user, scalable, fault-tolerant, and able to maximize IOP absorption without storing the entire data set.
- The production ML storage fabric of Tectonic Shift looks like a standard Tectonic cluster with an additional shift cluster made up of flash-based storage nodes.
- The cache policy is specifically tailored to the ML workload and able to maximize IOP absorption.
- Mark also mentions that they have evaluated Tectonic Shift using benchmarks consisting of three production DLRM recommendation model training workloads.


## USENIX ATC '23 - Calcspar: A Contract-Aware LSM Store for Cloud Storage with Low Latency Spikes

URL: [https://www.youtube.com/watch?v=esHi3z0HdRE](https://www.youtube.com/watch?v=esHi3z0HdRE)

1. The transcript is from a conference presentation about cloud block storage, specifically Amazon EBS.
2. Cloud block storage has become organized and safer, leading to widespread adoption by businesses worldwide.
3. Amazon EBS is chosen due to its low latency and high predictability, which are crucial for many applications.
4. The speaker discusses the trend towards cloud-based application servers and databases.
5. Other databases mentioned include RSM store and ASM store.
6. Cloud block storage offers guaranteed steady and predictable latency, making it a professional resource.
7. The speaker analyzes the latency performance of cloud block storage systems.
8. They discuss the importance of observing and appreciating the exercise paid in terms of obvious latency increase.
9. An example is given of a city where L2 latency increased significantly due to high load.
10. The speaker introduces EBS's low latency characteristic and how it works well with other systems.
11. They discuss the concept of CDM figure in cloud block storage.
12. The speaker mentions the use of GB2 and GB3 in cloud block storage.
13. They discuss the importance of understanding the nature of latency spec and the challenge of quantifying it.
14. The speaker suggests that AWS EBS's regular fee control can help manage latency issues.
15. They present an equation to configure LPS for better latency performance.
16. The speaker discusses the impact of high RPS on latency and how it can be managed.
17. They mention the concept of IO overdrafting and its impact on flow.
18. The speaker discusses EBS's punishment mechanism for excessive IO requests.
19. They present a latency model based on real-world internet latency data.
20. The speaker discusses the challenge of cloud storage meeting demanding performance requirements.
21. They mention the issue of fluctuation in cloud storage and how it can be handled.
22. The speaker introduces the concept of Pro tax to avoid latency battles.
23. They propose a solution for managing latency fluctuations in EBS.
24. The speaker discusses the importance of proactive control in managing IO load and overdraft.
25. They mention the challenge of fluctuation in tech support and education.
26. The speaker suggests adopting small workloads to avoid latency battles due to internet regulation.
27. They introduce a dynamical time Windows scheduler to reduce latency opportunity.
28. The speaker briefly summarizes the latency characteristics of cloud block storage.


## USENIX ATC '23 - Adaptive Online Cache Capacity Optimization via Lightweight Working Set Size...

URL: [https://www.youtube.com/watch?v=NHDM8bd_260](https://www.youtube.com/watch?v=NHDM8bd_260)


- The transcript is from a conference presentation about an adaptive online catching layer for data processing systems.
- The catching layer is used to manage the working set size and improve querying performance.
- The presenter discusses challenges in maintaining optimal data storage, including excessive restores and insufficient capacity.
- The presenter introduces Alexio, a catching layer that has been observed to have a high cache ratio in Presto deployments.
- The presenter highlights the importance of accurately estimating the working set size and item repetition ratio for effective resource allocation.
- The presenter proposes a cookie data structure for managing item information online, with operations for insertion, aging, and deletion.
- The presenter also suggests an optimistic concurrency control strategy called Optimistic Agent 80 for reducing locking contention in the system.
- The presentation evaluates the performance of the proposed system using Twitter Trace data and finds it to be more accurate and stable than existing approaches.


## USENIX ATC '23 - SAGE: Software-based Attestation for GPU Execution

URL: [https://www.youtube.com/watch?v=vpsNlotLJIM](https://www.youtube.com/watch?v=vpsNlotLJIM)


- The transcript is from a conference presentation about securing GPU execution.
- The presenter, Marco Canadian, is standing in for Andrei Ivanov who couldn't attend due to a visa issue. Benjamin Rothenberg and Adrian Parrig also contributed to the work.
- The motivation for the work is the difficulty of securely executing code on GPUs, which are often used in security-critical domains.
- The proposed solution is a software-based approach called Sage, which provides time-code data integrity secrecy for GPU execution.
- Sage works by verifying the integrity of the code before it's executed on the GPU, and then establishing a secure communication channel between the CPU and GPU.
- The trusted verifier in Sage is responsible for verifying the integrity of the code and setting up the secure communication channel.
- Sage provides verifiable code execution, ensuring that the code executed on the GPU is the same as the code verified by the trusted verifier.
- The presenter discusses the challenges of software-based attestation on GPUs, including the lack of documentation and the difficulty of achieving optimal GPU utilization.
- Sage is architected with a trusted verifier running within a CPU enclave (like Intel SGX), which sends challenges to the GPU device.
- The verification function in Sage computes a checksum of the code running on the GPU, and the key establishment module sets up a secure communication channel between the CPU and GPU.
- The presenter also discusses the challenge of predictable execution time, as any modification of the verification function could be detected by measuring the execution time.
- The presenter concludes by discussing the potential of combining software and hardware solutions for a multi-layer security defense.


## USENIX ATC '23 - Confidential Computing within an AI Accelerator

URL: [https://www.youtube.com/watch?v=nTVP6IvFlDY](https://www.youtube.com/watch?v=nTVP6IvFlDY)

1. The speaker is discussing Confidential Computing, a new paradigm in AI that provides strong protection for sensitive data and code.
2. Confidential Computing uses a concept called Trusted Execution Environment (TEE) to protect privileged attacks including those on the hypervisor, operating system, and base assumptions.
3. The speaker mentions that recent years have seen a new wave of AI Innovation that requires GPUs for cost-efficient training of large models in the cloud. However, this also presents a challenge in terms of confidentiality due to the risk of sophisticated attackers stealing data.
4. Confidential Computing is seen as a solution to this problem, providing a strong security mechanism for AI workloads in the cloud.
5. The speaker mentions that major CPU vendors have shown support for Confidential Computing over the past 10 years, but there has been limited support for PCI devices. Recently, Nvidia announced Hopper GPUs with Confidential Computing extensions.
6. The speaker is working on a development board using TSMC 7 nanometer technology that provides strong security guarantees and isolates the entire device host. It also adds remote attestation using hardware root trust for low performance overhead.
7. The speaker introduces the Graphcore IPU architecture, which employs a thousand tiles with multi-threader cores and specialized units for AI workloads. Unlike CPUs and GPUs, it uses flat memory space and core private SRAM for load/store additions.
8. The IPU software stack comprises a compiler, runtime, and introduces an abstraction called stream. The compiler takes the input/output and fits it into a unique stream that generates code encapsulated in the IPU binary.
9. The speaker discusses the need for a small TCB (Trusted Computing Base) to provide confidentiality and integrity for data computation. They introduce a security paper that makes assumptions about the threat model.
10. The speaker then talks about the IPU trust extension, which removes trust from the runtime by decoupling compilation and execution. This is done by preprocessing data and encrypting code and data before shipping it to the cloud runtime.
11. The encrypted code and data are decrypted using a GCM encryption engine in the PCI memory path intercept package, which can deliver PCI Gen 4 bandwidth rate.
12. The Confidential Computing Unit (CCU) is responsible for managing the life cycle of TE and attesting to the code using the job manifest and provisioning key. It also adds a trusted mode set CCU that creates a TE based on observation training job span.
13. The speaker concludes by stating that they believe infrastructure with hyperscale privacy-preserving AI work is foreseeable in the near future, and their work could serve as a blueprint for this.


## USENIX ATC '23 - Arbitor: A Numerically Accurate Hardware Emulation Tool for DNN Accelerators

URL: [https://www.youtube.com/watch?v=WvIHZMkGD7o](https://www.youtube.com/watch?v=WvIHZMkGD7o)


- The transcript is from a conference presentation about the Arbiter, a hardware accelerator for machine learning training.
- The presenter discusses the challenges of optimizing hardware level operations for speed and precision, and how these optimizations can affect model accuracy.
- The Arbiter is designed to estimate the effect of these optimizations more accurately and efficiently than existing methods.
- The Arbiter is open-source and has been used in case studies with popular benchmark data sets, showing significant speed improvements.
- The presenter also mentions the use of low precision arithmetic, sparsity processing, and approximate computing for hardware acceleration.
- The Arbiter can emulate these operations with high precision, which is crucial for accurate machine learning model training.
- The presenter concludes by encouraging the audience to check out the paper and the GitHub page for more information.


## USENIX ATC '23 - Bridging the Gap between QoE and QoS in Congestion Control: A Large-scale Mobile...

URL: [https://www.youtube.com/watch?v=arT_YQmLKJ0](https://www.youtube.com/watch?v=arT_YQmLKJ0)

1. The transcript is from a conference about congestion control in large-scale mobile app services.
2. Quality of Experience (QE) and Quality of Service (QS) are key metrics discussed, with QS being optimized by transport layer protocol delivery capability.
3. The authors propose a solution for the mismatch between QE and QS optimization, focusing on end-to-end performance of web requests.
4. They emphasize that optimizing QE is challenging due to its complex relationship with QS and the different time scales involved.
5. The proposed solution involves introducing a layer in the application layer to select the appropriate Congestion Control Algorithm (CCA) for better QE.
6. Two main questions are addressed: selecting the best CCA based on QE mean, and switching CCAs without traffic interruption due to dynamic network conditions.
7. The authors propose a framework called Flu, which uses reinforcement learning to build a prediction model for CCA preference.
8. Flu also introduces a mechanism for smooth switching between CCAs, addressing the challenges of new CCAs starting in slow-start phase and network condition mismatches.


## USENIX ATC '23 - FarReach: Write-back Caching in Programmable Switches

URL: [https://www.youtube.com/watch?v=VVP0J8l9wlI](https://www.youtube.com/watch?v=VVP0J8l9wlI)

1. The study aims to improve the performance of key-value stores, particularly for write-intensive workloads which have become dominant in production environments.
2. A programmable switch architecture is proposed to address this challenge, consisting of a control plane and data plane.
3. The data plane includes multiple pipelines, with each pipeline containing series stages that process requests and responses within the switch memory.
4. A write policy is deployed on the switch cache, which absorbs in-switch records instead of updating the server immediately to improve performance.
5. However, this approach faces challenges such as restricted programming language for the switch data plane, limited resources for offloading cache management, and slow controller processing that may encourage latency in the switch data plane.
6. The availability challenge is addressed by proposing a far-RICH (Reliable In-switch Cache) policy to ensure the latest record is always available to clients.
7. A prototype has been implemented based on the Tofino switch, and extensive experiments have shown that it achieves 66 times the performance compared to the baseline of 128 simulated servers.
8. The open-source prototype design and implementation details are provided in the study.


## USENIX ATC '23 - CXL-ANNS: Software-Hardware Collaborative Memory Disaggregation and Computation...

URL: [https://www.youtube.com/watch?v=fa66gZiiF58](https://www.youtube.com/watch?v=fa66gZiiF58)


- The speaker is a PhD student presenting their recent work on approximate nearest neighbor search (ANNS) at a conference.
- They have collaborated with a colleague on this project.
- ANNS is widely used in various products and services such as search engines, recommendation systems, and databases.
- The challenge is handling large workloads with billions of data points requiring terabytes of memory.
- The speaker proposes a software-hardware collaborative approach to overcome the limitations of CXL (Compute eXpress Link) technology, which has shown promising but limited performance due to its far memory light characteristic.
- The proposed solution involves selectively offloading computation and reducing data transfer overhead compared to traditional systems like Oracle.
- The speaker then introduces the target research domain and the challenge of retrievable taken, which plays a crucial role in providing fundamental support for various services such as search engines, recommendation systems, and databases.
- Two main approaches for reducing memory consumption are discussed: compressing embedding tables (which can lead to errors and degraded search accuracy) and storing graph embedding tables on SSDs (which can result in slower storage access and higher latency).
- The speaker advocates building a Point data set using CXL memory pool, which provides a large memory space and supports three protocols: CXL.io, CXL cache, and CXL map.
- A graph-based ANS approach is briefly explained, achieving state-of-the-art accuracy and performance in challenging workloads.
- The speaker highlights two observations from their research: 1) traversing nodes closer to the query provides faster memory access, and 2) distance calculation can be a bottleneck, with memory access taking up most of the execution time.
- To address these issues, the speaker proposes XL NS software-hardware collaborative approach that includes a root complex size software stack for endpoint hardware stack, domain-specific accelerator register delivery interface, and cxl-based memory expander for local caching and acceleration on the endpoint side.


## USENIX ATC '23 - Overcoming the Memory Wall with CXL-Enabled SSD

URL: [https://www.youtube.com/watch?v=dQDCqHYS1Lk](https://www.youtube.com/watch?v=dQDCqHYS1Lk)


- The transcript is from a presentation at Syracuse University about overcoming the memory wall challenge in natural language processing models.

- The speaker discusses the growing model size (141x per year) and the limited growth of memory resources (13x per year), which creates a gap called the 'memory wall'.

- The presenter highlights CXL, a new cache-coherent PCIe based interconnect that enables direct memory access to CPU endpoints via low latency store instruction features.

- The speaker suggests using CXL compatible devices like flash memory for expanding main memory.

- However, there are three major challenges when using flash memory as an expansion option:
    * Granularity mismatch between host requests (64 bytes) and flash memory management data page grain (kilobytes).
    * Flash memory rewrite latency is slower than the device theorem rewrite latency.
    * Unlike DRAM, flash memory has limited endurance due to repeated program-erase cycles on the oxide layer of flash memory cells.

- The speaker proposes a solution using CXL Flash, which includes:
    * Creating two design tools: Physical Memory Tracer and trace-driven simulator model for CXL Flash.
    * Integrating existing optimization techniques like DRM cache and MSHR prefetcher to overcome granularity mismatch and device lifetime issues.
    * Analyzing the effectiveness of existing algorithms for improving CXL flash performance.

- The speaker briefly covers potential system-level changes that could improve device performance, but does not provide details.


## USENIX ATC '23 - STYX: Exploiting SmartNIC Capability to Reduce Datacenter Memory Tax

URL: [https://www.youtube.com/watch?v=lfupho5_iNA](https://www.youtube.com/watch?v=lfupho5_iNA)


- The speaker is Hoshanji from UIUC.
- He presented a paper on "Stacks" at a conference.
- The talk focused on data center memory and optimization techniques.
- Two notable trends in data center memory are the stagnant price reduction of DRAM technology and the increasing demand for memory due to consumer needs.
- The speaker highlighted two memory optimization features: Kernel Samepage Merging (KSM) and compressed swap pages.
- KSM aims to merge page content to eliminate redundant pages, saving host memory.
- Compressed swap pages store swap pages in RAM cache instead of common backup storage like disk swap systems for faster access.
- The speaker discussed the impact of Swap Z and traditional swap methods on system performance.
- Kernel features can significantly interfere with memory-intensive, latency-sensitive applications due to CPU cycle consumption and cache pollution.
- The speaker presented a solution called "Stacks," which leverages smart network interface controllers, CPUs, ASICs, and memory IO subsystems.
- Stacks propose offloading data plan operations to smart ink for efficient memory optimization without involving CPU cycles.
- The presentation included a demonstration of the effectiveness of Stacks in reimplementing two kernel features: swap and page compression.
- Evaluation results showed that Stacks successfully reduced 99th percentile latency increase by up to 624x and 870x for swap and KSM respectively.
- The speaker also mentioned the reduction in CPU cycle consumption with Stacks integration.
- The presentation concluded that memory optimizing control features are beneficial but can interfere with running applications, increasing latency significantly.
- Stacks framework leverages compute and RDMA capabilities of smart ink to reduce interference and preserve the benefits of memory optimization features while reducing 99th percentile latency for current applications.


## USENIX ATC '23 - Change Management in Physical Network Lifecycle Automation

URL: [https://www.youtube.com/watch?v=dmX_UXavC5o](https://www.youtube.com/watch?v=dmX_UXavC5o)


- The transcript is from a conference presentation on 'change management physical Network lifecycle automation' in Google's SDN-based Data Center network, Jupiter.
- The speaker discusses four challenges faced in managing Google's vast network: scale, safety, deployment, and interoperability.
- The scale challenge involves managing the growing network with numerous human touchpoints.
- The safety challenge is about managing constant change without disrupting the network application running on the client.
- The deployment challenge is about efficiently deploying the network fabric globally in a predictable time frame.
- The interoperability challenge is about ensuring various teams and systems can effectively communicate and share an authoritative, consistent view of the network topology.
- The speaker introduces Malt, a Network management content tool that uses a language model for generating, managing, and querying network models.
- Malt represents the network topology as an entity-relationship graph with entities like nodes and relationships like connections.
- The presentation focuses on using Malt to generate, manage, and maintain a unified intent model for high-level planning and detailed Network design decisions.
- Two services are discussed: the Model Design Service and the Build Service, both of which use the Malt language model.
- The Model Design Service creates and mutates current/future network models, while the Build Service focuses on asynchronization points, resource reservation, and building the distributed data flow graph execution engine.
- Topo Plan, a service for managing future Network topology, is introduced as an analogy to software version control systems like Git.
- The presentation concludes with two case studies: Dead Zone reduction deployment project and change management in a multi-data center fabric.


## USENIX ATC '23 - AAsclepius: Monitoring, Diagnosing, and Detouring at the Internet Peering Edge

URL: [https://www.youtube.com/watch?v=Fb0dCFZMLlU](https://www.youtube.com/watch?v=Fb0dCFZMLlU)

1. The transcript is from a conference discussing internet issues and solutions, specifically packet loss rate reduction in cloud services.
2. Four key questions are addressed: automating fault process, identifying victim traffic, dealing with faults, and deterring traffic.
3. Solutions involve monitoring user traffic in real-time, distinguishing healthy vs affected traffic, and using Swift rollback to minimize impact.
4. Faults are classified into three categories based on occurrence: within cloud, client-based, or middle (internet network).
5. Detection and resolution strategies vary depending on the fault type and location.
6. A proposed Auto system aims to automate the entire process, accurately identify fault direction, and deter traffic accordingly using a private backbone.
7. The system consists of three subsystems: monitor, diagnose, and deterrent, each with specific roles and functions.
8. Monitoring involves active probing, fault detection, and reporting; diagnosis uses a decision tree for fine-grid localization; deterrent employs different strategies based on fault direction.
9. The system has been successful in preventing major accidents in Huawei Cloud for three years.


## USENIX ATC '23 - Deploying User-space TCP at Cloud Scale with LUNA

URL: [https://www.youtube.com/watch?v=TK1vEDOopX4](https://www.youtube.com/watch?v=TK1vEDOopX4)


- The transcript is from a conference presentation by Schumer Alibaba Cloud.
- Topic: Experience deploying user space TCP in Alibaba cloud storage Luna.
- Luna's network cloud storage architecture follows the compute-storage-disk aggregation philosophy.
- Challenges for frontend network include different ages, drivers, and geographical locations of computers in the cluster.
- Kernel CCP was chosen for high reliability and compatibility, but it has high overhead and is not suitable for performance sensitive scenarios.
- Solutions to improve performance include RDMA and user space TCP solutions.
- Luna uses a user space driver and a unique thread, memory, and traffic model.
- Luna's thread model includes batch r2c and inline r2c models.
- Luna's memory model provides transparent 4K stack and zero-copy for application upper layer.
- Luna's traffic model collaborates with the kernel network stack.
- Performance evaluation shows that Luna reduces response latency by 70% and increases throughput by 35%.
- Luna has been deployed in production since 2017, increasing throughput for elastic block storage by 50% while maintaining low latency.


## USENIX ATC '23 - RubbleDB: CPU-Efficient Replication with NVMe-oF

URL: [https://www.youtube.com/watch?v=1Sjf79QyvrM](https://www.youtube.com/watch?v=1Sjf79QyvrM)


- The transcript is from a conference discussing improvements in CPU efficiency for replicated key-value stores using NVMeOF.
- A log structure merge tree example was used to illustrate the problem of slow and dead systems, often caused by the CPU becoming a bottleneck in the system's key-value store.
- The discussion focused on redundant compaction in a replicated setting, suggesting that it might not be necessary.
- The idea is to outsource and eliminate redundant compaction, making it possible for a robot DB to make protocol avoid redundant compaction and help NVMeOF remove redundant compaction.
- The speaker also mentioned the challenges of saving CPU while introducing secondary SD file shipping, which can add CPU overhead due to data disk file system operations.
- The speaker then introduced NVMoF, a protocol that allows hosts to mount remote mid-disks as local file systems, with data transferred via RDMA or TCP configurations.
- The primary and secondary disks are distinguished in the figure, and the primary can ship SD files without CPU involvement, bypassing the secondary's CPU but introducing a new challenge of handling this bypassed long CPU NVMe work on the Linux product layer.
- Many key-value stores rely on file system interfaces to access data, which can cause issues when shipping SD files to the secretary, who may not even see the incoming file.
- The speaker then discussed the issue of SSD file preallocation and proposed a mechanism where the primary can successfully ship SSD files to the secondary using NVMoF.
- However, this doesn't entirely solve the problem, as an interesting challenge arises when applying compaction results from the primary to the secondary, especially when mem tables are involved.
- The speaker then discussed two techniques used in RobotDB: partial order and request ID tagging, which can help fix consistency issues and ensure that requests are processed in the correct order.
- An evaluation result was presented, comparing the end-to-end performance of replicated RocksDB with and without compaction every instance.
- The speaker also compared tail latency, showing that RobotDB had a lower latency than the Baseline for both read and update workloads.


## USENIX ATC '23 - Distributed Transactions at Scale in Amazon DynamoDB

URL: [https://www.youtube.com/watch?v=3OpEIMR-ml0](https://www.youtube.com/watch?v=3OpEIMR-ml0)


- The transcript is from a conference presentation about using transactions in DynamoDB, a NoSQL database.
- The speaker discusses the benefits and challenges of adding transaction support to DynamoDB.
- Transactions can simplify application development and help maintain multi-item invariance, which is crucial for many applications, such as online ecommerce.
- However, maintaining invariance in a distributed system is difficult. Traditional methods like two-phase locking can prevent concurrent access but can also lead to performance issues.
- DynamoDB uses a multitenant service that allows applications to begin and end transactions. It doesn't use traditional two-phase locking due to the cost of maintaining multiple versions of items.
- Instead, DynamoDB introduces two new APIs: Transact Get Item and Transact Write Item. The former allows multiple items to be read consistently from an arbitrary set of tables owned by the customer. The latter allows multiple items to be created, deleted, or updated atomically.
- The speaker also introduces a new operation called Check Item, which is used when a transaction wants to verify whether another item is in a certain state before updating.
- The speaker then discusses how these APIs can be used to model various use cases, such as a shopping cart example with the Transact Write Item API.
- The speaker also explains the high-level architecture of how transactions work in DynamoDB, including the two-phase protocol used for preparing and committing transactions.
- Fault tolerance is achieved through checkpointing and recovery mechanisms.
- The speaker concludes by mentioning that DynamoDB now supports full ACID transactions, providing high scalability, high availability, and predictable performance.


## USENIX ATC '23 - Prefix Siphoning: Exploiting LSM-Tree Range Filters For Information Disclosure

URL: [https://www.youtube.com/watch?v=NgVVmu39u7g](https://www.youtube.com/watch?v=NgVVmu39u7g)


- Presenter: Moshik Kovich
- Topic: Information Disclosure Attack on Key Value Store using Range Filter
- Collaborators: Ad Kman and Anda Morrison, Tel Aviv University

- Key Value Stores (KVS) are used in many data stores, object storage, database systems for their performance benefits.
- KVS can also pose a security risk due to timing attacks, where an attacker can distinguish between the response times of queries to different keys.
- The presentation focuses on a specific type of timing attack called 'Perfect Siphoning', which reveals key prefixes using range filters in KVS.
- Range filters store information about key prefixes, which can be exploited by an attacker to reveal full keys.
- The attack is demonstrated on two different types of range filter: Surf and Sigma.
- The attack involves finding a false positive key, identifying its prefix, and then scanning for possible suffixes.
- The attack is feasible due to the high probability of finding false positive keys and the low linear key length call function.
- The presentation also discusses potential mitigation strategies, such as using authorized keys for queries, keeping ACLs outside the KVS, rate limiting user requests, and using a separate filter for Point queries.


## USENIX ATC '23 - EPF: Evil Packet Filter

URL: [https://www.youtube.com/watch?v=pkR5kJkFGkc](https://www.youtube.com/watch?v=pkR5kJkFGkc)


- The transcript is from a conference presentation on EPF pack filter joint work.
- The presenter discusses BPF (Berkeley Packet Filter) and its role in enabling new attacks on Kernel Security.
- Current security exploitation methods are discussed, with a focus on how BPF can be used to weaken kernel security.
- The presentation shows that BPF allows attackers to create large amounts of content in the kernel space and manipulate it, bypassing existing isolation mechanisms.
- The presenter introduces a new way to use BPF for password defense.
- The talk also discusses how BPF can be used to bypass user-space defenses and execute malicious code in the kernel space.
- The presentation mentions three defenses against these attacks: BPF ISR, BPF NX, and BPF CFI.
- The presenter evaluates the effectiveness of these defenses against two novel attacks that abuse the BPF subsystem.
- The evaluation shows that the defenses incur low to moderate overhead.


## USENIX ATC '23 - Translation Pass-Through for Near-Native Paging Performance in VMs

URL: [https://www.youtube.com/watch?v=e1DrrIKU0Ko](https://www.youtube.com/watch?v=e1DrrIKU0Ko)


- The transcript is from a conference discussing optimizing performance of virtual machines, which are used for consolidation and efficiency in resource utilization.
- Virtualization can lead to a substantial performance impact due to additional mechanisms required for abstraction and isolation.
- A significant issue is memory translation overhead, which can cause a lot of slowdown in applications.
- Two main approaches to virtualization are:
  - Nested paging: The operating system within the VM exposes a page table that translates guest virtual addresses to guest physical addresses. The hypervisor then provides an additional hierarchy page table to translate guest physical addresses to host physical addresses.
  - Shadow paging: The operating system within the VM provides a set of page tables to translate guest virtual addresses to guest physical addresses, but the hardware MMU performs the memory translation using a shadow page table provided by the hypervisor.
- Current systems require multiple memory accesses to translate a single virtual memory address to a physical memory address, which can lead to performance issues.
- The goal of the Translation Passthrough (TPT) system is to enable efficient translation management within virtualized systems while maintaining protection and isolation.
- TPT allows for self-managed direct guest VM host memory translation, providing native address translation performance.
- TPT maintains protection and isolation using a new hardware component that enforces isolation for virtual machines accessing physical pages.
- The TPT design is backwards compatible and easy to integrate into existing systems.


## USENIX ATC '23 - Efficient Memory Overcommitment for I/O Passthrough Enabled VMs via Fine-grained...

URL: [https://www.youtube.com/watch?v=IeDlXZLyXaA](https://www.youtube.com/watch?v=IeDlXZLyXaA)


- The transcript is from a conference presentation.
- The speaker worked on memory commitment in VMS at Alibaba group.
- Memory commitment helps mitigate inefficient memory resource utilization in VMS.
- DMA (Direct Memory Access) is an important part of virtualization systems, especially for high-performance RDMA applications.
- A contradiction exists between memory commitment and DMA: when a page is reclaimed, it can cause a DMA failure if the IOP table entry is missing.
- Solutions to this problem include adding paid support hardware or monitoring DMA buffer allocation within the guest.
- The speaker discusses two software solutions, both of which require dedicated hardware and still face memory swapping overhead.
- A method called "three-page reporting" is mentioned as a way to get a report of free pages from the hypervisor without guest intervention.
- The goal is to make MSA (Memory Scaling Architecture) memory reformatting and password coexist, ensuring hardware compatibility and guest compatibility for easy deployment in existing systems.
- Wiprobe, a tool used for memory reclamation, contains three parts: wave probe data manager, memory formation routine, and wave probe injector guest module.
- A rule-based software isolation method is used to prevent harmful code use.
- The memory reclamation process involves synchronization problem handling.
- An experimental evaluation of the tool is conducted based on a hardware architecture with an Intel CPU and a cumulus hypervisor host.
- The wave probe significantly outperforms page ballooning in terms of time cost.
- Limitations of the work include its specificity to x86 architecture and Linux-based OS.


## USENIX ATC '23 - LPNS: Scalable and Latency-Predictable Local Storage Virtualization for...

URL: [https://www.youtube.com/watch?v=iD4CdPmtagU](https://www.youtube.com/watch?v=iD4CdPmtagU)


- The transcript is from a presentation about LPS (Latency Predictable Storage) NVMe virtualization.
- Background motivation includes the limitations of current storage virtualization mechanisms in providing accurate latency predictability and Quality of Service (QoS) control for multitude workloads with different QoS requirements.
- The proposed architecture utilizes a key component called LBNs (Latency Bound Network Stacks).
- Implementation details include micro-benchmark and application benchmark evaluations, demonstrating that LPNs provide reliable latency predictability and QoS control for virtualization scenarios in real-world applications.
- Overhead issues are discussed, focusing on the challenge of removing additional bottleneck latency caused by network devices and complex network topologies in data centers.
- The presentation concludes with a summary of LPS providing predictable latency QoS control for cloud storage while optimizing performance and reducing costs compared to traditional software-level virtualization designs.


## USENIX ATC '23 - P2CACHE: Exploring Tiered Memory for In-Kernel File Systems Caching

URL: [https://www.youtube.com/watch?v=oqm207ZscPg](https://www.youtube.com/watch?v=oqm207ZscPg)

1. The speaker is presenting at State University New York Hampton on the topic of exploiting memory, internal file system, and casting strong work in storage technologies.
2. They mention Ling Fung Xiang from Jarrow University Texas Arlington and observe trends in storage technologies.
3. The first trend mentioned is that storage devices are becoming increasingly fast, with traditional rotating base HDDs evolving into land-based SSDs.
4. The speaker introduces the concept of worldtime memory, a type of cell-based storage device that exposes a memory-like interface and operates at byte-addressable levels.
5. A concrete example is given using Intel's Optane persistent memory and its test version, esd4, which leverages bi-directional adjustability to improve performance in the software stack.
6. The speaker highlights that software overhead has become dominant in storage stacks and uses hd4 as an example of a traditional kernel file system unable to fully explore available PM boundaries.
7. A comparison is made between the est4 test file system's performance and ht4 text, showing significant improvements with esd4 achieving 25 clicks per second for hour-sized 64k IO operations.
8. The speaker then lists several proposed solutions to address challenges in leveraging bi-directional adjustability and ensuring crash consistency while maintaining high performance.
9. These proposed solutions include East Vertex SFS, text Nova, stratum split FS, and a specialized file system tailored for persistent memory systems.
10. The speaker emphasizes that the biggest roadblock to these PM specialized file systems is their maturity level and the time it will take for them to become production-ready.
11. Existing well-tested and production-ready kernel file systems need to evolve effectively to harness the performance benefits of new storage device characteristics.
12. The presentation introduces PSquare cash, a novel kernel casting mechanism designed specifically for PM specialized systems, offering instant data durability, strong consistency, and high performance without requiring application modification or radical system redesign.
13. PSquare cash is open-source on GitHub and employs a rewrite distinguishable memory hierarchy, lightweight journaling mechanism, and PM's light adjustability to speed up data updates.


## USENIX ATC '23 - Revisiting Secondary Indexing in LSM-based Storage Systems with Persistent Memory

URL: [https://www.youtube.com/watch?v=oqQlKjBiwM4](https://www.youtube.com/watch?v=oqQlKjBiwM4)


- The transcript is from a conference presentation about improving the performance of secondary indexing in RSM-based storage systems.
- RSM3, a widely adopted storage engine, has high write performance but inferior read performance due to its multilevel structure.
- Recent research suggests that advanced storage devices like ASM3 can handle heavy computing overhead, but they require high rate performance. Many database applications also require higher query performance.
- Indexing is an important technique for improving query performance. However, it can be inefficient in LSM3 due to consistency issues between the secondary index and primary table.
- The presentation introduces a new calculator pair approach for blind white buffering in RSM3, which improves performance by reducing read data.
- The presenter also discusses two strategies for handling many database systems that tend to use synchronous strategy or validation strategy for secondary key updates.
- The presentation suggests using persistent memory (PM) for secondary indexing due to its addressability, comparable latency to DRAM, and data persistency.
- However, directly adopting PM index for secondary indexing can be inefficient due to nonunique secondary keys and low data locality.
- The presenter introduces PS3, a PM-based secondary index mechanism that uses a specific layer value secondary key and hybrid hash table with lightweight validation approach.
- PS3 also proposes two optimization techniques for nonindex query level region error trace feature.
- The presentation compares the performance of various secondary indexing approaches, including LSM-based, PM-based, and Composite Index log structure approach.
- The presenter concludes that precise steel (PS3) outperforms PM-based secondary index due to its good locality for searching secondary entries.


## USENIX ATC '23 - Zhuque: Failure is Not an Option, it’s an Exception

URL: [https://www.youtube.com/watch?v=yC_oMzOb02Q](https://www.youtube.com/watch?v=yC_oMzOb02Q)


- Presenting research on a simple pre-programming model for persistent memory systems.
- Uses flush-fail semantics, similar to EADR/GPF model.
- Claims to require little effort from application developers and performs at least 3x faster than prior work.
- Discusses the issues with naive approach of making program persistent by putting it in persistent memory.
- Introduces three groups based on programming models: common transactional model, relaxed failure atomicity model, and whole system persistence model.
- The transactional model imports traditional ACID transaction database systems but has restrictions on locking semantics.
- The relaxed failure atomicity model divides the program into regions and uses runtime tracking of dependencies between threads.
- The whole system persistence model expects system to deliver interrupt in a specific order when power failure occurs.
- Discusses a new programming model called 'whole process persistence model' which transforms memory allocated for a process to persistent memory on power failure.
- This model is implemented using libsy based runtime work, which is interposed and intercepts arguments to accomplish the goal entirely transparently to the application.
- Performance results show moderate improvement over prior work with some overhead versus native implementation.


## USENIX ATC '23 - EnvPipe: Performance-preserving DNN Training Framework for Saving Energy

URL: [https://www.youtube.com/watch?v=RfAq1JbHbXI](https://www.youtube.com/watch?v=RfAq1JbHbXI)


- Christ talks about the impact of DNN training and inference on carbon emissions.
- The rapid expansion of AI is causing significant energy consumption, leading to a larger carbon footprint.
- Previous approaches have aimed at saving energy during DNN training by using GPU Dynamic Voltage Frequency Scaling (DVFS).
- This method seeks the optimal streaming multiprocessor (SM) and memory frequency for the GPU.
- However, reducing SM frequency can lead to a trade-off between energy saving and performance degradation.
- The speaker presents mvpipe, a performance-preserving DNN training framework that saves energy.
- mvpipe is implemented as a library in PyTorch and has three main components: a profiler, a scheduler, and a frequency planner.
- The profiler profiles the performance and energy trend of the pipeline stage.
- The scheduler schedules the pipeline units to maximize energy saving.
- The frequency planner reconfigures the SM frequency to minimize performance degradation.
- The goal is to maximize energy saving, preserve accuracy, and minimize performance degradation.


## USENIX ATC '23 - Decentralized Application-Level Adaptive Scheduling for Multi-Instance DNNs on...

URL: [https://www.youtube.com/watch?v=6ToXzky1Dl4](https://www.youtube.com/watch?v=6ToXzky1Dl4)

1. Introduction of decentralized application Level scheduling for mobile devices.
2. Discussion on limited resources and compatibility issues in mobile environments.
3. Presentation of a DNA network profiling model to optimize power consumption and performance.
4. Highlight on the challenges of proper assignment of top applications for performance enhancement.
5. Mention of privacy concerns with apps tracking user data.
6. Proposal of using GPU accelerators for AI tasks in mobile devices.
7. Discussion on the importance of scheduling for efficient computing and power consumption.
8. Introduction to research questions focusing on offline algorithms, semisupervised deep reinforcement learning, and decentralized scheduling.
9. Mention of a paper presenting a latency-inference DNS model and a power model for OS operating systems.
10. Discussion on the need for user level solutions to deal with OS influence on execution.
11. Introduction of a third research question focusing on decentralized scheduling in open mobile systems.
12. Mention of a paper reviewing previous work and proposing a global optimization solution for multitenant scheduling.
13. Discussion on the use of software and hardware for testing in the experiments.
14. Presentation of three groups of experiments comparing different DNS models under various conditions.
15. Mention of machine learning based decision model for decentralized scheduling.
16. Conclusion emphasizing the importance of privacy and performance maintenance in mobile applications.


## USENIX ATC '23- UnFaaSener: Latency and Cost Aware Offloading of Functions from Serverless Platforms

URL: [https://www.youtube.com/watch?v=Yk9N5Ui6oaI](https://www.youtube.com/watch?v=Yk9N5Ui6oaI)


- Serverless computing is a popular and growing field.
- Many organizations are using serverless applications in some form.
- Azure workloads from 2019-2020 showed a majority of applications had one function, with a significant growth in workflow applications.
- There is a proposal to leverage unused capacity in virtual machines (VMs) for serverless functions, which could reduce costs and improve efficiency.
- Serverless functions are typically stateless and event-driven, executing wherever there is available resource infrastructure.
- The design of applications with a degree of disaggregation can help migrate computational functions everywhere and communicate with the rest of the system.
- There is a trend towards building complex applications with serverless functions, which can help manage critical path performance.
- A high-level idea is to build a system that can change existing serverless platforms to better utilize resources and lower costs. This would involve offloading functions to various hosts, including VMs, and using a scheduler to determine the best offloading scenario.
- A pop messaging system could be used to communicate between different components of this system.
- The system would aim to optimize cost and latency, and would need to consider performance jitter and the cost associated with moving data around.
- The system would also need to monitor resource availability and predict future resource availability for offloading.
- The system would not add anything critical to the path or support provider schedulers, but would aim to improve performance and reduce cost.


## USENIX ATC '23 - LLFree: Scalable and Optionally-Persistent Page-Frame Allocation

URL: [https://www.youtube.com/watch?v=yvd3D5VOHc8](https://www.youtube.com/watch?v=yvd3D5VOHc8)

1. A new allocator, LA3, was developed by a well-known project for scalable and optionally persistent memory management.
2. The problem: Many memory management subsystems were designed for single core systems with low memory capacity. However, modern systems have multiple CPUs accessing memory in parallel and larger memory capacities with different properties like persistency.
3. Existing allocators can become bottlenecks due to contention data structures. For example, the Linux page frame allocator manages physical memory and supports huge pages, but it can suffer from performance bottlenecks due to page fragmentation.
4. The new LA3 allocator aims to address these issues by being designed for multiple cores and optionally supporting persistency. It avoids memory sharing and uses atomic instructions for updates.
5. The LA3 allocator is log-free, which helps with scalability and performance. It uses a large bit field for managing pages, with each 4 KB page represented by a single bit.
6. The allocator also uses an index-like data structure to group bits together, improving search times for free pages.
7. For persistency, the LA3 allocator uses Atomic instructions for updates and ensures crash consistency without using logs.
8. Performance benchmarks show that the LA3 allocator has a consistent allocation time independent of the number of cores allocating in parallel. It is significantly faster than the Linux allocator for huge page allocation.
9. The LA3 allocator also handles fragmentation well, able to recover entire huge pages over time and avoid unnecessary checks that can slow down performance.


## USENIX ATC '23 - SingularFS: A Billion-Scale Distributed File System Using a Single Metadata Server

URL: [https://www.youtube.com/watch?v=bjzU3RhvBXg](https://www.youtube.com/watch?v=bjzU3RhvBXg)


- The transcript is from a conference discussing a distributed file system using a single medium server.
- The motivation behind this is the dominance of distributed file systems in modern data centers, and the desire to scale while reducing TCO.
- A single medium server is capable of managing billions of files, as demonstrated by Alibaba's use of a Billy scale file system.
- However, existing solutions fail to fully utilize the performance capabilities of new hardware, such as RDMA NICs and persistent memory.
- The speakers identify three challenges contributing to this performance gap: crash consistency overhead, concurrency control in shared directories, and scalability.
- The proposed solution is Singular FS, a billion-scale distributed file system using a single medium server, focusing on optimizing medium storage methods and operation methods.
- The key design features of Singular FS include logfree method operations, hierarchical concurrency control, and hybrid inode partitioning.
- Logfree method operations are used to classify and handle different types of operations, eliminating the need for additional crash consistency costs.
- Hierarchical concurrency control is used to minimize critical areas in double node operations and eliminate transaction conflicts.
- Hybrid inode partitioning ensures locality in file operations and delegates requests to corresponding physical nodes.
- The evaluation of Singular FS shows comparable latency to local PM file systems and lower latency than distributed file systems for certain operations.
- Singular FS also demonstrates higher throughput per node compared to existing distributed file systems.


## USENIX ATC '23 - The Hitchhiker's Guide to Operating Systems

URL: [https://www.youtube.com/watch?v=crWJEi6udNU](https://www.youtube.com/watch?v=crWJEi6udNU)


- The transcript is from a conference presentation about teaching an operating system course.
- The presenter notes that one reviewer found the paper on teaching operating systems interesting, but thought it could be improved.
- The presenter mentions a problem with the textbook used, stating that even though it's great, it doesn't fully address the needs of students who might become top-notch system researchers.
- The presenter suggests using the OSDI book and provides a reflection on a missing plane system class.
- The presenter proposes an interesting program assignment: Tower of Hanoi, which they expect will be challenging due to its recursive nature.
- The presenter discusses the concept of a state machine in programming and operating systems, and how it can help in understanding and debugging systems.
- The presenter mentions that an operating system is a state machine built on host programs, and that understanding this can provide a refreshing perspective.
- The presenter talks about the use of process APIs and system calls like fork, exit, and exec from a state machine perspective.
- The presenter suggests using a state machine to teach debugging, providing examples of state machine trace and debugging tools like address sanitizer and thread sanitizer.
- The presenter mentions that the operating system course should cover process, thread, and storage, with Three Easy Pieces as an implementation example.
- The presenter discusses the importance of understanding end-to-end stories in system calls and how a state machine model can help.
- The presenter suggests building a toy emulator to clarify concepts mathematically, and mentions the Unix philosophy of piping output to another command.
- The presenter briefly talks about the use of a model checker for exhaustive checking and verification of system behavior.
- The presenter mentions that the course has received positive feedback and is popular in mainland China.


## USENIX ATC '23 - Accelerating Distributed MoE Training and Inference with Lina

URL: [https://www.youtube.com/watch?v=Vsb4j6hHAaA](https://www.youtube.com/watch?v=Vsb4j6hHAaA)


- Presenter's name is Xiaoming from City University of Hong Kong.
- The presentation is about a mixture expert system called Lena, a joint work with City University of Hong Kong and Chinese University of Hong Kong.
- Moe (Mixture of Experts) is an example model paradigm that comprises several expert gating networks assigning weights to expert outputs.
- Moe architecture is sparsely activated, selecting only certain experts for processing instead of computing the complete graph. This benefits from the sparsity of computation.
- The number of experts can be increased without significantly increasing the computation cost, allowing for a larger model with lower computation cost.
- Moe has shown great potential in NLP tasks using Transformer models. Google's Glam Moe model family outperforms GPT3 in 29 language tasks.
- Distributed systems are used to achieve efficient training and inference in Moe, which involves another parallelism called expert partisan.
- However, this also introduces additional communication costs as data samples may need to be routed to different devices' gating networks and experts.
- The size of data transfers in Transformer-based Moes can be large due to the architecture of the Moe Network and the expert networks.
- An experiment with different scale Moe models and architectures found that the overhead (Ottawa) takes an average of 30-34 steps, which is significant.
- The bottleneck in Moe performance is identified as the Moe layer, which becomes a performance bottleneck due to the exponential computation restart required for the original sequence.
- Asynchronized blocking operations and data transfer operations also contribute to the performance bottleneck.
- The Slowdown Factor varies and cannot be determined due to the Black Box nature of GPUs. It has been measured to be up to four times the maximum in some cases.
- Inference in Moe is biased towards expert popularity, which is purely data-driven. This can lead to imbalanced device loads.
- A design choice for training stage is proposed to prioritize avoiding network bandwidth sharing and minimize blocking periods.
- Tensor partitioning is proposed as a solution to overcome the challenge of communication primitives that cannot be preempted easily.
- The challenge is to control resource sharing among GPU operations.
- The proposed solution involves using tensor partitioning to reduce the Micro Ops, which can always prioritize o2o whenever ready and reduce microop execution time.


## USENIX ATC '23 - SmartMoE: Efficiently Training Sparsely-Activated Models through Combiningand...

URL: [https://www.youtube.com/watch?v=iGDt-nzTofY](https://www.youtube.com/watch?v=iGDt-nzTofY)


- The transcript is from a conference presentation about the work conducted at Pacman lab, Qinghao University.
- The team worked on training sparsely activated models more efficiently by combining offline and online parallelizations.
- Larger models tend to yield higher accuracy in downstream tasks, but scaling these models is constrained by computation resources.
- Mixture of Experts (MoE) is proposed as a promising solution for scaling large models without adding computation.
- The challenge is that increasing model size also means increased computation. MoE aims to make this process more efficient.
- MoE consists of many expert sub-networks, and the training process involves activating a subset of these experts to prevent an increase in computation.
- The team explored hybrid parallelism for MoE models, which requires system expertise to finetune the best configuration.
- Existing works have failed to handle MoE's imbalance and dynamic workload property, leading to overloaded experts and low GPU utilization.
- The proposed smart MoE is a dedicated automatic parallelization system designed for MoE models, which understands the limitations of existing works.
- Smart MoE provides an enlarged space for hybrid parallelism support and a two-stage automatic polarization approach to handle dynamic workload efficiently.
- The two-stage approach includes an offline stage that constructs a comprehensive search space and obtains a candidate pool, and an online stage that selects and improves the plan from the pool.
- The system was tested with various scenarios using three clusters of different GPUs, network bandwidth, skill models, and MoE swing models.
- Smart MoE was compared to four strong baselines, including Deep Speed MoE, Faster MoE, and TAO, achieving excellent results across different model structures and clusters.


## USENIX ATC '23 - MSRL: Distributed Reinforcement Learning with Dataflow Fragments

URL: [https://www.youtube.com/watch?v=f14YBz2v-OU](https://www.youtube.com/watch?v=f14YBz2v-OU)


- The transcript is from a conference presentation on MSRL, a distributed reinforcement learning system.
- The presenter discusses the challenges in RL training systems, including large models, accelerating the entire training loop, and handling diversity of algorithms.
- The first challenge is addressed by using a non-distributed approach, which can handle larger models efficiently.
- The second challenge is tackled by using hardware acceleration, specifically GPUs.
- The third challenge is handled by developing an actor-based system, which can be deployed on various types of hardware.
- The presenter then introduces MSRL, a system that decouples algorithm specification and operational execution.
- This is achieved through three key technologies: defining a computation data flow graph, accelerating the data flow graph on heterogeneous devices, and supporting flexible distribution policies.
- The presenter uses PPO as an example of how MSRL can be used to develop algorithms.
- MSRL generates fragments based on information provided by the distribution policy.
- The system architecture includes a continent coordinator, fragment generator, fragment dispatcher, execution backends, and a fragment optimizer.
- The presenter concludes by sharing experiment results that demonstrate MSRL's efficiency and scalability compared to other systems.


## USENIX ATC '23 - Beware of Fragmentation: Scheduling GPU-Sharing Workloads with Fragmentation...

URL: [https://www.youtube.com/watch?v=-37_clawjdc](https://www.youtube.com/watch?v=-37_clawjdc)


- Joint work by HKUST and iPAPA on resource management scheduling for GPU cluster.
- Agenda: background, GPU sharing fragmentation, machine learning cluster popularity, machine learning workload driven development.
- GPU cluster provides machine learning service with general architecture that satisfies different user requirements and supports a wide range of workloads including training and influence evaluation.
- Specific focus on the resource scheduling layer responsible for managing ML task containers and assigning them across a heterogeneous cluster with thousands of CPU/GPU servers with diverse capacity.
- Commonly observed low GPU utilization despite the cluster's capability to host thousands of GPUs.
- Illustration of medium utilization across nodes, with two out of eight GPUs showing usage, and the rest mostly at 50% utilization.
- Reference to a paper published at NSDI 2020 by Alibaba Cloud on their machine learning service.
- Introduction of a solution called GPU sharing (or transition share) that enables multiple tasks to run concurrently on GPUs in a multi-time multiplex manner.
- Related work includes framework level modification, Coda API interception, and hardware methods like Nvidia MIG.
- Measured and simulated results showing that the workload could utilize twice as many GPUs without sharing, but GPU sharing is not a silver bullet solution.
- Analysis of the cluster with 1000 nodes and 6000 GPUs hosting AI tasks, showing that around 50 tasks require one GPU, indicating insufficiency.
- Observation of stranded GPUs due to insufficient CPUs, leading to unexpected scheduling failures despite sufficient GPU quota.
- Work aimed at addressing fragmentation-induced resource utilization.
- Existing approach: packing limitation and mitigation through consolidating tasks onto one node and freezing resources.
- Classical bin packing formulation problematic for GPU sharing workload scheduling.
- Introduction of a new approach to address the fermentation problem in scheduling GPU sharing workloads.
- Definition of fragmentation, its source, and an example of insufficient GPUs and stranded GPUs contributing to fragmentation.
- Proposed solution: Fermionic Scheduling Gradient Descent (FSGD), a statistical measure that quantifies expected unallocated GPU resource given a target workload distribution.
- FSGD outperforms traditional methods in reducing unallocated GPUs and utilizes more GPU resources compared to the best-fit policy.
- Implementation of FSGD as a pluggable component in Kubernetes using a scheduling framework, with a high-fidelity event-driven tree simulation for replaying traces collected from real kubernetes clusters.


## USENIX ATC '23 - Towards Iterative Relational Algebra on the GPU

URL: [https://www.youtube.com/watch?v=NUIA_c-dOzI](https://www.youtube.com/watch?v=NUIA_c-dOzI)


- The transcript is from a conference discussing iterative relational algebra and its use in GPU environments.
- The speaker introduces data logic (data log) and iterative relational algebra, explaining how they are used to compute the transitive closure of a graph.
- The speaker mentions that data log rules are simple and can be used in various fields, including machine learning and detective databases.
- The iterative relational algebra is used to compute the transitive closure using two rules: one for the base case and another for recursion.
- The iterative relational algebra is then compiled into common relational algebra primitives like Union, projection, rename, and join.
- Joint operation in relational algebra can generate duplicate tuples, which can be computationally expensive to remove.
- Data log programs can be parallelized using modern data log implementations such as Souffle thread parallel implementation and DP array target GPU parallel GPU parallelism.
- The speaker then discusses two popular join algorithms: short merge join and hash join.
- The speaker also mentions the importance of handling duplicate tuples in the iterative relational algebra algorithm.
- The transitive closure operation is then demonstrated using a parallel iterative relational algebra, with the algorithm stopping when no new paths are found.
- The speaker introduces an open addressing based approach for hash table implementation on GPUs.
- The speaker also discusses the importance of handling memory overhead in CUDA libraries like cuDF and Souffle.
- Finally, the speaker summarizes their contributions to high-performance GPU HTBL iterative relational algebra and efficient GPU memory management systems.


## USENIX ATC '23 - VectorVisor: A Binary Translation Scheme for Throughput-Oriented GPU Acceleration

URL: [https://www.youtube.com/watch?v=TElCneM9UxQ](https://www.youtube.com/watch?v=TElCneM9UxQ)


- Sam is a 6-year PhD candidate at Princeton.
- GPU programming has become more accessible due to cloud availability and falling prices.
- However, GPU programming can be complex due to the need for memory coalescing, divergent control flow, and different hardware architecture.
- High-level DSLs and libraries exist but may not fit all workloads well.
- Low-level frameworks like CUDA or OpenCL have their own challenges and potential issues.
- GPU programming model is notably different from typical programming models.
- WebAssembly could be a solution for easier GPU programming, as it supports multiple languages and provides memory isolation.
- The speaker proposes a new GPU programming model that could accelerate existing programs without modification, providing backwards compatibility and cross-vendor support.


