# Stuff You Should Know (as a computing professional)

This list was created for students and alumni of PDX Code Guild, however, anyone interested in being a computing professional could benefit from this list.

The list is largely biased towards the "software engineering" side of computing.

## Evan's List

This is Evan's opinionated list of "stuff everyone should know". Further down in the document, an alumni contributed list is given as well.

The list contains both important computer science concepts, as well as software development tools and techniques.

Much of this list was/will not be covered in the Code Guild curriculum. Think of it as a guide for further study.

Note: it took me 10 years to learn all this, including a bootcamp, a CS degree, on the job learning, and a ton of self-study along the way! Don't be overwhelmed. This is a journey, and you are going to be here a while. Settle in and enjoy the ride!

*Note*: other instructors at Code Guild may not agree with this list, and that is ok! They are free to submit a pull request :)

### The List

* Unix
  * "Unix is an IDE"
  * Mac and Linux both have a Unix interface under the hood
  * even Microsoft is moving in this direction
  * server environments are almost always unix-based
* the command line: bash, grep, awk, sed, find, bash scripts, etc.
  * start with the built-in Unix commands, then move on to 3rd party "useful command line programs"
  * learn how to pipe commands together to compose new programs!
* Regular Expressions
* Git
  * rebasing, merging, etc.
* CSS basics. Box model
* Algorithms + Data Structures
  * Binary Search
  * Big O Notation
  * Stacks, Queues, Trees, Linked Lists, Graphs, Hash Tables
    * Bare minimum you *must* know these!
  * Specialized Trees
    * Heaps
    * Red Black
    * Trie
    * Merkle
    * Markov Chains
* Security basics
  * Check out the OWASP top ten list for example
  * Reverse engineering
  * Reading a objdump
  * Understanding compilers and assembly
* Databases
  * SQL vs NoSQL
  * CAP Theorem
* Auth
  * authentication vs authorization
* Testing
  * unit, integration, end-to-end, etc.
* Architecture basics
  * separation of concerns
  * "layered" architectures
  * microservices vs mono repos
* Design Patterns
  * Publish/Subscribe (aka "pubsub")
  * MVC (model view ccontroller)
  * lots more!
* Low Level
  * binary
  * how floating point numbers are represented in bits vs integers
  * how memory addressing works
  * how CPU works (at a basic level)
  * logic gates
    * everything in a computer can be constructed from simple logic gates!
  * assembly language basics
    * gain a basic understanding of how assembly language works to illuminate how computers work in general
    * will also make you appreciate high level languages that much more!
* Higher-order Functions
  * lambdas
  * closures
  * map/filter/reduce
  * callbacks
* Concurrency basics
  * concurrency vs parallelism
  * synchronous vs asynchronous
  * Processes vs Threads
* Theory of Computation basics
  * Turing Completeness
    * what implication does this have for programming languages?
  * The Halting Problem
    * what implications does this have for computers? 
* The Internet
  * how internet works and networking in general
  * the web vs. the internet (not the same thing!)
* Managing Complexity
  * Coupling
    * coupling is a source of complexity, reduce coupling!
  * Abstraction
  * Modularity
* Programming Language Theory basics
  * Syntax vs semantics
  * Static vs Dynamic semantics
  * Static vs Dynamic types
  * Syntactic Sugar
  * Compiled vs Interpreted
  * Imperative vs Declarative
  * Paradigms (Procedural, FP, OOP, Logic, etc.)
* Hashing
  * hash tables, cryptographic hashes, content-based addressing, hashing passwords
  * hashing vs encrypting (not the same thing! Do not encrypt passwords, hash them instead!)
* Encryption
  * RSA
  * PGP
  * Public key cryptography
  * How to use hashes to make your cryptography even more secure
    * SHA1
    * SHA256
    * SHA3 (Keccak256)
* Caching
  * many problems are solved with a cache
* History
  * [History of Software Engineering](https://learning.acm.org/techtalks/histofsofteng)
  * history of the web, hypertext, javascript, etc.
  * history of Computer Science
    * timeline of important events
    * binary logic -> boolean algebra -> Jacquard's loom -> punch card systems, etc.
    * Charles Babbage and Ada Lovelace
    * Church-Turing thesis
    * George Bool
    * Haskell Curry
    * Shannon and information theory
    * von Neumann
    * Bell Labs
    * Xerox PARC
  * One of the best books ever: The Dream Machine by M. Mitchell Waldrop 
* Functional Programming
  * Concepts and usage, most modern languages allow you to do this pretty easily along with OOP
  * Languages that utilize this to a tee:
    * Haskell
    * Elm
    * Pony
    * Erlang
    * Elixir
* Distributed Systems
  * The nine nines
  * Fault tolerance and resiliency
  * Consensus
  * Peer to peer communication
* Serialization
  * TCP packets
  * Binary encodings in general (such as JPEG, this ties into the next 2 sections)
* Error Correction
  * Hamming codes
  * Reed Solomon codes
* Compression
  * Lampel-Ziv
  * DCT Transforms
  * Deflate

### People

Study these people. Read what they wrote, watch their talks, etc.

* Douglas Engelbart
  * "one of the greatest men of all time"
  * [The Mother of All Demos](https://www.youtube.com/watch?v=yJDv-zdhzMY)
  * [A few words on Doug Engelbart](http://worrydream.com/Engelbart/)
* Ted Nelson
  * coined the terms hypertext and hypermedia 
  * learn about his Xanadu system and compare it with the web today
  * [Computers for Cynics](https://www.youtube.com/playlist?list=PLAdoQNdX3OqUIT0h2k5kUjDN7rDBnmbRl)
  * Jaron Lanier on Xanadu: [First Thought, Best Thought](https://www.youtube.com/watch?v=5i6LXdj_Z6s)
* Alan Kay
  * watch any of his talks on youtube, read his Quora answers
* Rich Hickey
  * watch any of his talks on youtube (although some are specific to the language Clojure, not all of them are)
* Leslie Lamport
  * has invented many of the tools academics and distributed systems use
    * LaTeX
    * PAXOS Consensus Algorithm
    * Many more
  * Invented a mathimatically provable solver for computer programs called TLA+
    * See his series on this on youtube
* Linus Torvalds
  * Founded and started the Linux OS
  * Not a lot of talks, but his code is a great read
* Dennis Ritchie
  * Wrote B, C and Unix (Along with Ken Thompson)
  * Basically one of the godfathers of all modern programming, the C style is used in almost every modern procedural language
* Douglas Crockford
  * has great talks about javascript on youtube
* David Beazley
  * "Jimi Hendrix of Python"
  * has awesome live-coding talks on youtube, specializing on Python
* Edsger W. Dijkstra
  * has some sharp criticisms of our industry that are worth reading

### Papers

Read these papers. Being able to read papers is a super helpful skill when you get into more research-oriented roles. The following papers are on the more accessible side, so should make good practice.

Note: some of these aren't actually "papers", but may be articles, blog posts, or sections from a book

* Donald Knuth - Notes on the Errors of Tex
* Paul Graham - [Beating the Averages](http://www.paulgraham.com/avg.html)
* Dijkstra's EWDs
* Chapters from: [The Architecture of Open Source Applications](https://aosabook.org/en/index.html)
  * chapters are self-contained, easy to read case studies of real software architectures
* Nick Seaver - Captivating algorithms: Recommender systems as traps
* [The Night Watch](https://scholar.harvard.edu/files/mickens/files/thenightwatch.pdf)
  * Epic and hilarious!
* [The Most Important Software Innovations](https://dwheeler.com/innovation/innovation.html)
* Fred Brooks - No Silver Bullet - Essence and Accident in Software Engineering
* Liu, Lu, Musuvathi, Nath - What bugs cause production cloud incidents?
* Leveson, Turner - Investigation of Therac-25 Accidents
* Niklaus Wirth - A Plea For Lean Software
* Tony Hoare - The Emperor's old clothes (ACM Turing award lecture)
* Vannevar Bush - As We May Think
* Chapters from Google's [Site Reliability Engineering](https://landing.google.com/sre/sre-book/toc/index.html)
  * chapters are largely self-contained essays, fairly easy to read, provides a peek behind the curtain regarding how Google operates internally
* Licklider - Man-Computer Symbiosis
* **Distributed Systems**
  * Crypto Currencies:
    * Bitcoin: A Peer-to-Peer Electronic Cash System [Whitepaper](https://bitcoin.org/bitcoin.pdf)
    * Ethereum: Inspired by bitcoin, but uses a distributed ledger/state machine to allow for programs to be run across all nodes that agree with the block consensus. [Whitepaper](https://ethereum.org/en/whitepaper/)
    * Hashcash: The precursor to bitcoin [Whitepaper](http://www.hashcash.org/papers/)
  
* Ken Thompson - Reflections on Trusting Trust

## Alumni Contributions

The following list was provided by asking Code Guild alumni for a list of things they wish they would have learned more about during bootcamp.

I will add to this as more alumni contribute!

* Classes (OOP)
  * [classes vs data structures + functions](https://blog.cleancoder.com/uncle-bob/2019/06/16/ObjectsAndDataStructures.html)
* Environment Variables
* How to *efficiently* package Python code as a single executable file
* Algorithms + Data Structures
  * I know it's on my list above, but students are asking for more as well!
