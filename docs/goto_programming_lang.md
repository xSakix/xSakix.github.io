## Composing All The Things with Kotlin Multiplatform • Garth Gilmour • GOTO 2023

URL: [https://www.youtube.com/watch?v=iq2tTtG3zs4](https://www.youtube.com/watch?v=iq2tTtG3zs4)

1. Introduction to JetBrains' Compose multiplatform for building cross-platform UIs
2. Kotlin Multiplatform Mobile (KMM) enables sharing business logic and data between iOS, Android, and JS
3. Compose for Desktop allows sharing UI code across desktop and mobile devices
4. Shared code can be up to 60% using KMM and Compose
5. Jetlag demo showcases UI sharing across iOS, Android, and web browsers
6. Compose multiplatform provides value proposition through UX consistency, simpler development, and less code
7. No live coding due to jet lag during the conference.
8. Ask the presenter for demonstrations and code changes.


## The Reflex Architecture • Ben Kolera • YOW! 2019

URL: [https://www.youtube.com/watch?v=5ACqm2ee-XI](https://www.youtube.com/watch?v=5ACqm2ee-XI)

1. Reflex framework presentation: a new functional reactive programming language for web applications
2. The creator aims to make it easier and more powerful than existing libraries
3. Influenced by Elm, PureScript, and other functional languages
4. Lazy evaluation and type safety
5. TypeScript compatibility with Babel support
6. Compiles to JavaScript and uses React as the underlying view library
7. Flexible architecture for customizing the language
8. Plans for better integration with external libraries and frameworks
9. A workshop will demonstrate practical examples of Reflex in action.
10. Workshop setup requires VirtualBox or a downloadable virtual machine image.
11. Set up early to avoid last-minute issues before the workshop starts.


## Scodec for Scala 3 • Michael Pilquist • YOW! 2020

URL: [https://www.youtube.com/watch?v=Uo9S4iKw8NA](https://www.youtube.com/watch?v=Uo9S4iKw8NA)

1. Discussing the talk's purpose: providing an update on Dotty, the new version of Scala 3
2. Dotty's compatibility with existing Scala libraries and tools
3. Over 85% of standard library migrated to Dotty
4. Many popular libraries compatible or in the process of being made compatible
5. More open-source ecosystem adopting Dotty support, such as Cats Effect 3
6. Continuous improvement on compatibility story over time
7. Encouragement for users to try Dotty and seek help from the community when needed.


## Jakarta EE 10: Modern & Lightweight Cloud Application Development • Ivar Grimstad • GOTO 2023

URL: [https://www.youtube.com/watch?v=2749IF7gAbI](https://www.youtube.com/watch?v=2749IF7gAbI)

- Jakarta EE 9 is about simplifying the namespace
- Replaced CDI 2.0 with CDI 2.1 as default version
- Reduced overall size of API by removing unused APIs and combining specifications (specs)
- Jakarta Starter available for easier integration
- Simplified naming conventions such as replacing 'JAX-RS-RI' with just 'Jersey'
- LinkedIn course on Jakarta EE available via a QR code or 24-hour free subscription (contact author for access if no subscription)


## Concurrency Abstractions for Application Security • Bram Verburg • GOTO 2023

URL: [https://www.youtube.com/watch?v=snCylAGgcxw](https://www.youtube.com/watch?v=snCylAGgcxw)

1. Discussion on concurrency and supervision in Erlang, a functional programming language designed for telecom applications with high availability requirements.
2. Erlang's unique features include concurrency through lightweight processes and message passing instead of threads to avoid shared memory issues.
3. Supervision trees provide an automatic approach to error handling by monitoring child processes and taking actions upon failure or crash.
4. Concurrent supervision enhances reliability further by introducing a layer of concurrency to the supervisor itself.
5. The speaker thanks their employer for enabling contributions to the community, such as speaking at this event.
(no context provided beyond the given transcript).


## Genetic Algorithms in Elixir • Sean Moriarity & Bruce Tate • GOTO 2023

URL: [https://www.youtube.com/watch?v=vS1_Z4xaeqQ](https://www.youtube.com/watch?v=vS1_Z4xaeqQ)

1. Discussion centered around Bruce Tate's book "Programming Elixir 2: Functional | Concurrent | Pragmatic" and Sean Moriarity's "Machine Learning in Elixir".
2. Bruce shared his background in C++ and Java, before discovering functional programming through Erlang.
3. Bruce explains how a genetic algorithm works using an example of finding the optimal path in a maze.
4. Sean highlights how Elixir can be used for machine learning tasks by creating custom libraries and integrating with other tools like TensorFlow.
5. Bruce and Sean agree on the importance of educational resources to introduce developers to Elixir's capabilities.
6. The book club conversation celebrates Elixir's growth within its ecosystem, with ongoing developments in functional programming and concurrency.


## Problem Solving with Erlang & the BEAM • Robert Virding & Francesco Cesarini • GOTO 2023

URL: [https://www.youtube.com/watch?v=I7A5Y5wHDHI](https://www.youtube.com/watch?v=I7A5Y5wHDHI)

1. The discussion focuses on the future of Python.
2. Francesco Cesarini and Robert Heaton predict continued usage and growth for Python in various fields.
3. Concurrency, parallelism, and ease of use are highlighted as key features of Python.
4. Francesco expresses excitement about Python's ability to adapt to change, while acknowledging potential changes over time.
5. The speakers believe that Python will continue to have a significant impact in the next decade, despite possible transformations.


## Zig Build System & How to Build Software From Source • Andrew Kelley • GOTO 2023

URL: [https://www.youtube.com/watch?v=wFlyUzUVFhw](https://www.youtube.com/watch?v=wFlyUzUVFhw)

1. Discussion on software distribution and installation methods
2. Importance of configure steps during compilation from source
3. Caution against using root when installing software
4. Introduction to Zig, a programming language with focus on performance, safety, and portability
5. The Zig Build System for faster builds and improved tooling
6. Call for donations to support the non-profit Zig Software Foundation through company sponsored donation matching programs.


## How to Do Embedded Development with Rust • Steve Klabnik • GOTO 2023

URL: [https://www.youtube.com/watch?v=7lHtXkYnip8](https://www.youtube.com/watch?v=7lHtXkYnip8)

1. Advice on low-level programming for software engineers: understand the hardware, learn assembly and Rust language.
2. Recommendation to start with a microcontroller development board like Arduino or similar board.
3. Suggestion to read datasheets and use online resources like DigiKey and Amazon-like platforms for documentation.
4. Mention of resources for documentation, such as DigiKey and Amazon-like platforms for embedded devices.
5. Recommendation to learn Rust through Mozilla's docs and Jason Kegler's book "Learn Rust with microcontrollers".
6. Suggestion to use the CMSIS pack from ARM for Cortex-M processor reference manuals.
7. Sharing of a resource, "The Definitive Guide to Data Structures" for a deeper understanding of data structures in low-level programming.


## Concurrency Oriented Programming in a Modern World • Robert Virding & Francesco Cesarini • YOW! 2022

URL: [https://www.youtube.com/watch?v=A-f7md5exaE](https://www.youtube.com/watch?v=A-f7md5exaE)

- Fault tolerance in computing involves designing systems to continue operating despite component failures
- Unix and Linux are examples of fault-tolerant operating systems, with processes that can be restarted or handled by the OS if they crash
- Airline reservation systems are designed for fault tolerance with smaller components potentially crashing without causing a system failure
- Handling errors consistently across programs allows for smooth recovery in case of individual single small failures
-To achieve true fault-tolerance, two physically separated machines should be used.


## Scala Implicits Revisited • Martin Odersky • YOW! 2020

URL: [https://www.youtube.com/watch?v=dr0PUXQhg3M](https://www.youtube.com/watch?v=dr0PUXQhg3M)

1. The talk focuses on a practical programming language experiment with a 25-year-old research paper as inspiration.
2. Key principles include eliminating superfluous punctuation, reducing boilerplate code, and improving flow for writers.
3. The language adopts the concept of immutable data structure called "flattened trees."
4. Elimination of curly braces, semicolons, parentheses, and colons results in a more natural syntax.
5. Experiment includes an IDE and a static type checker.
6. The language introduces a single punctuation mark: ';'.
7. The language eliminates boilerplate code by replacing `if` statements with prefix notation.
8. The language eliminates braces, allowing the programmer to visually identify scopes through indentation levels.
9. Tooling helps maintain vertical lines on tab stops for region identification.
10. After implementing these changes, the results are considered great in practice.


## Calling Functions Across Languages • Richard Feldman • GOTO 2023

URL: [https://www.youtube.com/watch?v=ZOvxa9aKCCg](https://www.youtube.com/watch?v=ZOvxa9aKCCg)

1. Discussion of using other languages alongside Python, highlighting Go (or Rock as a placeholder) for its concurrency and performance benefits.
2. Demonstration of using Pythons ctypes module to call functions in C and C++ libraries, and FFI for Ruby and JS.
3. Explanation of Go's Cgo functionality, which allows for calling C code from Go.
4. Showcase of Cython for compiling Python into C/C++ extensions, resulting in performance improvements.
5. Overview of Rust-Python integration using the Rust bindgen tool and the Rust-Python FFI.
6. Discussion on gradually transitioning to Go by incrementally replacing portions of code without undertaking a high-risk all-or-nothing project.


## Effective Programming in OCaml • KC Sivaramakrishnan • YOW! 2021

URL: [https://www.youtube.com/watch?v=X28PFYvZ_V8](https://www.youtube.com/watch?v=X28PFYvZ_V8)

1. Talk focused on the OCaml programming language and its concurrency improvements.
2. Traditional approaches using channels, co-routines (CSP), and monads were limited in performance or complexity.
3. Fibers introduced as a new concur parallel paradigm.
4. Multicore library implemented with fibers for better performance.
5. FX library offers simpler concurrency constructs such as spawn, forkjoin, and forkmerge.
6. No context issues mentioned explicitly.
7. Work is open-source, available for installation and usage.
8. Numerous examples provided using FX library.
9. Technical papers published on these topics in ICFP and PLDI conferences.


## Hashing Modulo Alpha Equivalence • Simon Peyton Jones • YOW! 2021

URL: [https://www.youtube.com/watch?v=PltixgJiRrw](https://www.youtube.com/watch?v=PltixgJiRrw)

1. Discussion on a paper about finding the number of distinct hash functions in a table with collisions
2. Collision set problem: find the expected number of hash functions that produce collisions when applied to elements from a universe
3. Two main approaches mentioned: a) use linearity to reduce the universe size b) find the maximum number of independent pairs of values and use probabilistic method
4. The presented algorithm is simple yet efficient, solving the collision set problem with formal reasoning and mathematics for improved efficiency in practical applications.
5. The concept seems obvious now but was not initially evident due to time spent searching for a solution.
6. There appears to be a gap in literature on this topic, as mentioned by one of the speakers.


## Zig Build System & How to Build Software From Source • Andrew Kelley • GOTO 2023

URL: [https://www.youtube.com/watch?v=vKKTMBoxpS8](https://www.youtube.com/watch?v=vKKTMBoxpS8)

1. The presentation discusses building software from source.
2. Using system packages is often the best way to get software, but sometimes it's outdated or not available.
3. Building from upstream source provides the latest version and can fixme.
4. Zig, a modern programming language, has an advanced build system.
5. The speaker highlights building C++ projects with CMakeLists.txt.
6. Zig's build system simplifies complex build systems like CMake.
7. The speaker showcases building Firefox using Zig.
8. Case studies include OpenSSL and NodeJS.
9. Zig enables cross-platform development.
10. Donations are encouraged through non-profit 501c3 organization, Zig Software Foundation.


## An Introduction to Functional Imperative Programming in Flix • Magnus Madsen • GOTO 2023

URL: [https://www.youtube.com/watch?v=2LSOqikNqxM](https://www.youtube.com/watch?v=2LSOqikNqxM)

1. Flex is a new programming language aimed at bridging functional, imperative, and logic programming paradigms.
2. It allows the user to write code in multiple styles within a single expression.
3. It provides unique features like lambda calculus notation, and embedded logic programs.
4. Flex has a visual studio code extension, an online playground, and comprehensive documentation.
5. The language is open-source, ready for early adopters, and its functional and imperative aspects were discussed in detail.
6. Context provided from a presentation about Flex programming language.


## Concurrency Oriented Programming in a Modern World • Robert Virding & Francesco Cesarini • GOTO 2023

URL: [https://www.youtube.com/watch?v=AvA97AB8cAA](https://www.youtube.com/watch?v=AvA97AB8cAA)

1. Concurrency is a fundamental concept in modern computing environments.
2. Traditional sequential programming cannot handle the complexity and performance demands of modern systems.
3. Multithreading and multi-core processors are examples of concurrency principles.
4. Asynchronous I/O, message passing, and actors are important concepts for concurrent programming.
5. Concurrent programming is challenging due to complex interactions between components and race conditions.
6. Building a concurrent language as an afterthought can lead to issues.
7. Learning concurrency principles improves one's overall programming skills regardless of the languages used.
8. Adopting concurrent thinking involves unlearning some concepts and re-evaluating how we work with data.


## Why Static Typing Came Back • Richard Feldman • GOTO 2022

URL: [https://www.youtube.com/watch?v=Tml94je2edk](https://www.youtube.com/watch?v=Tml94je2edk)

1. Static typing has gained popularity in recent years, particularly since 2014.
2. The presentation discusses reasons for this trend and predictions for the future.
3. TypeScript, Rust, and Swift are examples of popular statically-typed languages.
4. Static typing offers advantages such as compile-time errors, better tooling, type inference, and better support for large codebases.
5. Dynamic languages like Python and Ruby are still relevant and widely used but have their drawbacks.
6. There's no evidence supporting a resurgence of dynamically typed languages or gradual typing.
7. The speaker predicts continued growth in popularity for statically-typed languages without gradual typing.


## The Java Agent: Modifying Bytecode at Runtime to Protect Against Log4J • Joe Beeton • GOTO 2022

URL: [https://www.youtube.com/watch?v=ZrGOv44iTC8](https://www.youtube.com/watch?v=ZrGOv44iTC8)

1. Demonstration of deserialization vulnerability in Java Reflection API
2. Exploitation using arbitrary classes and methods
3. Introduction to RASP (Runtime Application Self-Protection) to patch vulnerabilities
4. Showcase of a custom RASP implementation for deserialization protection
5. Disclaimer not to use the custom RASP in production and recommend using available developer resources and scanning tools from control security for secure software development practices.


## Expert Talk: Zig Programming Language & Linters • Andrew Kelley & Jeroen Engels • GOTO 2022

URL: [https://www.youtube.com/watch?v=zKmZmiOU6qE](https://www.youtube.com/watch?v=zKmZmiOU6qE)

1. The discussion involves Andrej Karpathy, a deep learning researcher, and Jeroen Engels, discussing functional programming and the Zig programming language.
2. They begin with comparing functional languages to relational databases in terms of referential indirection.
3. Engels explains that in Zig, function arguments are passed by value, which can be changed inside a function but doesn't affect the original variable.
4. Karpathy highlights the importance of understanding whether the language has pure or impure functionalities.
5. They discuss the role of linting in catching imperative side effects in Zig and how it could improve with better documentation, type systems, and tooling.
6. Engels mentions that functional programming can lead to simpler code due to the lack of mutation and shared state concerns but adds that it doesn't solve all problems.
7. They touch on the subject of referential transparency in functional languages, which enables parallelism and better testing by removing side effects. 
8. Engels describes how data structures in functional programming can be immutable and transformed instead of being modified directly.
9. Karpathy points out that the need for imperative code might arise when dealing with external systems or hardware interaction.
10. They conclude their conversation acknowledging the trade-offs between functional and non-functional languages while appreciating each other's perspectives on programming.


## Deno: The JavaScript Runtime for the Serverless Era • Ryan Dahl • GOTO 2022

URL: [https://www.youtube.com/watch?v=VDKJ1rSj-NI](https://www.youtube.com/watch?v=VDKJ1rSj-NI)

1. Demonstration of Fresh, a new web framework by Mathias Biilmann and the team at ZEIT.
2. Fresh aims to optimize server-side JavaScript for web development and make it faster than current solutions like Create React App.
3. Fresh focuses on performance, simplicity, and size reduction, with an example app weighing 84 kilobytes compared to larger frameworks.
4. Fresh relies heavily on ZEIT's Next.js and Denode infrastructure in the cloud.
5. The team at ZEIT is actively working on server-side optimizations and hiring new members for development.


## BEAM Concurrency in Action • Sasa Juric • YOW! 2022

URL: [https://www.youtube.com/watch?v=A4x6IfceJCM](https://www.youtube.com/watch?v=A4x6IfceJCM)

1. Comparison between Beam and traditional Unix tools for data processing.
2. Beam uses a pipeline-style approach for managing data flow, with side inputs, windowing, and triggering.
3. Beam offers more control over the process compared to black box solutions like yaml driven CI.
4. In Beam, terminating a process leads to automatic transaction abort due to closed sockets being process-owned.
5. With Beam, distributed systems problems can be handled earlier and more easily using existing patterns and messaging systems.


## Rust in Action • Tim McNamara & Richard Feldman • GOTO 2023

URL: [https://www.youtube.com/watch?v=iYJ6bLITZsI](https://www.youtube.com/watch?v=iYJ6bLITZsI)

1. Interview with Tim Parker, co-author of "Rust in Action".
2. The book was written during the pandemic as an outlet for Tim's frustration and as a way to engage with the Rust community.
3. The book covers the fundamentals of Rust, emphasizing safety and security.
4. It aims to teach readers how to think like a Rust programmer.
5. Tim shares his experience of balancing writing the book with family and work commitments.
6. He appreciates feedback from the community and acknowledges that the book might not be perfect but serves as a guide for learning Rust.
7. The authors made an effort to make the examples in the book practical, fun, and educational.
8. Tim encourages readers to share their thoughts on the book and offers help through social media or the book's website.
9. He reflects on his writing process, stating that it was a sacrifice with consequences due to time requirements.
10. The conversation concludes with gratitude and appreciation for Tim sharing his experiences in writing "Rust in Action".


## Intro to the Zig Programming Language • Andrew Kelley • GOTO 2022

URL: [https://www.youtube.com/watch?v=YXrb-DqsBNU](https://www.youtube.com/watch?v=YXrb-DqsBNU)

1. Zig software Foundation aims to improve the craft of software engineering for everyone in the industry.
2. The presentation showcases the benefits of using Zig's CT plus compiler, toolchain, and build system.
3. It simplifies maintenance for existing projects, even if you don't use the language.
4. Zig is a simple yet powerful programming language, excelling in demanding environments.
5. The number of Zig users is growing rapidly.
6. Consider using or sponsoring Zig if you like its contributions to software engineering.
(No context provided beyond the transcript itself.)


## The Perfect Language • Bodil Stokke • YOW! 2017

URL: [https://www.youtube.com/watch?v=vnv8MGIN7A8](https://www.youtube.com/watch?v=vnv8MGIN7A8)

1. Explore new languages to gain different perspectives and prevent becoming a machine yourself.
2. Create an open-source project in each language you learn to give back to the community.
3. Attempt to write a compiler or interpreter to understand how languages work under the hood.
4. Try writing your own programming language to fill a unique niche and contribute to the field.
5. Refresh knowledge by learning at least one new language annually for personal growth and better understanding of current developments.
6. Build tools in various languages to enhance proficiency, expand capabilities, and broaden perspectives.
7. Experiment with different paradigms and explore why certain decisions were made in language design. 
8. Push yourself beyond your comfort zone by learning esoteric programming languages to challenge your understanding of code.
9. Don't restrict yourself to only popular or practical languages, but rather learn what interests you.
10. Collaborate with others and form a community to share knowledge and experiences in learning new languages.


## TypeScript vs KotlinJS • Eamonn Boyle & Garth Gilmour • GOTO 2022

URL: [https://www.youtube.com/watch?v=GlU8ZyJNI7Q](https://www.youtube.com/watch?v=GlU8ZyJNI7Q)

- Kotlin.js allows developers to write frontend code using the Kotlin language
- Kotlin.js provides type safety and tooling for JavaScript
- The compiler converts Kotlin code into optimized JavaScript
- It uses WebAssembly where appropriate, improving performance
- Kotlin Multiplatform facilitates shared business logic across platforms
- Kotlin's null safety may save time in the long run as developers won't need to learn it again later
- Some use cases for kotlin.js include generating HTML or working with non-web apps in manufacturing companies


## Simplifying Systems with Elixir • Sasa Juric • YOW! 2020

URL: [https://www.youtube.com/watch?v=EDfm2fVS4Bo](https://www.youtube.com/watch?v=EDfm2fVS4Bo)

1. Elixir is a functional language based on Erlang and its BEAM virtual machine.
2. The main concepts include pattern matching, immutability, tail recursion, and processes.
3. Elixir offers simplicity for concurrency through lightweight processes that act as green threads.
4. OTP principles provide fault tolerance and scalability via supervision trees, hot code loading, and error handling.
5. Elixir has a strong focus on tooling with excellent testing capabilities and a REPL environment.
6. It offers support for web development through frameworks like Phoenix.
7. The BEAM approach results in benefits such as reduced gaps between local development and production, testability, and system confidence.
8. The speaker is a fan of Elixir and other BEAM languages after using them in production for 10 years.


## Streamlining Large-Scale Java Development Using Error Prone • Sander Mak • GOTO 2022

URL: [https://www.youtube.com/watch?v=C5MBsKZHqrY](https://www.youtube.com/watch?v=C5MBsKZHqrY)

1. Presentation about refaster, a tool for converting SQL to Dataform format.
2. Dataform is a configuration-as-code solution for data infrastructure at Picnic.
3. Refaster helps in adopting and migrating to the Dataform syntax, saving time and effort.
4. Refaster is a fork of AirProm, with improvements focused on ease of use and multiple refactoring rules.
5, Refast can be used as a CLI or as part of Picnic's platform team for improvement.
(no context provided directly.)


## Interview with Louis Pilfold on Elixir Gleam • YOW! 2022

URL: [https://www.youtube.com/watch?v=kDfa7AVeugw](https://www.youtube.com/watch?v=kDfa7AVeugw)

1. The video features an interview with Louise Hu, a maintainer of the Glean programming language.
2. Glean is a new functional language that aims to be easy to learn and use.
3. It has similarities with Scheme, Racket, Lisp, and Python in terms of syntax and philosophy.
4. Glean emphasizes clarity, safety, simplicity, and being friendly towards beginners.
5. The language's type system allows for easier learning but can cause some limitations.
6. Glean has a dynamic module system that provides access to the standard library without any predefined imports.
7. The language focuses on readability with a strong preference for single-line functions and no semicolons.
8. Glean's community is growing and actively working on improving documentation, tutorials, and tooling.
9. The team aims to make the language easier to install and get started with in the future.


## Full-Stack Haskell: From Prototype to Production • Ryan Trinkle • YOW! 2018

URL: [https://www.youtube.com/watch?v=guhrVxY63tg](https://www.youtube.com/watch?v=guhrVxY63tg)

1. Presentation about Obsidian Systems and their projects in Haskell community
2. Introduction to Obsidian's open source package, Obsidian Web
3. Features: Reusable components, type safety, support for server-side rendering, and hot reloading
4. Development of Obsidian Mobile using React Native with GHCJS
5. Motivation to expand the use of Haskell beyond research prototypes into real-world applications in web and mobile development
6. Goal is to make functional programming benefits widely available for significant impact on the world
7. The speaker thanks the audience for their support and encourages continued engagement within the community.


## Building Your Own Compiler The Slightly Easier Way With LLVM • Erik Corry • YOW! 2016

URL: [https://www.youtube.com/watch?v=_XbOTRunqHk](https://www.youtube.com/watch?v=_XbOTRunqHk)

1. Discussed the process of compiling programs into machine code.
2. Explained the need for intermediary representations (IR) during compilation.
3. Introduced LLVM, an open-source compiler infrastructure project.
4. Demonstrated a simple assembler program using LLVM's IR to generate bytecode.
5. Criticized "Compilers: Principles, Techniques, and Tools (The Dragon Book)" for not covering SSA form due to its age. Suggested seeking better compiler learning resources.


## Idioms for Building Fault-tolerant Applications with Elixir • José Valim • YOW! 2021

URL: [https://www.youtube.com/watch?v=mkGq1WoEvI4](https://www.youtube.com/watch?v=mkGq1WoEvI4)

1. Elixir talk overview: language background, unique features, and community growth
2. Erlang VM (BEAM) allows for concurrency through lightweight processes and message passing
3. Elixir is a functional programming language with pattern matching, immutability, and lazy evaluation
4. Elixir's syntax resembles Ruby while retaining the power of Erlang
5. Community growth: 100K+ stars on GitHub, 2000+ libraries, and yearly conferences
6. Popular companies using Elixir: Pinterest, WhatsApp, Moz, Bleacher Report, Netflix, and Udacity
7. Elixir's adoption in education: curriculum in universities and free online resources
8. Alexa language rankings: Elixir consistently ranked above Ruby, Swift, Scala, and Go
9. Pinterest case study demonstrates server cost savings of over $2 million per year after converting to Elixir.


## A Tour of the Modern Java Platform • James Ward & Ryan Knight • GOTO 2022

URL: [https://www.youtube.com/watch?v=BU_zIpQI5Dg](https://www.youtube.com/watch?v=BU_zIpQI5Dg)

1. The talk discusses modern Java ecosystem tools and advancements.
2. Quarkus allows for fast startup times, high throughput, and small memory footprints in cloud-native environments.
3. GraalVM supports polyglot programming, enabling the execution of different languages within a single virtual machine.
4. Native image converts Java applications to native binaries without requiring a JRE or JDK for runtime, leading to faster startup times throughput memory footprint cloud-native environment runtime language virtual machine native binary java application jre jdk polyglot programming.
5. Demo shows GraalVM running JavaScript and Python within Quarkus's context.
6. The speaker shares GitHub link for code examples.
7. No additional questions were asked during the transcript.


## What’s New in F# 5.0 & Beyond • Don Syme • YOW! 2021

URL: [https://www.youtube.com/watch?v=1cqvmiaj6SI](https://www.youtube.com/watch?v=1cqvmiaj6SI)

1. F# is a functional-first, object-oriented, and component-based language.
2. Distinguish between functions (pure) and methods (impure).
3. Use immutable data structures to simplify reasoning about state.
4. Functional programming promotes clarity, simplicity, and readability in code.
5. Embrace some elements of object programming while rejecting OOP's downsides.
6. Learn from both functional and imperative paradigms.
7. Recommendation for learning F# is through a low-cost Udemy course.


## Spring Boot: Up & Running • Mark Heckler & Thomas Vitale • GOTO 2022

URL: [https://www.youtube.com/watch?v=F0BJiE2LnpQ](https://www.youtube.com/watch?v=F0BJiE2LnpQ)

1. Discussion on the book "The Soul of a New Machine" by Tracy Kidder with Thomas Claburn and Mark Heckler.
2. The book is centered around a team at Data General in the 1980s trying to create a new computer.
3. It provides insight into the challenges, culture, and personalities involved in software development during that era.
4. The book's relevance still holds for modern-day developers despite technological advancements.
5. Thomas Claburn shares his connections to the book through his father, who was a computer engineer at Data General.
6. Mark Heckler and Thomas first met on Twitter, a platform they both enjoy engaging with for networking and news sharing.
7. The book can be found in various formats and locations, including online platforms and physical copies.
8. Both guests encourage following Mark Heckler on Twitter to discuss topics like software development and books related to it.


## The Quick Python Book • Naomi Ceder & Luciano Ramalho • GOTO 2022

URL: [https://www.youtube.com/watch?v=7CwmUmQjvYg](https://www.youtube.com/watch?v=7CwmUmQjvYg)

1. Naomi Ceder and Anka Wittenberg introduced Go To: Python by discussing its focus on the Python programming language and its community.
2. They highlighted Guido van Rossum's influence and involvement in previous events.
3. The conference aims to bring together academic researchers, industry experts, and open-source developers for discussions on new ideas and opportunities.
4. Naomi Ceder proposed a session about Python as an embedded language in applications like AutoCAD and Mathematica, showcasing its versatility.
5. Anka Wittenberg suggested discussing how Python is used in the scientific community with the library thing, emphasizing a need for improving the interpreter's performance rather than deep changes to the language itself.
6. A recent PEP proposes redesigning the Python runtime, but there hasn't been significant discussion around it yet.
7. The conference offers both in-person and online participation; use promo code "book club" when registering at gotopia.tech for upcoming events.


## Growing Together with the BEAM • Stavros Aronis & Hans Nahringbauer • Code BEAM 2022

URL: [https://www.youtube.com/watch?v=OXlC6f8indM](https://www.youtube.com/watch?v=OXlC6f8indM)

1. Presentation about Ace, a Swedish telecom operator software
2. Origins in the early 90s as an internal project for management of network elements
3. Initial challenges included lack of tools and programming language to handle concurrent connections
4. Erlang adopted for its fault-tolerant features and scalability
5. Development team has remained stable, with many members staying over 20 years
6. Success factors include a strong team, early adoption of cloud services, and the use of Erlang
7. Ace has offices in Sweden, Finland, and Lithuania, with around 250 employees and an ongoing search for additional Erlang developers to expand the team.


## Expert Talk: What’s Next For .NET? • Hannes Lowette & Martin Thwaites • GOTO 2022

URL: [https://www.youtube.com/watch?v=vzywu1ol-b8](https://www.youtube.com/watch?v=vzywu1ol-b8)

1. The discussion focuses on the history and future of .NET as a development platform.
2. Mark's involvement with .NET since its inception as a response to Java.
3. Evolution from Windows-only to cross-platform capabilities.
4. The significance of open sourcing .NET and contributions from various communities.
5. The role of managed code and garbage collection in making .NET developer-friendly.
6. Challenges of modernizing legacy applications for optimal performance on new hardware.
7. Advancements in observability and metrics to revolutionize monitoring production codes.
8. Excitement about the future of .NET, its speed, and ability to adapt to changing technological demands.


## Life After Business Objects: Confessions of an OOP Veteran • Vagif Abilov • GOTO 2021

URL: [https://www.youtube.com/watch?v=Q2p_iqjfekI](https://www.youtube.com/watch?v=Q2p_iqjfekI)

1. Presentation on functional programming in an insurance company context.
2. Introduction to F# language for type-safe code, simplicity, and conciseness.
3. Use of F# for data processing, data analysis, reporting, and ML models.
4. Moving from traditional OOP approach to a more functional style using F#.
5. Utilization of immutable lists and tuples in F#.
6. Discussion on public members versus private fields and functions for encapsulation.
7. Transition to immutable data structures like Option type or Result type for error handling.
8. Incorporation of functional patterns such as map, filter, reduce, etc. for manipulating collections.
9. Emphasis on writing tests for unit checking.
10. Adoption of FsUnit library for unit testing and type checking benefits.
11. Integration of F# with .NET framework, SQL Server, Excel, and Power BI tools.
12. Use of Apache Spark in a big data environment with Scala and PySpark alongside FSharp.Data package.
13. Implementing functional style for ML models development using ML libraries for F#.
14. Introduction to the concept of monads in the context of insurance claims processing.
15. Integration of functional programming into the existing legacy code base through gradual adoption approach.
16. Use of functional paradigm with Akka.NET library for distributed computing tasks.
17. Publication of F#-based open source project called `FSharp.Climate` on GitHub as a contribution to climate modeling research.
18. Conversion of legacy code from imperative style to functional programming using pattern matching, recursion, and lambda expressions in F#.
19. Discussion of the choice between Clojure and F# languages, with the author preferring F# for its .NET integration capabilities and familiarity with Visual Studio IDE.
20. Sharing of contact details with readers interested in functional programming or seeking to adopt it within their organizations.


## Ready for Rust • Erik Doernenburg • GOTO 2021

URL: [https://www.youtube.com/watch?v=WgLlwjZNEtY](https://www.youtube.com/watch?v=WgLlwjZNEtY)

1. Rust is a systems programming language that aims to provide safety and speed.
2. The talk presented an overview of the Rust ecosystem, tools, libraries, and community resources.
3. Cargo is the package manager for the Rust ecosystem and provides dependency management, documentation, testing, and publishing features.
4. There are various types of crates (Rust packages), including library, binary, example, benchmark, and workspace metadata.
5. Rust has a strong community and provides resources such as official documentation, book, videos, and events like Hacktoberfest.
6. The Rust compiler enforces type safety to prevent common programming errors.
7. LLVM is a low-level virtual machine used by multiple languages, including Rust, leading to potential speed improvements for Rust.
8. An example showcased that under certain conditions, Rust can be faster than C in a specific benchmark scenario.


## #FAIL • Kevlin Henney • GOTO 2021

URL: [https://www.youtube.com/watch?v=Lc13xKEJZTc](https://www.youtube.com/watch?v=Lc13xKEJZTc)

1. Discussion on the importance of learning from past failures and successes in safety management.
2. Lessons can be drawn from multiple industries, such as aviation, healthcare, and manufacturing.
3. The Reason Why (Rasmussen) model highlights three systems: organizational, technical, and human factors.
4. Aviation's Just Culture concept balances accountability with learning from mistakes.
5. UK
6. Safety-Science (SSS) framework helps identify root causes of incidents.
7. Examples from aviation, healthcare, and mining demonstrate.
8. SHARP program for US mining industry encourages reporting accidents to learn.
9. Healthcare failures lead to thousands of preventable deaths annually.
10. Learning from past safety failures leads to safer environments for individuals and companies.
11. Historical observations highlight the lack of learning from history by people or governments.


## Expert Talk: gRPC, Kubernetes & .NET • Mark Rendle & Matt Turner • GOTO 2022

URL: [https://www.youtube.com/watch?v=vzqzLSJWo3k](https://www.youtube.com/watch?v=vzqzLSJWo3k)

1. Discussion on the most significant technological advancements in the last decade, including smartphones and mobile data revolutionizing communication and access to information.
2. The role of the internet and social media platforms such as Facebook and Twitter in connecting people globally.
3. Importance of cryptocurrencies like Bitcoin in decentralizing money systems and their potential for significant economic disruption.
4. Advances in Artificial Intelligence, leading to voice recognition technology, facial recognition, self-driving cars, and machine learning applications.
5. The double-edged sword aspect of these technologies, highlighting both the benefits and potential negative consequences.
6. Need for ethical considerations as we continue developing AI and related technologies.
7. Brief discussion on the future of quantum computing and its implications on security, data encryption, and advancements in various fields. 
8. The debate surrounding gene editing techniques like CRISPR and their potential to eradicate genetic diseases while raising ethical concerns.
9. Discussion on technological advances in medicine, such as prosthetics and bionic limbs that can be controlled by the mind.
10. Mention of space exploration advancements, including reusable rockets like SpaceX's Falcon 9 and missions to Mars.
11. The rise of streaming services and their impact on media consumption, as well as their implications for industries like television and film production.
12. Discussion on the ongoing revolution in renewable energy and its potential to combat climate change by reducing our reliance on fossil fuels. 
13. Brief mention of the YouTuber's upcoming video focusing on technological mistakes, such as the existence of null in computing systems.


## Did We(b Development) Lose the Right Direction? • Stefan Judis • GOTO 2021

URL: [https://www.youtube.com/watch?v=3PmPkZJ22Cc](https://www.youtube.com/watch?v=3PmPkZJ22Cc)

1. Stefan's website rebuild focused on improving accessibility and performance using HTML, CSS, and a minimal amount of JavaScript for functionality only.
2. He shared his journey from being a JavaScript-driven developer to embracing a lighter approach with a better user experience.
3. The site received a green lighthouse score due to the lack of slowing elements like large JavaScript bundles.
4. Stefan encourages developers to use whatever technology they enjoy but advises considering trade-offs associated with different choices.
5. The emphasis should be on building functional websites that work well, rather than focusing solely on trendy technologies.
6. Slides from the presentation are available at Stefan's website, which he owns and promotes.


## Expert Talk: Native vs Cross-Platform • Sebastiano Poggi & Carl-Gustaf Harroch • GOTO 2022

URL: [https://www.youtube.com/watch?v=cNXDpl-rfrM](https://www.youtube.com/watch?v=cNXDpl-rfrM)

1. Discussion about the Flutter framework for mobile app development, its features, and community support.
2. Comparison with Swift for iOS development.
3. Explanation of Dart, the programming language used in Flutter.
4. Flutter's cross-platform capabilities.
5. Sebastiano Poggi shares his views on mobile app development trends.
6. Comparison between Flutter and React Native.
7. Importance of being familiar with multiple platforms for developers.
8. Possible future collaborations between Google and Apple, focusing on similar mindsets and technologies.


## Programming Language Stereotypes • PJ Hagerty • GOTO 2021

URL: [https://www.youtube.com/watch?v=3o_nCe67wA4](https://www.youtube.com/watch?v=3o_nCe67wA4)

1. Addressing diversity and inclusion in tech requires self-evaluation to identify biases.
2. Forget about common myths, legends or stereotypes associated with specific roles within the industry.
3. Mentor and support people who don't resemble you, specifically those underrepresented groups.
4. Bringing in more diverse perspectives leads to better technology creations.
5. Focus on building great things in tech while promoting diversity and inclusion principles.


## Expert Talk: Functional Programming • Russ Olsen & Christian Romney • GOTO 2022

URL: [https://www.youtube.com/watch?v=AbCWHZljhkM](https://www.youtube.com/watch?v=AbCWHZljhkM)

1. Russ Olsen discusses his book "Functional Thinking" and its aim to help readers understand functional programming concepts without diving into specific syntax or languages.
2. Functional thinking emphasizes breaking down a problem into smaller parts, focusing on data rather than side effects.
3. Key concepts include immutability, referential transparency, lazy evaluation, higher-order functions, and recursion.
4. Russ shares the idea of "functional first," trying to approach problems using functional techniques before reaching for imperative or object-oriented approaches.
5. He advises readers interested in learning functional programming languages like Haskell or Clojure, while considering a language they are already familiar with.
6. To better grasp functional concepts, Russ suggests writing code by hand to visualize data flow.
7. As an exercise for viewers, Russ proposes solving the Tower of Hanoi puzzle using functional techniques without looking up any solutions.
8. Russ recommends picking up a functional programming language and reading his book "Functional Thinking."


## Live-Coding a Dashboard with KSQL, Python & JavaScript • Kris Jenkins • GOTO 2021

URL: [https://www.youtube.com/watch?v=8bPDiuJGGh0](https://www.youtube.com/watch?v=8bPDiuJGGh0)

1. Discussion on real-time data streaming and its growing significance in the technology world.
2. Kafka as a powerful tool for streaming live data.
3. Demonstration of building a simple real-time dashboard using Kafka, Confluent, Node.js, and React.
4. Code examples for live streaming data.
5. Encourages developers to understand and use Kafka in their systems for handling live real-time data in motion.
6. Highlights the importance of events happening right now due to their current nature.
7. Q&A session follows the presentation.


## Expert Talk: Web Development & Its Failures • Kevlin Henney & Stefan Judis • GOTO 2021

URL: [https://www.youtube.com/watch?v=jQ0_bIVhkLk](https://www.youtube.com/watch?v=jQ0_bIVhkLk)

1. The transcript is a discussion among software developers about naming issues context: none (indicates no specific context provided).
2. They mention encountering Kevlin Henny, likely an inside joke or recurring occurrences in their daily lives.
3. Topics include fixing broken screens, navigating through construction areas using GPS, and dealing with real-world issues.
4. The developers share their experiences on the way to a conference.
5. They express enjoyment from participating in this conversation while emphasizing the importance of communicating and learning from each other's expertise.


## The Ideal Programming Language • Richard Feldman & Erik Doernenburg • GOTO 2021

URL: [https://www.youtube.com/watch?v=MPyUvtPFDSg](https://www.youtube.com/watch?v=MPyUvtPFDSg)

1. Discussion on the usage and perception of Elm in the programming community, compared to JavaScript, TypeScript, React, and WebAssembly.
2. Evan Czaplicki's background as a co-founder of Prezi and how it led him to create Elm.
3. Elm's focus on simplicity, safety, and productivity, with no runtime errors and automatic type inference.
4. The challenge of introducing new developers to functional programming concepts and how Elm eases the learning curve.
5. Elm's popularity compared to TypeScript in terms of usage and GitHub stars, and its positioning between pure FP languages like Haskell and imperative languages like JavaScript or C.
6. The use of Elm in large-scale production projects such as Basecamp 3 and the BBC newsletter.
7. Elm's growing community, active maintainers, and consistent releases every two years.
8. Elm's approach to web development with a focus on HTML, CSS, and JavaScript interoperability through porting techniques.
9. The lack of a large ecosystem for Elm compared to TypeScript or JavaScript, but its strength in core libraries and the community-driven package manager.
10. Evan's belief that Elm can gain more adoption by embracing WebAssembly and improving mobile app development capabilities through native compilation.


## Programming: Now & Then • Eamonn Boyle & Garth Gilmour • GOTO 2021

URL: [https://www.youtube.com/watch?v=52jnUWrO9i8](https://www.youtube.com/watch?v=52jnUWrO9i8)

1. Discussion between a host and Stephen Wolfram, founder of Wolfram Research and creator of the Mathematica software.
2. Wolfram shares his early interest in computers and programming at age 10.
3. He developed an interest in fundamental theories from a young age while studying physics, mathematics, biology, etc.
4. Wolfram developed Mathematica with the aim to solve problems across various disciplines using computational thinking.
5. The program evolved through iterations and has applications in fields like quantum mechanics, cryptography, AI, etc.
6. Wolfram describes his work as a "philosophical quest" to understand the universe at its most basic level. 
7. Both parties discuss their shared perspective of approaching problems from fundamental principles.
8. Host expresses interest in learning coding and Wolfram encourages finding a good teacher for that purpose.


## Erlang, the Hidden Gem: Solving Problems at Scale for 30+ Years • Francesco Cesarini • GOTO 2021

URL: [https://www.youtube.com/watch?v=-m31ag9z4VY](https://www.youtube.com/watch?v=-m31ag9z4VY)

1. The talk discusses Erlang and its BEAM (Binary Efficient Architecture-Machined Code) virtual machine.
2. BEAM was designed with fault tolerance in mind, allowing it to handle crashes without halting the entire system.
3. Erlang code is compiled into bytecode and interpreted by BEAM, ensuring portability across various platforms.
4. The BEAM team focuses on making the virtual machine scalable for multiple architectures while maintaining speed and lock-free operations.
5. New versions of BEAM can significantly improve program performance without needing to change Erlang code or upgrade hardware.


## Functional Programming for Pragmatists • Richard Feldman • GOTO 2021

URL: [https://www.youtube.com/watch?v=3n17wHe5wEw](https://www.youtube.com/watch?v=3n17wHe5wEw)

1. Presentation discussing functional programming (FP) and its benefits compared to imperative programming.
2. FP's focus on side-effect free functions, immutability, composition, and referential transparency.
3. Benefits include easier reasoning about programs, simpler testing, increased concurrency support, and reduced memory usage.
4. Drawbacks include learning curve, potential confusion with asynchronous behavior, and ecosystem challenges.
5. Advocates for choosing functional programming as a pragmatic choice in most professional scenarios due to its advantages.


## Modernizing Enterprise Java • Markus Eisele, Natale Vinto & Ana-Maria Mihalceanu • GOTO 2021

URL: [https://www.youtube.com/watch?v=tSjCFMSp9oY](https://www.youtube.com/watch?v=tSjCFMSp9oY)

1. Markus and Natale, authors of "Reactive Systems with the Actor Model," join the GOTO Book Club session.
2. The book teaches developers how to design reactive systems using the actor model.
3. Topics covered include concurrency, scalability, resilience, and non-blocking I/O.
4. The actors model is an essential part of a reactive system.
5. The book focuses on Java for readability and familiarity to developers.
6. It's suggested as required reading for university students.
7. The authors are praised for creating an excellent resource for the modern world, particularly for Java developers in enterprise apps sectors.
8. Markus and Natale thank the GOTO Book Club for hosting them and bid farewell to the participants.


## A TypeScript Fan's KotlinJS Adventures • Eamonn Boyle & Garth Gilmour • GOTO 2021

URL: [https://www.youtube.com/watch?v=9p60bBBpG6A](https://www.youtube.com/watch?v=9p60bBBpG6A)

- Topic: Comparing JavaScript and Kotlin for frontend web development
- JSX simplifies writing JavaScript for UI
- Kotlin Multiplatform Mobile brings in more Java developers to the Kotlin ecosystem
- Kotlin's null safety feature is a significant improvement over JavaScript
- Improvements like better tooling, web bindings, and JSX implementation could make Kotlin even more appealing
- Jetpack Compose can unify UI layout for Android, desktop, and web with one DSL language
- The availability of Jetpack Compose for various platforms could be a game changer for frontend developers using both languages.


## How to Read Complex Code? • Felienne Hermans • GOTO 2021

URL: [https://www.youtube.com/watch?v=az-MX_M11lg](https://www.youtube.com/watch?v=az-MX_M11lg)

1. Presentation on "Reading and Understanding Code: Techniques and Tools" by Sandi Metz.
2. The brain processes code in a non-linear manner, unlike natural language.
3. Techniques to improve code comprehension include: 
    a. Reading aloud to engage multiple cognitive systems.
    b. Summarizing the code to internalize its meaning.
    c. Refactoring to simplify and clarify logic.
4. The Memory Model concept can help self-diagnose understanding issues in code.
5. Resources for learning more: Twitter (@sandimetz), website (felina.com), SE Radio podcast, book "Practical Object-Oriented Design in Ruby", and Felina's site for reading club resources.


## Java Security & the Java Ecosystem • Nicolas Frankel • GOTO 2021

URL: [https://www.youtube.com/watch?v=uVob-4aXbxY](https://www.youtube.com/watch?v=uVob-4aXbxY)

1. Discussion on the history of Java versions and release cadence, focusing on the impact of Sun Microsystems acquisition by Oracle in 2010.
2. Concerns regarding the rapid pace of releases since Java 9, leading to potential fragmentation among developers and installations.
3. Shift from biannual updates to yearly updates with LTS support since Java 8 update 201 (Java SE 8).
4. Critique on Oracle's management of the Java Development Kit (JDK), leading to pessimism in the future of Java.
5. Call for checking out a talk addressing these concerns, despite being slightly outdated at the time of conversation.


## AccessibleJS • Jemima Abu • GOTO 2021

URL: [https://www.youtube.com/watch?v=9SFSJDIg4KE](https://www.youtube.com/watch?v=9SFSJDIg4KE)

1. Talk highlights the importance of accessibility in web development with JavaScript.
2. Key points include using semantic HTML, aria attributes and focus management.
3. Semantic HTML provides meaning to elements, improving screen reader experiences.
4. ARIA (Accessible Rich Internet Applications) allows defining roles for custom components.
5. Tabbable elements should have a clear tab order.
6. Focus styles can help users navigate pages easily.
7. Utilize event delegation and document fragments to avoid memory performance optimization techniques.
8. Talk concludes with relevant resources, and invites questions or connections via the presenter's website, LinkedIn, or Twitter.


## Object Oriented Programming vs Functional Programming • Dave Farley • GOTO 2021

URL: [https://www.youtube.com/watch?v=-VADIcicpcg](https://www.youtube.com/watch?v=-VADIcicpcg)

1. The video discusses software development and its history, including the rise of object-oriented (OO) design in the 90s.
2. Function, a Steve Allen K context is absent, implying 'no context' for summarization.
3. Critiques of current OO practices are presented.
4. Suggestions to improve software development include:
    a. Limiting synchronicity through better abstractions and protocols.
    b. Favoring more loosely-coupled systems.
    c. Adopting ideas closer to Allen Kay's 60's vision (reactive manifesto).
    d. Exploring hybrid designs combining functional and OO approaches.
    e. Discarding overuse of inheritance and polymorphism in favor of composition.
    f. Emphasizing simplicity and clarity by reducing the number of abstractions.
    g. Encouraging viewer feedback for exploring these ideas further in future videos.


## Explosive Velocity with a Modern Stack • Tejas Kumar • GOTO 2021

URL: [https://www.youtube.com/watch?v=KTkyQ3z7M8w](https://www.youtube.com/watch?v=KTkyQ3z7M8w)

1. Building a real-time data-driven website with Next.js and Hasura
2. Separating concerns for frontend, backend, and database
3. Using Prisma to define schema and create auto-generated types
4. Setting up Next.js with Hasura for real-time updates
5. Utilizing strongly-typed tools like VS Code and TypeScript for predictability and velocity
6. Prioritizing user experience through auto completion suggestions from editors
7. Outsourcing concerns to Heroku (for database) and Hasura (as a GraphQL engine) 
   
(no context provided directly in input))


## Functional Programming Through the Lens of a Philosopher & Linguist • Anjana Vakil • GOTO 2021

URL: [https://www.youtube.com/watch?v=0kI-as3K4Zo](https://www.youtube.com/watch?v=0kI-as3K4Zo)

1. Discussion on functional programming and its evolution in the last decade.
2. Advancements in tooling and type systems enabling more approachable functional programming.
3. The role of immutability, referential transparency, and higher-order functions in functional programming.
4. Emphasis on the conceptual benefits and mental models instead of focusing solely on syntax.
5. Importance of understanding mathematical concepts to better comprehend functional programming principles.
6. Comparisons between imperative and declarative paradigms.
7. The impact of curation on educational materials and resources for learning functional programming.
8. Hope for in-person conferences to facilitate philosophical discussions about programming and its teachings.


## The Power & Performance of Phoenix LiveView • Geoffrey Lessel • GOTO 2021

URL: [https://www.youtube.com/watch?v=-Rl-26JJ6js](https://www.youtube.com/watch?v=-Rl-26JJ6js)

1. Presentation summary: Demonstrated how to set up real-time updates in Phoenix LiveView using a simple counter application.
2. Steps included creating a basic Phoenix application, adding LiveView, defining live views, and implementing the view with some JavaScript.
3. The project can be found on GitHub under 'jeffgeerling/phoenix_liveview_counter' and its code is organized into distinct steps for easy understanding.
4. The speaker shared social media handles: Twitter, blog (jeffreylessol.com), and YouTube channel where they cover Elixir topics, including LiveView.


## Svelte - Web App Development Reimagined • Mark Volkmann • GOTO 2021

URL: [https://www.youtube.com/watch?v=4CGzFwHoD0A](https://www.youtube.com/watch?v=4CGzFwHoD0A)

1. Presentation covers a comparison between popular JavaScript frameworks: Angular, React, Vue, and Svelte.
2. Angular is a full-stack framework with TypeScript support for strong type checking and an opinionated approach to application structure.
3. React focuses on declarative rendering, virtual DOM for optimization, and a large ecosystem of libraries and plugins.
4. Vue combines the best features from Angular and React, providing flexibility, simplicity, and scalability.
5. Svelte is a relatively new framework that emphasizes code readability, smaller bundles, and improved developer experience through reactive programming.
6. The speaker suggests checking out resources on each framework and their books "Svelte in Action" and "Sapper in Action."


## Command-line, The Underestimated Tool • Bert Jan Schrijver • GOTO 2021

URL: [https://www.youtube.com/watch?v=bWDuXAQJX8Y](https://www.youtube.com/watch?v=bWDuXAQJX8Y)

1. Importance of learning and practicing Unix commands for software development, system administration, and DevOps roles.
2. Familiarity with basic commands like cd (change directory), ls (list files/directories), pwd (print working directory), man (manual pages), and grep (search for a pattern).
3. Utilization of Unix tools such as sed, awk, and tr for data transformation and manipulation.
4. Use of pipelines to combine multiple commands for enhanced functionality.
5. Benefits from automating tasks with scripts written in bash or python.
6. Tracing problems in remote environments by visibly observing tests run in containers on cloud environments using tools like tmux, screen, and ssh.
7. Encouragement to practice Unix commands regularly for improvement and retention of knowledge.
(no context provided beyond the transcript).


## A Beginner's Guide to eBPF Programming with Go • Liz Rice • GOTO 2021

URL: [https://www.youtube.com/watch?v=uBqRv8bDroc](https://www.youtube.com/watch?v=uBqRv8bDroc)

1. Demonstration of creating a BPF program to track system calls using Golang and C.
2. Modification of sysenter tracepoint from "printk" to "raw_tracepoint".
3. Goal to replicate the 'vps' script functionality in user space without BCC or eBPF tools.
4. Attachment of raw tracepoints for specific system calls, such as read and write.
5. Observation of recreated system call counters after executing the modified code.
6. Potential to attach to various trace points and utilize BPF helper functions for more complex analysis.
7. Full code available on GitHub with hope for audience questions or engagement.


## From Objective-C to Swift and the Latest Innovations at Apple • Daniel H Steinberg • GOTO 2019

URL: [https://www.youtube.com/watch?v=qynCRtJlV8I](https://www.youtube.com/watch?v=qynCRtJlV8I)

1. Discussion on Apple's Worldwide Developers Conference (WWDC)
2. Introduction of Swift programming language
3. Comparison between Objective-C and Swift
4. Focus on WWDC announcements: Silicon Macs, iOS 15 updates, and macOS Monterey
5. Discussion about Apple's chip development and integration
6. Speculations about future Apple hardware releases
7. Emphasis on Swift package manager enhancements
8. Predictions for third-party tools like Carthage and CocoaPods as first-party application gains functionality
9. Mention of in-person classes taught by the speaker across Europe.


## The Jamstack Book • Brian Rinaldi & Raymond Camden • GOTO 2021

URL: [https://www.youtube.com/watch?v=x0RoXonhldk](https://www.youtube.com/watch?v=x0RoXonhldk)

1. Ray and Chris discuss their book "The Jamstack" and the concept of Jamstack websites.
2. The book covers various case studies, technologies like Gatsby, Eleventy, and Next.js, and CDNs.
3. Jamstack sites are faster, more secure, and cost-effective due to separating data and logic from presentation layers.
4. The authors encourage readers to explore different tools in the booklet.
5. They suggest buying multiple copies of "The Jamstack" for oneself and loved ones.
6. Legos (toys) are expensive.
7. Ray wants more books sold so he can buy more Death Star Lego sets.


## GraphQL Anywhere - Our Journey With GraphQL Mesh & Schema Stitching • Uri Goldshtein • GOTO 2021

URL: [https://www.youtube.com/watch?v=2vwlkJnaV0Y](https://www.youtube.com/watch?v=2vwlkJnaV0Y)

1. Presentation focuses on GraphQL's potential beyond frontend development.
2. GraphQL can be used for backends, APIs, and data infrastructure.
3. GraphQL enables building flexible and resilient systems with less code.
4. The talk covers various use cases of GraphQL in different scenarios: backend APIs, serverless functions, and data discovery.
5. GraphQL's flexibility allows for easy integration with existing systems without breaking changes.
6. A case study demonstrates how a company switched from REST to GraphQL while maintaining the same URL structure.
7. The introduction of GraphQL Hive enabled unified data view across different services, even when not using GraphQL at runtime.


## Should Kotlin Be Your Go-To Language? • Garth Gilmour & Eamonn Boyle • GOTO 2019

URL: [https://www.youtube.com/watch?v=FcrkrsxYigM](https://www.youtube.com/watch?v=FcrkrsxYigM)

1. The conversation focuses on understanding the role of performance in software development, particularly for junior developers.
2. The panelists discuss that performance is critical but often underestimated by developers, leading to poor user experiences and increased costs.
3. They emphasize that although modern technology provides optimizations, it's important for developers not to ignore performance issues entirely.
4. The sweet spot between neglecting and overly focusing on performance must be found for most developers working on typical projects.
5. Discussions around performance include topics like garbage collection strategies in various programming languages and complex optimization layers within the JVM.


## Erlang, Elixir, Blockchain & Serverless… What?! • Ulf Wiger, Sasa Juric & Eric Johnson • GOTO 2019

URL: [https://www.youtube.com/watch?v=2QNA6uaBHY4](https://www.youtube.com/watch?v=2QNA6uaBHY4)

1. Discussion on Erlang and Elixir programming languages.
2. Erlang developed at Ericsson for telecommunications systems in 1986.
3. Erlang's main feature - concurrent processes with built-in fault tolerance.
4. Elixir based on Erlang with modern language features like macros, patterns, and better syntax.
5. Both languages used for building scalable real-time distributed systems.
6. Comparison between Erlang and Elixir: 
    - Syntax: Elixir more readable and approachable to newer developers.
    - Functional programming principles shared by both languages.
    - Support for parallelism and concurrency.
    - No context provided for summarizing unrelated content.


## Did We(b Development) Lose the Right Direction? • Stefan Judis • GOTO 2020

URL: [https://www.youtube.com/watch?v=0Vtoblyq8fE](https://www.youtube.com/watch?v=0Vtoblyq8fE)

1. Stefan judged web projects in a front-end contest and faced issues with large JS frameworks leading to slow performance.
2. He switched from React to Vue due to smaller bundle size but still struggled with performance.
3. Stefan moved to static site generators, specifically Gatsby, which improved page speed significantly.
4. He built his personal website using Gatsby and achieved a perfect green lighthouse score and better user experience.
5. Stefan believes front-end developers should focus on building sites that just work without overemphasizing the technology used.


## Life After Business Objects - Confessions of an OOP Veteran • Vagif Abilov • GOTO 2020

URL: [https://www.youtube.com/watch?v=UBUYwpDl3-g](https://www.youtube.com/watch?v=UBUYwpDl3-g)

1. Presentation about a banking project using F# functional programming language for back-end services.
2. Switch from C# to F# due to its excellent support for domain modeling and declarative coding style.
3. F#'s algebraic data type facilitates clear and precise modeling.
4. Simplified code with fewer bugs, faster deployment of features.
5. Compact F# code typically works after compilation.
6. Significant reduction in the number of failing unit tests after switching to functional programming.


## Upgrade Time: Choose Java 11+ or the “Other” One…Kotlin • Paulien van Alst • GOTO 2020

URL: [https://www.youtube.com/watch?v=BcVOvdrFaPY](https://www.youtube.com/watch?v=BcVOvdrFaPY)

1. Setup Gradle and Kotlin plugin for the application
2. Migrate Java classes to Kotlin using the JetBrains migration assistant 
3. Review and fix any potential issues from the migration
4. Write unit tests using JUnit5, Mockito, and Kotlin Test extensions
5. Replace Java-specific imports with Kotlin ones (e.g., import org.junit.Test to import kotlinx.serialization.Serializable)
6. Rewrite configuration classes (e.g., replace @Configuration with @SpringBootApplication annotation)
7. Convert data objects from Java Beans to data classes in Kotlin
8. Migrate integration tests using Kotlin's Spock framework and Mockito
9. Run the application, ensuring it starts properly after all changes 
10. Successfully completed the migration from Java to Kotlin


## The Future of Java: Will You Have to Pay For It? • Trisha Gee & Daniel Bryant • GOTO 2019

URL: [https://www.youtube.com/watch?v=W-_5AV2qZXs](https://www.youtube.com/watch?v=W-_5AV2qZXs)

1. Discussion on the term "developer skills" and its shift to emphasize a broader skillset beyond technical abilities.
2. Importance of communication, empathy, collaboration, and business understanding for developers.
3. Senior developers often possess better problem-solving and questioning abilities compared to juniors.
4. The need for developers to develop a range of skills including technical, communication, and business acumen to succeed in the industry.
5. Different companies have different requirements for developers and value unique skill sets and personalities. 
(no context provided)


## Programming Kotlin: Why, How & Its Future • Venkat Subramaniam & Hadi Hariri • GOTO 2021

URL: [https://www.youtube.com/watch?v=7J2ATE4NGZ8](https://www.youtube.com/watch?v=7J2ATE4NGZ8)

1. Discussion about Venkat Subramaniam's new book "Graduating from GoTo: The Roadmap for Senior Developers"
2. Transitioning from junior to senior developer role
3. Emphasis on communication, leadership, and coaching skills for senior developers
4. Venkat's motivation to write the book based on his experiences and observation of industry trends
5. Graduating from GoTo concept refers to moving from a single technology or team specialization to broader expertise
6. Importance of soft skills like empathy and emotional intelligence in the development field
7. The book offers practical advice, real-life examples, and exercises for senior developers
8. Discussion on Groovy and the Go programming language
9. Venkat's involvement with the GoTo team at GoToConference
10. GoToConference focuses on bringing together experts in software development
11. Upcoming edition of "Graduating from GoTo" to include more examples and exercises.
12. Book Club promotion code 'book club'.
13. Venkat Subramaniam is a prominent figure in the programming community.
14. The Groovy language has evolved into the GraalVM platform.
15. Discussion on GoTo team's work on the Go programming language.


## A TypeScript Fan's KotlinJS Adventures • Eamonn Boyle & Garth Gilmour • GOTO 2020

URL: [https://www.youtube.com/watch?v=Si3z82PEB5o](https://www.youtube.com/watch?v=Si3z82PEB5o)

- Kotlin JS is a JavaScript interoperable module
- It allows developers to write frontend code using Kotlin
- Mixing with JavaScript possible, but not always recommended for large projects due to type checking and other benefits of Kotlin
- Type inference makes it more readable than TypeScript
- Gradle support ensures similarities between backend and frontend build processes
- Type erasure can cause issues, requiring explicit type annotations for nullability
- Future improvements include better code emitting, bundle size optimization, automatic generation of TypeScript definition files, and WebAssembly targeting.


## Memory Efficient Java • Kirk Pepperdine • GOTO 2020

URL: [https://www.youtube.com/watch?v=kQEu1VsrG44](https://www.youtube.com/watch?v=kQEu1VsrG44)

1. To optimize code performance, use the CPU profiler to analyze time-consuming methods.
2. Start with the slowest method and understand its functionality.
3. Identify potential issues causing inefficiencies in code by reviewing algorithms and data structures.
4. Make necessary changes to improve the algorithm or data structure for better performance.
5. In this specific example, removing unnecessary array creation resulted in a 2x improvement in performance.
6. The compiler can't optimize certain aspects, so human intervention is crucial for optimal performance tuning.
7. Constantly review and update code to ensure it remains efficient with changing requirements or environment changes.
8. Understand the trade-off between simplicity and efficiency in choosing data structures and algorithms.
9. Always use the CPU profiler when faced with slow code, even if you suspect a specific issue. 
10. The JIT compiler might not be able to optimize all cases automatically.


## 97 Things Every [Java] Programmer Should Know • Trisha Gee & Kevlin Henney • GOTO 2020

URL: [https://www.youtube.com/watch?v=T47k2tHXmOA](https://www.youtube.com/watch?v=T47k2tHXmOA)

1. The discussion revolves around Go To's latest book, "The Book of Troubleshooting", and its format containing small chunks of knowledge.
2. It aims to challenge readers' perspectives by presenting various views on issues without providing definitive answers.
3. The co-authors aimed for balance in the book regarding different opinions on topics like remote work.
4. To get the most out of the book, readers should explore it fully without expecting clear resolutions. They can subscribe to Go To's YouTube channel and attend conferences using the promo code from the book club on gotopia.tech.


## Secrets of the Shenandoah Garbage Collector • Stephanie Crater • GOTO 2020

URL: [https://www.youtube.com/watch?v=WcSqLvxwzbA](https://www.youtube.com/watch?v=WcSqLvxwzbA)

- Discussion on the Netflix Tech Blog post about their microservice architecture evolution
- Moving from monolithic to service-based approach, addressing concerns such as scalability and resilience
- Concept of a "stout" stack, where services have broad responsibilities and can communicate with multiple data stores
- Importance of choosing the right level of encapsulation for microservices based on context and optimization goals
- Example of shelves not needing to know why they aren't holding things or if they are favored, as long as they perform their primary function effectively.
- Key metrics like pause time, throughput, latency, and overall Shenandoah optimization should guide decisions in microservice design rather than simply improving visual dashboards or graphs.


## Gradually Adopt GraphQL Without Writing any Backend Code • Uri Goldshtein • GOTO 2020

URL: [https://www.youtube.com/watch?v=DWBL7GLMVsY](https://www.youtube.com/watch?v=DWBL7GLMVsY)

- GraphQL is a query language for APIs that provides better (humor)
- Introducing GraphQL on the front-end is easier and encourages solving common issues
- Benefits include simpler code, improved developer experience, and enhanced customization of responses
- Execution can be moved to other services like service-to-service communication
- Tool like GraphQL Mesh allows starting execution on front-end products, optimizations, and moving it to other services later.
(no context provided directly in the transcript.)


## Facts You May Not Know About Kotlin • Eugene Petrenko • GOTO 2020

URL: [https://www.youtube.com/watch?v=XwzStZaDpH0](https://www.youtube.com/watch?v=XwzStZaDpH0)

1. Presentation highlights Kotlin, a JVM language with type inference and smart casts for efficient coding.
2. Kotlin supports functional programming concepts such as higher-order functions, lambda expressions, and extension functions.
3. The null safety feature in Kotlin reduces common mistakes related to NullPointerExceptions.
4. The reified generic feature allows working with type parameters at runtime.
5. Smart constructors allow easy object creation without boilerplate code.
6. Kotlin Multiplatform Mobile (KMM) enables developers to share code across platforms like Android and iOS.
7. Kotlin can enhance the coding experience by using fun keywords in multi-platform programming.
8. The speaker encourages questions at the end of the presentation.
(no context provided directly in the transcript.)


## Memory Efficient Java • Kirk Pepperdine • GOTO 2020

URL: [https://www.youtube.com/watch?v=sE_dv7piOZg](https://www.youtube.com/watch?v=sE_dv7piOZg)

1. Demonstration of the class index feature using a JMH benchmark to profile memory usage
2. Two objects involved: Benchmark and BenchmarkInner
3. BenchmarkInner object has a reference to a Benchmark outer class object
4. Testing three scenarios: no inner class, default access modifier, and package-private access modifier for the inner class
5. JDK 14 shows that Score also appears in the profile, which was unexpected and might be a regression
6. The application runtime drops to approximately 12 seconds after optimizations are made.


## Elixir in Action • Sasa Juric & Erik Schoen • GOTO 2020

URL: [https://www.youtube.com/watch?v=-bCkha6U70o](https://www.youtube.com/watch?v=-bCkha6U70o)

1. Go To's "A practical guide to cloud native development" book release and reception
2. The book discusses principles of cloud native technologies without getting too technical or focusing on specific products
3. It covers concepts, tools, and practices to develop cloud-native applications in various stacks and environments
4. The author wanted it to be accessible for readers with different backgrounds and skills
5. The book has received positive feedback from readers and grew organically through recommendations
6. Feedback from unsolicited sources is the most rewarding experience for the author. 
7. Link provided to subscribe to Go To's YouTube channel, attend upcoming conferences with a promo code, and learn more at gotopia.tech.


## Next-Generation Programming: Rust & Elm • Richard Feldman • GOTO 2020

URL: [https://www.youtube.com/watch?v=ukVqQGbxM9A](https://www.youtube.com/watch?v=ukVqQGbxM9A)

1. Comparison of Elm and Rust programming languages.
2. Elm is a functional language for building front-end applications with static typing and strong type system.
3. Rust is a systems language designed for safety, speed, and concurrency.
4. Elm has better tooling for web development compared to TypeScript.
5. Rust excels in the back-end space due to its flexibility, and safety guarantees.
6. Both languages have excellent community support with learning resources available.
7. Elm's type system results in less code, while Rust might require more boilerplate code.
8. Elm has a smaller standard library, while Rust offers broader capabilities.
9. Elm prioritizes simplicity and ease-of-use for beginners, while Rust aims at safety and control.
10. Both languages feature type systems with strong guarantees, reducing common bugs in software development.


## Maximizing Java Application Performance with GraalVM • Oleg Šelajev • GOTO 2020

URL: [https://www.youtube.com/watch?v=PeMvksAZbdw](https://www.youtube.com/watch?v=PeMvksAZbdw)

1. GraalVM is a high performance, polyglot VM developed at Oracle Labs.
2. It targets faster execution and smaller memory footprints compared to JDK.
3. GraalVM can run languages like Python, Ruby, JavaScript, C/C++, R, and more.
4. It's used by large companies such as Twitter, Netflix, Uber, and Capital One for various purposes.
5. Oracle has an enterprise edition called Oracle Runway based on GraalVM.
6. The project is open-source and encourages participation in its ecosystem.


## Bootiful GraphQL with Kotlin • Dariusz Kuc • GOTO 2020

URL: [https://www.youtube.com/watch?v=1siPT1pTXFU](https://www.youtube.com/watch?v=1siPT1pTXFU)

1. Introduction to GraphQL Resolvers and asynchronous handling in JavaScript.
2. Traditional resolver blocks the thread while fetching data, leading to slower execution.
3. Using functions instead of properties in resolvers improves performance.
4. Library requires minimal setup with single dependency.
5. Library generates schema from source code.
6. Annotations provide documentation and directives.
7. Native support for Promises allows writing fully asynchronous code.
8. Comprehensive examples and documentation available on GitHub pages.


## HTML: How to Make Loveliness • Bruce Lawson • GOTO 2020

URL: [https://www.youtube.com/watch?v=L83LVfhTbzg](https://www.youtube.com/watch?v=L83LVfhTbzg)

1. Tim Berners-Lee highlights the web's impact on people worldwide, not just computers or technology.
2. The web has empowered individuals in areas such as education, healthcare, and political freedom.
3. Examples include African women, a blind man in Toronto, Bangladeshi bus passengers, a Taiwanese lady in a wheelchair, Cambodian farmer and granddaughter, and a New York Metro passenger.
4. The industrial revolution took 50 years to have the same impact as today's web in terms of progress for all people.
5. Web users should pay forward its benefits, acknowledging it is about humanity and not just technology.


## Kotlin Flows and Channels for Android • Ryan Pierce • GOTO 2020

URL: [https://www.youtube.com/watch?v=xch4aw7hNcY](https://www.youtube.com/watch?v=xch4aw7hNcY)

1. Three ways to implement a user list application using LiveData and Coroutines with Flow.
2. First method involves LiveData, data binding adapter, and view model to create a ListView.
3. Observe users from the UserLiveData stream and add each user to the List Adapter.
4. Second method uses Flow and lifecycle scope with custom coroutine builder "launchWhenCreated".
5. As users are collected by the collect operator, they're added to the adapter.
6. Flow is reactive, suspending when there are no values and resuming with new values.
7. A cleaner version of the second method uses the launchIn lifecycle scope and adds the user through an onEach statement.
   
Note: Transcript provided, summarized accordingly. Context provided.


## Ray: A System for Distributed Applications • Dean Wampler • GOTO 2020

URL: [https://www.youtube.com/watch?v=uPeCk7Wx8HU](https://www.youtube.com/watch?v=uPeCk7Wx8HU)

1. Ray Talk overview: scalable programming for data-intensive workloads, with a unified framework for parallelism and concurrency.
2. Ray integrates well with Python ecosystem tools such as Dask, XGBoost, and Scikit-learn.
3. Ray provides transparent resource management to help maintain consistent performance during heavy loads.
4. Ray's Actors enable concurrent execution without the need for explicit threading or process management.
5. Ray's Task Schedulers handle resource allocation and scheduling for parallel execution, eliminating the need for complex task queues.
6. Ray provides built-in resilience through task checkpointing and automatic restart functionality.
7. Migration to Ray involves using drop-in replacements for multi-threading libraries with a new import statement that allows scaling across clusters.


## Adopt GraphQL without Writing any Backend Code • Uri Goldshtein • GOTO 2020

URL: [https://www.youtube.com/watch?v=1bJ_M_v-tso](https://www.youtube.com/watch?v=1bJ_M_v-tso)

1. Three approaches to GraphQL implementation:
   a. Backend-only integration (server and SDKs)
   b. Frontend-only integration (Apollo Client with queries and mutations)
   c. Combined frontend and backend usage (GraphQL-CodeGen for auto-generated SDKs)

2. Benefits of GraphQL include flexibility, better UX, better cache management, easier scaling, and reduced API calls.

3. Frontend-centric approach using GraphQL allows quick adoption with existing sources, customizations, and gradual migration deeper into the stack.

4. The speaker recommends starting with frontend usage of GraphQL to see its benefits in action and gradually remove manual code by using markdown style for output.


## The Magic of Music Matching • Roy van Rijn • GOTO 2020

URL: [https://www.youtube.com/watch?v=8Dj0rekeM7g](https://www.youtube.com/watch?v=8Dj0rekeM7g)

1. Exploration of music recognition technology using Python and NumPy libraries.
2. Calculation of Dynamic Time Warping (DTW) distances between audio fingerprints from two songs.
3. Shazam and SoundHound use DTW to match audio signatures with their database.
4. Development of a simple, working music matcher in Python.
5. Fingerprinting can be used for copyright infringement detection but not directly applicable to speech recognition.
6. Room for improvement in the algorithm as library size grows larger.


## Making Mutants Work for You • Henry Coles • GOTO 2019

URL: [https://www.youtube.com/watch?v=LoFJajoJQ2g](https://www.youtube.com/watch?v=LoFJajoJQ2g)

1. The speaker discusses mutation testing, a form of fault-based testing.
2. Mutation testing involves modifying code to intentionally introduce defects and assessing if the test suite catches these new errors.
3. It can be used for unit tests, acceptance tests, and integration tests.
4. The speaker mentions various languages and frameworks that support mutation testing.
5. Mutation testing supports approximately 20 different languages and frameworks like Python, C++, Ruby, Java, .NET, and JVM.
6. The speaker highlights some limitations of mutation testing like poor support for multi-threaded code and non-deterministic behavior.
7. They encourage the audience to follow sister, a related resource.
8. Mutation coverage is used as a metric to measure how much of the system is covered by the test suite.
9. The speaker briefly lists supported languages during lunchtime without vouching for their efficacy (Go, Scala, Clojure, Typescript, Rust, Swift).
10. Lastly, they encourage following them on Twitter.

no context (the provided text is a transcript of a conference presentation)


## An Introduction to JVM Performance • Rafael Winterhalter • GOTO 2020

URL: [https://www.youtube.com/watch?v=wgJWs14YcEs](https://www.youtube.com/watch?v=wgJWs14YcEs)

1. The speaker begins by apologizing for technical issues and background noise.
2. They introduce themselves as Ruthie Guo, a security researcher and community builder.
3. They thank the event organizer for the invitation to speak about their journey in open source and infosec.
4. Ruthie talks about how they got involved with infosec due to curiosity and a desire to protect others online.
5. They mention their experience at Defcon, BSides, HackerOne, and Google Summer of Code.
6. The speaker shares their passion for open source projects, particularly Bite Buddy, which they collaborate on with a Russian coach.
7. Ruthie finishes by encouraging listeners to connect with them through Twitter (@rufflecoats) and their website. They also thank the audience for attending virtually amidst pandemic concerns.


## Kotlin 4 vs. Scala 3 • Garth Gilmour & Eamonn Boyle • GOTO 2020

URL: [https://www.youtube.com/watch?v=sIL4mduqHe0](https://www.youtube.com/watch?v=sIL4mduqHe0)

1. The video discusses a comparison between Scala and Kotlin programming languages.
2. Scala is statically-typed, general-purpose, object-oriented, and functional language developed in 2003 by Martin Odersky.
3. Kotlin originates from JetBrains as an interoperable language for the Android platform.
4. Both languages share syntax similarities with Java, but have different approaches to type systems.
5. Scala is more complex and difficult to learn for beginners due to its polymorphism, implicits, higher-order functions, and operator overloading features.
6. Kotlin aims at making programming easier through features like coroutines and null safety.
7. Both languages have their pros and cons depending on the project scale or mentoring junior developers.
8. Personal preference, environment (Kickstarter vs enterprise), and collaboration with friends play a role in choosing between Scala and Kotlin.


## You Really Don't Need All that JavaScript, I Promise • Stuart Langridge • GOTO 2019

URL: [https://www.youtube.com/watch?v=rxlJRydqmk8](https://www.youtube.com/watch?v=rxlJRydqmk8)

1. The web is an open standard, allowing for creativity and innovation.
2. Web standards are a living document, constantly evolving to adapt to new technologies.
3. Browsers must follow the specification to provide a level playing field for developers.
4. Polyfills can help bring emerging features to users before full standardization.
5. Balance between staying ahead of web standards and ensuring compatibility is essential.
6. The web is a powerful tool for knowledge sharing, connecting people, and building the largest repository of information known.


## Scaling up an iOS Codebase • Tjeerd In't Veen • GOTO 2019

URL: [https://www.youtube.com/watch?v=n09omYo_QPk](https://www.youtube.com/watch?v=n09omYo_QPk)

1. Importance of understanding software dependencies and managing them effectively.
2. Three types of version numbers: major, minor, and patch.
3. Semantic Versioning guidelines for consistent release numbering.
4. Challenges in dependency management and the impact of breaking code or releasing major updates.
5. Package managers such as Cargo, CocoaPods, npm, Maven, Gradle, Bower, NUGet, and SPM discussed and their applicability based on projects' needs.
6. The speaker shares a link to their book published by Manning with a discount offer.


## Battle of the Circuit Breakers: Resilience4J vs Istio • Nicolas Frankel • GOTO 2019

URL: [https://www.youtube.com/watch?v=kR2sm1zelI4](https://www.youtube.com/watch?v=kR2sm1zelI4)

1. Demonstration of a real-world example using Node.js and Circuit Breaker pattern to handle unresponsive microservices.
2. The circuit breaker pattern consists of four states: Open, Closed, Half-Open, and Hybrid state.
3. A real-life service (Shopify) is made unavailable through Fiddler during the demo.
4. Circuit Breaker strategy using the opengyre/circuitbreaker library in Node.js.
5. Exploration of a simple REST API (shopify) and an order service using Shopify's APIs.
6. The circuit breaker pattern ensures that unresponsive microservices do not bring down other services or the entire system bypassing them when unavailable.
7. Circuit Breaker implementation in Node.js involves setting up a shopify API client, an order service, and a broker service.
8. Broker service uses circuit-breaker pattern to call unresponsive order service while still working with responsive shopify service.
9. In practice, developers should play around with the provided source code for better understanding of Circuit Breaker patterns in microservices architecture.


## Building Secure React Applications • Philippe De Ryck • GOTO 2019

URL: [https://www.youtube.com/watch?v=O91hJJ5KMLs](https://www.youtube.com/watch?v=O91hJJ5KMLs)

- Transcription includes a mix of Dutch and English phrases and words.
- Topics discussed include river levels, updating applications, voting booths, Persephone multi dat, Saturnus, Flint roles, Twitter dislikes, securities, and ministry questions.
- Acknowledgments and thank you messages are present at the end.
- Applause is heard at the conclusion.
- No specific context is provided.


## Nullable Reference Types in C# 8 • Jon Skeet • GOTO 2019

URL: [https://www.youtube.com/watch?v=1tpyAQZFlZY](https://www.youtube.com/watch?v=1tpyAQZFlZY)

1. Nullable reference types in C# 8 and above add annotations to variables to indicate whether they can be null or not.
2. The compiler generates warnings for possible null reference issues, prompting developers to fix them.
3. Enabling nullable reference types does not alter the IL (intermediate language) code's behavior; it only highlights potential issues.
4. It is an iterative process to address and eliminate these warnings for cleaner and safer code.
5. This feature enables better communication between developers by indicating expected nullability within code.
6. The speaker emphasizes the need for greater diversity in the tech community.


## How Java & Scala are Imitating Functional Languages • Maurice Naftalin & José Paumard • GOTO 2019

URL: [https://www.youtube.com/watch?v=e6n-Ci8V2CM](https://www.youtube.com/watch?v=e6n-Ci8V2CM)

1. Discussion on programming language features: static typing vs. dynamic typing
2. Typescript's evolution and its adoption by large organizations like Microsoft and Facebook
3. Java being cautious about adding new features due to a large number of users and the difficulty in removing them later
4. Lambdas, an addition to Java that seemed to stand the test of time despite their conservative approach
5. Comparison between TypeScript's rapid evolution and Java's more cautious approach
6. Both approaches have advantages depending on specific circumstances.


## The Future of Machine Learning & JavaScript • Asim Hussain • GOTO 2019

URL: [https://www.youtube.com/watch?v=vfmGII9mGmY](https://www.youtube.com/watch?v=vfmGII9mGmY)

1. Presentation about Generative Adversarial Networks (GANs) and their real-world applications.
2. GANs create new images by learning from existing data and generating - humor.
3. MoJoFire, a fake fire, demonstrating GAN capabilities.
4. Possible real-world uses: anti-aging, face swapping.
5. Example of creating celebrity photos by combining features.
6. Potential risks associated with deepfakes and its ethical implications.
7. Tutorials available for learning about Mojo fire and slack bot creation in Tensfor Js.
8. Upcoming book titled "Touch the Machine Line with Tensfor Js".
9. Attendees encouraged to take a picture of the book title to stay updated on its release.
10. Context provided for learning more about GANs and their implementation step by step. If no context is given, write 'no context'.


## What’s New in Swift • Daniel H Steinberg • GOTO 2019

URL: [https://www.youtube.com/watch?v=6P-nh3uNnsQ](https://www.youtube.com/watch?v=6P-nh3uNnsQ)

1. The video discusses new features in Swift 5.5.
2. Pattern matching for optionals introduces a simpler and safer way to unwrap optional values.
3. Switch case patterns can now match against multiple cases, allowing for more concise code.
4. The `withExpression` property wraps code within a closure while keeping the original scope alive.
5. Associated value default initializers simplify struct and enum creation by providing default values for specific properties.
6. A new decimal type for numbers with decimal points adds convenience methods for common operations.
7. Decimal's `rounded(to:)` method allows users to specify the number of places for rounding.
8. Swift 5.5 includes several features inspired by SwiftUI and combines them for improved functionality.


## Kotlin/Native: The Good, The Bad, and the Ugly • Ellen Shapiro • GOTO 2019

URL: [https://www.youtube.com/watch?v=JHUY1Ckmo64](https://www.youtube.com/watch?v=JHUY1Ckmo64)

Error


## Building a Blockchain in Erlang • Ulf Wiger • GOTO 2019

URL: [https://www.youtube.com/watch?v=QLwFpT_0c4U](https://www.youtube.com/watch?v=QLwFpT_0c4U)

1. Erlang as a programming language for blockchain and decentralized applications.
2. Features of Erlang: concurrency, distribution, fault tolerance, soft real-time properties (PROP) and high availability (HA).
3. PROP and HA enabled by message passing between processes.
4. QuickCheck tool for property-based testing in Erlang.
5. Eternity blockchain project with open-source state channel.
6. Cubic quick check tool not open source, but equivalent tools exist for other languages like proper in Erlang.
7. Whole Eternity blockchain or state channel is open source.
8. Foundation and incubators provide grants to those interested in contributing to the project.


## A Veterans Guide To Transitioning Android Teams Into Kotlin • G. Gilmour & E. Boyle • GOTO 2019

URL: [https://www.youtube.com/watch?v=ocCE3s9j-9A](https://www.youtube.com/watch?v=ocCE3s9j-9A)

1. The video features a discussion with members of the Cortland team and their experiences with the programming language.
2. Cortland is a systems programming language based on C++, designed for safety, portability, and high performance.
3. It emphasizes safety through memory protection, type system, and other mechanisms to catch errors at compile-time.
4. Portability is ensured by supporting multiple platforms (e.g., Linux, Windows, macOS), architectures (x86, ARM), and compilers.
5. Cortland aims for high performance by generating efficient code without sacrificing safety or portability.
6. The team highlights their experience with Cortland's simplicity, ease-of-use, and efficiency compared to C++.
7. They also mention the advantages in agile development, faster sprints, less code review, and version control management.
8. Ultimately, these benefits provide a competitive edge for the company through customer satisfaction and happiness.


## Upgrade Time: Choose Java 11 or the “other” one…Kotlin • Paulien van Alst • GOTO 2019

URL: [https://www.youtube.com/watch?v=VX3UBvwJtyA](https://www.youtube.com/watch?v=VX3UBvwJtyA)

1. Introduction to test pyramid concept and its importance in testing strategies
2. Test pyramid consists of four layers: Unit tests, Integration tests, Service/System tests, and Acceptance tests
3. Unit tests focus on smallest parts of code, ensuring individual functions work correctly
4. Integration tests verify the interaction between components, ensuring they function as expected when connected
5. Service/System tests at service or system level, simulating real-world scenarios
6. Acceptance tests check the functionality of an application from the user's perspective
7. Unit tests should make up around 60% to 90% of total tests
8. Integration tests should be a significant portion of the test pyramid as they uncover interdependent bugs
9. Service/System and Acceptance tests are expensive in terms of time and resources, but necessary for broader system checks
10. Test pyramid aims to strike a balance between coverage and efficiency, avoiding testing blind spots. 
(no context provided in the input transcript)


## Kotlin: Dissecting the stdlib • Huyen Tue Dao • GOTO 2019

URL: [https://www.youtube.com/watch?v=uCMuGVh7W_0](https://www.youtube.com/watch?v=uCMuGVh7W_0)

1. Colin Gillespie discussed the usage of Kotlin for Android development.
2. He mentioned that Kotlin is now used by more than 70% of new and existing projects on Jetpack Compose.
3. Kotlin's null safety features provide a cleaner and safer codebase.
4. Kotlin coroutines simplify concurrency, making the code easier to read and test.
5. The new experimental sealed classes can be used for constructing state machines in Jetpack Compose projects.
6. Colin shared an example of using sealed classes for a countdown clock feature.
7. He advised exploring Kotlin's open-source code and adapting its techniques to improve readability and functionality.


## Life After Java 8 • Trisha Gee • GOTO 2019

URL: [https://www.youtube.com/watch?v=eBuFzQeiGe0](https://www.youtube.com/watch?v=eBuFzQeiGe0)

1. Presentation discusses Java release cadence and its impact on version updates and support.
2. Long Term Support (LTS) versions released every three years, with regular releases every six months.
3. Oracle Java 8 End-of-PublicUpdates (EOPU) in January 2019 and OpenJDK LTS supported until December 2026.
4. Faster release cadence means quicker deprecation and removal of methods, resulting in more pain for developers if they don't keep up.
5. Suggestion to upgrade to at least Java 11 and stay updated through continuous integration or test environments.
6. Resources include slides, videos, reading materials, and articles on migrating to newer versions.


## From Spring Boot Apps to Functional Kotlin • Nicolas Frankel • GOTO 2019

URL: [https://www.youtube.com/watch?v=f6a78mCrSeE](https://www.youtube.com/watch?v=f6a78mCrSeE)

1. Spring Framework 5.3 features: WebFlux, Reactive programming, and better integration with Kotlin.
2. WebClient for making reactive HTTP calls using Flux and Mono types.
3. Reactor WebFilter to intercept requests in a non-blocking manner.
4. A new WebTestClient for testing reactive endpoints.
5. Spring Boot 2.3 supports Kotlin coroutines through the kotlinx-coroutines library, enabling easier migration from blocking calls to non-blocking ones.
6. Two options for removing "magic": remove controllers and migrate routes or use Bean DSL and no longer rely on reactive programming.
7. Spring continues to embrace Kotlin as a preferred language.
8. Recommendation to read the presenter's blog, follow them on Twitter, and play with the provided repository for better understanding.


## It Really is Easier to Ask for Forgiveness (than Permission) • Naomi Ceder • GOTO 2019

URL: [https://www.youtube.com/watch?v=SYrVZR_g718](https://www.youtube.com/watch?v=SYrVZR_g718)

1. Pythonic code prioritizes readability and simplicity over performance.
2. Explicit is better than implicit: clearly define variables, functions, and comments.
3. Flat is better than nested: avoid deeply nested structures for easier comprehension.
4. Sparse is better than dense: use whitespace and newlines to enhance readability.
5. Dict Comprehensions can replace complex loops for efficient data generation.
6. List Comprehensions are preferable over map/filter combinations for list operations.
7. Avoid working to avoid exceptions, as Python interpreter handles them efficiently.
8. While aiming for better readability and simplicity in code, understand that performance may be sacrificed in some cases.


## Rust 2018: Access All Areas • Florian Gilcher • GOTO 2019

URL: [https://www.youtube.com/watch?v=sCSfyQYDImM](https://www.youtube.com/watch?v=sCSfyQYDImM)

1. Rust is a systems language focused on safety, speed, and correctness.
2. It's built to replace C and C++ in many domains due to memory safety (repeated for emphasis).
3. Rust offers guarantees with no runtime semantics except for threads.
4. Simple runtime semantics allow usage across any area of a product.
5. Rust is used for IOT sector, covering small devices to service systems.
6. Simplicity in Rust's memory model and runtime enables it for any domain in a product.


## ReasonML: React as a Language and what the Future looks like • Peter Piekarczyk • GOTO 2019

URL: [https://www.youtube.com/watch?v=xGN4BMPbk7Q](https://www.youtube.com/watch?v=xGN4BMPbk7Q)

1. Presentation about ReasonML, a functional language from Facebook developed alongside React Native
2. Reason combines OCaml's type system with JS syntax, allowing developers to write both front and back-end code in one language
3. Type inference ensures correctness of code while writing, reducing the need for boilerplate
4. Reason allows for easier debugging due to better error messages and type safety
5. The community is still small but growing rapidly as it gains traction with developers
6. React faced similar criticism when first introduced, but eventually gained widespread adoption
7. Recommendation to try out Reason and give it a chance to potentially gain the same popularity as React.


## Achieving Functional Programming in Java • John Napier • GOTO 2019

URL: [https://www.youtube.com/watch?v=VUH_HhAaNpc](https://www.youtube.com/watch?v=VUH_HhAaNpc)

1. Presentation on Functional I/O in Rust using Lambda library
2. Explanation of the Lambda library as an FFI binding to PureScript's Effect type
3. Discussion of Rust's synchronous and asynchronous operations, and how they can be combined in a monadic fashion
4. Demonstrations of using Lambda for functional I/O
5. Explanation of the IO monad to perform I/O operations within context provided or 'no context'
6. Introduction to computational effects like logging and tracing
7. Discussion of using bind() and ap() functions to chain I/O operations
8. Overview of Lambda's features like reading from stdin, writing to stdout, working with files, timers, spawning threads, and network sockets
9. Demonstration on how to use the bind() function in a real-world example
10. Concept of monadic bind allowing for composing asynchronous operations
11. Lambda being released under the MIT license with support available via GitHub issues and chat channels. Encouragement to rate this session honestly.


## Embracing the Future in a Multi-Platform World: A Kotlin Story • Sean McQuillan • GOTO 2019

URL: [https://www.youtube.com/watch?v=xilI3dIOJfI](https://www.youtube.com/watch?v=xilI3dIOJfI)

1. Kotlin talk overview: language evolution, major versions, and future plans.
2. Major features introduced in Kotlin 1.3 include coroutines for simplifying asynchronous programming and null safety for eliminating null pointer exceptions.
3. Coroutine examples demonstrated through a Sudoku solver application.
4. Multiplatform Kotlin enables developers to share app logic across iOS, Android, JVM, and Native (C/C++). It's still in beta phase but can help solve multi-threading issues and Heisenbugs.
5. Attendees encouraged to check out a real sampling project showcasing cross-platform ios and android development.


## Server-side Kotlin with Coroutines • Roman Elizarov • GOTO 2019

URL: [https://www.youtube.com/watch?v=hQrFfwT1IMo](https://www.youtube.com/watch?v=hQrFfwT1IMo)

1. Promise-based asynchronous programming is the standard way to write asynchronous code in JavaScript.
2. Promises simplify error handling and concurrency management compared to callbacks.
3. A promise represents an operation that might fail or succeed and can have three states: pending, fulfilled, and rejected.
4. The then() method defines what should happen when a promise is resolved (fulfillment handler) or rejected (rejection handler).
5. Chaining promises allows you to execute several asynchronous operations sequentially with ease.
6. Promise anti-pattern: Nesting promises within .then() callbacks, leading to difficult-to-read code and poor performance.
7. Async/await is a syntactic sugar that makes working with promises more readable by making asynchronous functions look synchronous.
8. Generators are used under the hood in async/await and return an iterator object, which follows the promise resolution.
9. Iterables and flows provide a more natural way to work with asynchronous programming for JavaScript programmers familiar with collections and sequences.


## The Language of Programming • Anjana Vakil • GOTO 2019

URL: [https://www.youtube.com/watch?v=6EdFiISk22k](https://www.youtube.com/watch?v=6EdFiISk22k)

1. The talk discusses the human aspect of coding and its connections to language and collaboration.
2. Code is a complex, abstract, symbolic system shared by humans similar to natural languages.
3. Programming can be seen as an act of translation between human thought and computer operations.
4. Collaboration is crucial in coding through open-source projects, libraries, and frameworks.
5. The talk emphasizes the need for reflection on how code's collaborative power is utilized to make a positive impact.
6. Resources with more information about cited studies can be found on speaker deck.


## Java Current and Future • Georges Saab & Mikael Vidstedt • GOTO 2019

URL: [https://www.youtube.com/watch?v=vJrHHe3IbQs](https://www.youtube.com/watch?v=vJrHHe3IbQs)

1. Java Development Kit (JDK) 16 is scheduled for March 2021 release with preview features from Project Amber and Loom.
2. JDK 9 to 15 have LTS support, while JEPs are being tracked in all releases.
3. The OpenJDK project has a transparent process with mailing lists, code repositories, and bi-weekly meetings open for public observation.
4. Project Loom brings fibers to the JVM as a new lightweight flow control mechanism for parallelism.
5. Project Panama allows direct access between native libraries and Java code via JNI, with early access binaries available since September 2020.
6. Project Valhalla introduces value types and better support for generic specialization to improve performance inbox analogy.
7. Project Preview enables developers to try out new features before an official release.
8. JEP 413 (Dynamic Linker Integration) brings dynamic linking improvements.
9. The process involves design, implementation, testing, and documentation by volunteers.
10. Early access binaries are available since September 2020 for Panama and Loom previews.
12. no context. (No text provided to extract context.)


## The Soul of Erlang and Elixir • Sasa Juric • GOTO 2019

URL: [https://www.youtube.com/watch?v=JvBT4XBdoUE](https://www.youtube.com/watch?v=JvBT4XBdoUE)

1. Presentation discusses the Elixir programming language and its advantages.
2. Context: Elixir in Action book (50% off today, 40% off for the rest of the DW).
3. Elixir built on Erlang's runtime (its soul according to the speaker).
4. Elixir features like concurrency, fault tolerance, and clear syntax.
5. Elixir provides better scalability and simplicity compared to Ruby or Node.js.
6. Speaker mentions popular frameworks Phoenix and Plug.
7. Discusses Elixir's strong support for functional programming, patterns, and libraries.
8. Explains how Elixir can handle millions of requests with ease.
9. Demonstrates the use of Erlang's OTP principles in a simple chat server example written in Elixir.
10. Encourages audience to evaluate session feedback, and provides book and eBook giveaways.
11. Book offer: 'Elixir in Action', 50% off today with code, 40% off rest of days with code, free copies available after presentation.
(no context provided directly)


## Reaching Beyond Traditional Boundaries with Clojure • Phil Hofmann • GOTO 2018

URL: [https://www.youtube.com/watch?v=2aIWMYcC4Qc](https://www.youtube.com/watch?v=2aIWMYcC4Qc)

1. Discussion on the history and evolution of programming languages (humor).
2. Comparison between C++ and Lisp, highlighting their unique features.
3. Introduction to functional programming languages such as Haskell and Clojure.
4. Explanation of the paradigm shift from imperative to declarative programming through examples like sorting and filtering.
5. Emphasis on learning multiple programming languages, paradigms, and closures.
6. Call for environmental awareness by saving orangutans (humor).
no context (transcript provided)


## Why I Was Wrong About TypeScript • TJ VanToll • GOTO 2018

URL: [https://www.youtube.com/watch?v=AQOEZVG2WY0](https://www.youtube.com/watch?v=AQOEZVG2WY0)

1. TypeScript: a superset of JavaScript that adds optional static typing
2. Advantages for large-scale projects with multiple developers: better collaboration, code quality and maintenance
3. Stickers from NativeScript org available to attendees
4. Contexts when using TypeScript could be helpful:
   - Large teams working on complex projects
   - Teams wanting more structure and type safety
   - Traditional back-end developers joining front-end workflows (TypeScript as a bridge)
   - Developers seeking to learn JavaScript through TypeScript's syntax similarities.
  
(no context provided beyond the given talk transcript.)


## Rust Async Programming in 2018 • Katharina Fey • GOTO 2018

URL: [https://www.youtube.com/watch?v=j0SIcN-Y-LA](https://www.youtube.com/watch?v=j0SIcN-Y-LA)

1. Rust 2018 highlights include (humor).
2. `async/await` features in Rust v1.31 and beyond.
3. async functions allow awaiting multiple futures concurrently with the join function.
4. `tokio` crate simplifies writing asynchronous network code.
5. `std::net` provides a standardized TCP stack for Rust.
6. embedded networking future possibilities.
7. async/await enables more expressive and maintainable code.
8. author works at First System GmbH and Scale Ai Gmbh.


## Fresh Async With Kotlin • Roman Elizarov • GOTO 2018

URL: [https://www.youtube.com/watch?v=hb0hfHVWCS0](https://www.youtube.com/watch?v=hb0hfHVWCS0)

1. Presentation about concurrency in Rust and the Coton library.
2. Concurrency handles multiple tasks happening simultaneously.
3. Traditional approach: multiple threads or OS-level abstractions.
4. Challenges with traditional approaches: data races, synchronization primitives, error-prone.
5. Rust tackles concurrency using async/await and the Tokio library.
6. Coton is a non-blocking I/O library for Rust based on Tokio.
7. Coton provides minimalistic, primitive suspend curtain support for integration with other libraries.
8. Learn more about Coton through its documentation, tutorials, and active community discussions.


## Keeping Up with Java • Sander Mak • GOTO 2018

URL: [https://www.youtube.com/watch?v=cF-rUNCOm2c](https://www.youtube.com/watch?v=cF-rUNCOm2c)

1. Java 9, 10, and 11 LTS (Long-Term Support) releases explained.
2. Oracle's JDK (Java Development Kit) now requires commercial license for production use after the release of Java 16.
3. OpenJDK builds are still freely available from various vendors including Amazon Corretto, AdoptOpenJDK, and Red Hat.
4. Oracle JDK will include more features, while OpenJDK will have security patches and bug fixes post-LTS.
5. LTS release schedule changed to every six months starting with Java 17.
6. Non-LTS releases (R-Releases) will receive Public Updates for six months, then only Security Updates for another year.
7. Adopting a vendor's JDK becomes crucial if moving between LCS (Long-Term Continuous Support) to LCS releases.
8. Strategy for adopting Oracle, Amazon Corretto, AdoptOpenJDK, Red Hat, or others needs to be decided based on requirements and preference.
(no context provided in the input explanation).


## Zen and the Art of Convincing Your Company to Use Rust • Ashley Williams • GOTO 2018

URL: [https://www.youtube.com/watch?v=Pn-1so-Ibsg](https://www.youtube.com/watch?v=Pn-1so-Ibsg)

1. Introducing Rust as a systems language for the webassembly WASMimpac (crab-related project)
2. Explaining why developers might hesitate to adopt Rust: lack of context, fear of failure, and limited client-side usage
3. Discussing how Rust can potentially solve common developer problems like memory safety and performance issues
4. Sharing a real-life example where the author implemented Rust in a large-scale application, leading to faster page loads and cost savings
5. Highlighting that Rust is not just for systems programming but also for smaller components
6. Encouraging developers to give Rust a try while promoting WASMimpac, a tool for using Rust with web browsers or Node.js.
```
no context (as the provided text is primarily a transcript of a presentation)
```


## Functional Programming in 40 Minutes • Russ Olsen • GOTO 2018

URL: [https://www.youtube.com/watch?v=0if71HOyVjY](https://www.youtube.com/watch?v=0if71HOyVjY)

- Functional programming emphasizes avoiding mutable state and using immutable data
- Side effects should be isolated and controlled
- Pure functions are easier to understand, test, reason about, and parallelize
- Higher-order functions allow reusing and composing logic without redundant code
- Lazy evaluation can improve performance by only evaluating needed parts of an expression
- Pattern matching aids readability and pattern matching with algebraic data types allows for more precise error handling and control flow
- Type systems aid in catching errors earlier, improving safety, and enabling better tooling
- Functional programming relies heavily on functions (944 out of 1000 methods in a large Swift codebase) with smaller amounts of interfaces and other elements.


## The Do's and Don'ts of Error Handling • Joe Armstrong • GOTO 2018

URL: [https://www.youtube.com/watch?v=TTM_b7EJg5E](https://www.youtube.com/watch?v=TTM_b7EJg5E)

1. In financial trading systems, there are issues with the sequencing of messages and ensuring correct processing.
2. Watson, IBM's supercomputer, faced problems while playing Jeopardy! due to its inability to handle natural language and the sequence of questions.
3. The speaker mentioned his PhD thesis on dynamic session type-checking to manage message sequences.
4. There might be systems today that address message sequencing concerns, but specific examples were not provided in the context.
5. The speaker is involved in high-frequency trading and is aware of a few such systems within this field.


## Software Automation in a Polyglot Stack • Jessica Kerr • GOTO 2018

URL: [https://www.youtube.com/watch?v=cEyjEEK0xuo](https://www.youtube.com/watch?v=cEyjEEK0xuo)

1. Discussion on the challenges of advocating for new tech in an established environment.
2. Factors to consider: risk, cost, and time required for implementation.
3. Importance of understanding management's objectives and demonstrating the business case for adopting new technologies or tools.
4. Addressing concerns about maintaining existing systems while introducing change.
5. Emphasizing new capabilities and safety from o no context.


## The Robustness of Go • Francesc Campoy • GOTO 2018

URL: [https://www.youtube.com/watch?v=40d26ZGfhR8](https://www.youtube.com/watch?v=40d26ZGfhR8)

1. Discussion about the Go programming language and its popularity.
2. Comparison with other languages like Python, Rust, C++, and Haskell.
3. Go's focus on simplicity, concurrency, and ease of use for web development.
4. Criticisms include static typing limitations, lack of higher-order functions, and difficulty in using functional programming.
5. Possible future enhancements to the language: higher-order functions (no context provided).
6. Francesco Soldato's experience with Go at Google.
7. Idea for a project that ensures communication between two routines happens on the same machine if possible (named project not remembered in transcript).


## Functional Programming with Kotlin • Hadi Hariri • GOTO 2018

URL: [https://www.youtube.com/watch?v=eNe5Nokrjdg](https://www.youtube.com/watch?v=eNe5Nokrjdg)

1. Introduction to Ruby's metaprogramming capabilities.
2. Method missing and how it responds to undefined methods by executing a block, allowing the creation of DSLs (Domain Specific Languages).
3. Example of creating a simple DSL for building HTML using method missing.
4. The `respond_to?` method can be used to check if an object recognizes a specific message.
5. Introduction to ActiveSupport and its Safe buffer feature, enabling the use of a template language without risking injection attacks.
6. Concept of SL (Structured Language) for building HTML with more complex syntax and semantics while still being human-readable.
7. Use of markdown instead of creating HTML directly directly direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct direct business
8. No mention of Ruby's metaprogramming capabilities being limited to new classes or needing explicit permission for old classes in the context provided.


## C++ - the Newest Old Language • Matt Godbolt • GOTO 2018

URL: [https://www.youtube.com/watch?v=HAFrggEDr5U](https://www.youtube.com/watch?v=HAFrggEDr5U)

1. Discussion about C++ as a modern language.
2. Matt (possibly the speaker).
3. C++11 and its new features.
4. Comparison to earlier versions of C++.
5. C++17 and its changes in syntax.
6. Useful libraries like Boost and Modern Template Library (MTTL).
7. C++'s growing popularity for systems programming, game development, and other real-world applications.
8. Compiler Explorer website for testing code snippets.
9. Adoption barriers for new learners include less standardized syntax compared to other languages.
10. No specific context provided in the transcript.


## Why is Rust Successful? • Florian Gilcher • GOTO 2017

URL: [https://www.youtube.com/watch?v=-Tj8Q12DaEQ](https://www.youtube.com/watch?v=-Tj8Q12DaEQ)

1. Rust is a system language with a focus on safety and performance.
2. Memory management in Rust is handled via ownership, borrowing, and lifetimes.
3. Rust has an efficient error handling mechanism using Result type.
4. Rust has traits for generic programming and type systems with features like pattern matching and tuple structs.
5. The Cargo build system manages dependencies, compilation, and testing in Rust projects.
6. Crates are reusable libraries or executables built from Rust code.
7. Blocking IO is discouraged in Rust, using async IO instead.
8. Rust offers a block-based concurrency model via threads and tasks.
9. The Rust ecosystem includes compilers, build systems (Cargo), toolchains, libraries, frameworks, and learning resources.
10. Rust has good support for developing games and graphics libraries like Glyph, Pixelbloc, or Diesel in databases.
11. Blocking I/O can be handled via async blocks, futures, or tokio crate.
12. There are options for concurrent programming in Rust using threads, tasks, or atomics.
13. The rust-gaming Discord server and community are helpful for game development using Rust.
14. Blocking I/O can be converted into non-blocking with the help of async library blocks.
15. Rust has tools like Clippy for linting, and there's support for blockchain development in Rust too.
16. The standard library in Rust supports various use cases such as network communication, data management, or graphical user interfaces (GUIs).
17. Rust offers concurrency with helpers like Join or task-based programming using the Tokio crate.
18. Rust supports building web applications via crates like actix-web or rocket.
19. The Rust ecosystem has tools and libraries for cross-platform game development, such as GUI libraries (Gfx or gbm).
20. Asynchronous network programming is possible with the Tokio crate in Rust.
21. Rust offers a simple approach to writing code, ensuring memory safety, threading model, and having no runtime dependencies.
22. The latest stable version of Rust can be installed on macOS via Homebrew or directly from the website.
23. The main differences between C and Rust are memory management, concurrency models, lifetimes, and safer code development practices.
24. Rust supports building games for multiple platforms like Windows, Linux, and macOS using toolchains such as GCC, Clang, or Rust's native one.


## Flutter: The Best Way to Build for Mobile? • Kasper Lund • GOTO 2017

URL: [https://www.youtube.com/watch?v=1BXg4wfB9pA](https://www.youtube.com/watch?v=1BXg4wfB9pA)

1. Flutter is a mobile UI framework built by Google, focusing on delivering native-like experiences on iOS and Android platforms.
2. Flutter uses the Dart programming language for development, which offers high performance and efficient use of CPU resources.
3. PWAs (Progressive Web Apps) utilize existing web technologies and are limited due to compatibility and performance issues when targeting mobile devices.
4. Flutter addresses these limitations by offering a faster development workflow, more predictable code execution, and native-level performance.
5. Legacy browser features can pose trade-offs in mobile app development on top of complex foundations.
6. Both Flutter and PWAs have their own strengths and weaknesses; Flutter's focus on mobile app development allows it to be more efficient bypassing web technologies for mobile devices.
7. Audience is encouraged to ask questions and vote in the session.


## JavaScript at Uber • Dustin Whittle • GOTO 2017

URL: [https://www.youtube.com/watch?v=IG9gwgUiqZM](https://www.youtube.com/watch?v=IG9gwgUiqZM)

1. Presentation on Uber's engineering tools and practices for building and improving their platform and user experience.
2. Breakdown into three main categories: data infrastructure, code collaboration, and visualization & sharing.
3. Data Infrastructure includes uber-genie (data catalog), uber-mimic (data access and workflow tool), and uber-curry (data processing).
4. Code Collaboration tools include uber-artemis (internal package registry) and uber-archon (code review system).
5. Visualization & Sharing includes uber-jupiterhub (interactive data science notebooks), uber-pandora's-box (centralized monitoring and alerting platform), and uber-galaxy (data exploration tool).
6. Code collaboration happens on GitHub with contributions to open-source projects like goreleaser and gogs, and code hosted on GitHub Enterprise.
7. Codeshare and artemis allow private dependency hosting for Uber's internal libraries, while codebase is managed using gitflow branching model.
8. Code sharing with the public includes Uber's Geofencing library and other projects on Github.
9. Internal collaboration occurs through Confluence Wiki and external knowledge sharing happens via blog posts and presentations at conferences or meetups like KubeCon, Velocity, and Strata Data Conference.


## Elixir: The only Sane Choice in an Insane World • Brian Cardarella • GOTO 2017

URL: [https://www.youtube.com/watch?v=gom6nEvtl3U](https://www.youtube.com/watch?v=gom6nEvtl3U)

1. Elixir is a dynamic functional language for building scalable and maintainable software
2. Erlang VM provides the runtime environment, fault tolerance, concurrency, and distribution
3. Elixir syntax is inspired by Ruby and Clojure
4. BEAM compiler converts Elixir into Erlang ASP format at compile time
5. GenSer allows for creating servers with ease
6. No explicit thread management needed in Elixir due to concurrency provided by Erlang VM
7. Macros enable reusable code through compile-time functions
8. Elixir adopts a more module-based approach for reusing code, using compiled time functions emitting Erlang ASP
9. GenServer module compiles Erlang ASP code into modules being used in.
10. Context provided during Q&A session.


## Introducing Elm to a JavaScript App • Richard Feldman • GOTO 2017

URL: [https://www.youtube.com/watch?v=28aJOb1A34o](https://www.youtube.com/watch?v=28aJOb1A34o)

1. Elm can be used in production with existing JavaScript applications by gradually replacing parts.
2. Include the elm-reactor script and define an element to render Elm into within your HTML.
3. Use `elm-make` to compile your Elm code and embed it in your page through a Script tag.
4. Set up communication between JavaScript and Elm using Ports, which handle events and messages.
5. Start with small parts of your application written in Elm and gradually replace more JavaScript components over time.
6. The ultimate goal is to have an entire production app built in Elm. 
7. Luke Westby, creator of the Ellie Elm application, is recommended for Elm training.
8. To incorporate Elm into existing JavaScript applications, you only need a DOM element to render into and knowledge on how to use Ports.


## Demystifying Scala • Kelley Robinson • GOTO 2017

URL: [https://www.youtube.com/watch?v=IayQ7lxPUP4](https://www.youtube.com/watch?v=IayQ7lxPUP4)

1. Tomas Rounaghi discusses his experience with Scala and its development history.
2. Martin Odersky created Scala to address limitations in Java, inspired by Haskell and ML.
3. Scala is statically-typed, supports functional programming and object-oriented features.
4. Type inference, implicits, and pattern matching are notable aspects of Scala.
5. The community addresses concerns regarding performance and runtime overhead.
6. Scala has a learning curve but rewards with code readability, conciseness, and maintainability.
7. It has strong adoption in big data processing and streaming at companies like Twitter, LinkedIn, and Netflix.
8. Typesafe Stack (now Lightbend) aims to bridge academic influences of Scala and practical uses.
9. Tomas encourages new users to learn from the community, use IDEs or editors with good support, and focus on fundamentals.


## Programming Across Paradigms • Anjana Vakil • GOTO 2017

URL: [https://www.youtube.com/watch?v=Pg3UeB-5FdA](https://www.youtube.com/watch?v=Pg3UeB-5FdA)

1. Discussion on microservices and their relation to functional programming and object-oriented programming.
2. Microservices can be seen as a functional decomposition approach, where each service operates on its inputs and produces an output.
3. Functional programming has inspired some aspects of microservices like immutability and statelessness.
4. Object-oriented programming principles can also be applied to microservices through the use of object composition and message passing between services.
5. Allen Kay's concept of OOP, where systems are made up of small chunks communicating with each other, resembles a micro functional decomposition approach inspired by both functional and object-based approaches.
6. Perspective on microservices as pure functions, with inputs passed from one service to another.



## Why You Should Take Another Look at C# • Mads Torgersen • GOTO 2016

URL: [https://www.youtube.com/watch?v=zQXNq-isqFI](https://www.youtube.com/watch?v=zQXNq-isqFI)

1. Presentation by Mads Torgersen on new C# 9.0 features and what to expect in the future.
2. Record & Play for quick replay of keyboard inputs in Visual Studio, improving debugging experience.
3. Global Imports simplify using namespaces without explicit import statements.
4. Range operators provide compact syntax for common operations like foreach or slice expressions.
5. Target-typed patterns enable pattern matching with type annotations, increasing flexibility and safety.
6. Records offer automatic properties, value tuple-like data structures with less boilerplate code.
7. Ref improvements allow passing ref values to methods that use them as out parameters.
8. Possible addition of NullRefType, a nullable version of ref types, in future C# versions for better nullability handling.
9. Encouraging attendees to fill out evaluations and thanking the audience for their time and attention.


## Exploring Swift Memory Layout • Mike Ash • GOTO 2016

URL: [https://www.youtube.com/watch?v=ERYNyrfXjlg](https://www.youtube.com/watch?v=ERYNyrfXjlg)

1. Swift Evolution proposals overview:
   - A28: Optional Chaining Syntax Extension for Subscripts (rejected)
   - A0346: Concurrency APIs via Actors and Concurrency Kit (accepted)
   - A0359: Allow Overloaded Operators to Return Different Types (accepted)
   - A0372: Allow Protocol Requirements to be Generic (accepted)
   - A0184: Add New Binary Floating-Point Operations (accepted)
2. Swift 5.6 features:
   - Concurrency via actors and Async/Await
3. SwiftUI improvements in Xcode 13:
   - LazyVStack, LazyHStack
   - Previews
   - Dynamic Type Support (DTS)
4. Memory Graph visualization tool in Xcode 13 for debug graph context no


## Exploring RxJava 2 for Android • Jake Wharton • GOTO 2016

URL: [https://www.youtube.com/watch?v=htIXKI5gOQU](https://www.youtube.com/watch?v=htIXKI5gOQU)

1. RxJava 2.0 is a major update with significant improvements in API design and performance.
2. The main goal is to simplify the library, making it easier for developers to understand and use.
3. RxJava 2.0 introduces functional operators for more expressive code and improved type safety.
4. Operators have been grouped by source type for better discovery.
5. Sources like Observable and Flowable have new names with consistent naming patterns.
6. The Flowable operator is a non-blocking alternative to the old Operator.
7. New operators like concat, merge, combine, and switch allow more flexible composition.
8. RxJava 2.0 introduces Flowable and ObservableCompat for backward compatibility.
9. The new FlowableSingle type unifies Single and Observable.
10. The library now provides better support for concurrent streams.
11. New operators like concat, merge, combine, and switch provide more flexibility in composing streams.
12. RxJava 2.0 encourages developers to embrace asynchronous sources and compose them together, making our apps truly reactive.


## Microservices in Go • Matt Heath • GOTO 2016

URL: [https://www.youtube.com/watch?v=WiCru2zIWWs](https://www.youtube.com/watch?v=WiCru2zIWWs)

1. Scaling a monolithic system can result in high complexity and slow growth, leading to refactoring and service deletion.
2. The platform consists of 50+ services, with most written in Go and some in Java/Scala.
3. Infrastructure includes Kubernetes, Envoy Proxy for circuit breaking, and Consul for service discovery.
4. They use GitOps principles with Argo CD for deployment.
5. The team focuses on simplifying processes, like connecting to different providers using one small NGO service.
6. The platform's graph has grown from 10+ services in 2020 to over 40 services today.
7. They use Telemetry with Prometheus, Jaegar, and OTPR to monitor their systems.
```text
no context provided.


## Kotlin - Ready for Production • Hadi Hariri • GOTO 2016

URL: [https://www.youtube.com/watch?v=R0J_Jl7bKY8](https://www.youtube.com/watch?v=R0J_Jl7bKY8)

1. Keynote speaker discusses JetBrains' history, starting with IntelliJ IDEA and growing to multiple successful products.
2. Kotlin language was created as a response to Java's verbosity, aimed at improving developer productivity and ease of learning.
3. Kotlin interoperates with Java, allowing for low-risk adoption in existing projects.
4. The speaker shares their personal enjoyment using Kotlin coming from a C# background.
5. JetBrains' commitment to Kotlin is strong due to its usage within their own products and the business model being based on JetBrains tooling.
6. Comparison between last night's encounter with Kotlin and this morning's experience with Java's boilerplate in Android Studio.
(no context provided outside of the keynote speech).


## MicroPython & the Internet of Things • Damien George • GOTO 2016

URL: [https://www.youtube.com/watch?v=EvGhPmPPzko](https://www.youtube.com/watch?v=EvGhPmPPzko)

1. Presentation focused on creating a web scraping tool for LinkedIn profiles, called ScrapLinked.
2. Inspired by the need to find potential candidates quickly and efficiently for a company's recruiting team.
3. The tool uses Selenium to open a headless browser, interact with LinkedIn, and extract data.
4. Faced challenges in finding email addresses on LinkedIn due to various factors like privacy settings, country restrictions, or missing information.
5. Developed a solution using regex patterns to detect potential email formats from users' profiles and verify their validity through an external API.
6. The tool also provides additional features such as downloading profile pictures and storing extracted data in CSV files.
7. ScrapLinked is available on GitHub for open-source contribution, hoping it grows into a sustainable community project.


## Using Modern C++ In Anger • Todd Montgomery • GOTO 2016

URL: [https://www.youtube.com/watch?v=9KljYagEPnE](https://www.youtube.com/watch?v=9KljYagEPnE)

1. Discussion about Cassandra, a distributed database management system
2. Scalability and fault tolerance benefits
3. Collaboration between DataStax and the Apache Software Foundation for Cassandra development 
4. Cassandra's adoption in various industries like finance, healthcare, and streaming media
5. Dynamic partitioning, improved index usage, and CDC enhancements added in recent releases
6. Pipeline benchmark improvements and faster read/write throughput
7. Continued efforts for new language drivers (Java, Python, Node) and development of Go and C++ drivers 
8. Exploration of persistence and replication techniques with unique designs
9. Collaboration with Martin for innovative ideas and trying out different approaches to see what works best.


