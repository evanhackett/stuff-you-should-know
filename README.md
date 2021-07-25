# Stuff You Should Know (as a computing professional)

This list was created for students and alumni of PDX Code Guild, however, anyone interested in being a computing professional could benefit from this list.

The list is largely biased towards the "software engineering" side of computing.

## Evan's List

This is Evan's opinionated list of "stuff everyone should know". Further down in the document, an alumni contributed list is given as well.

The list contains both important computer science concepts, as well as software development tools and techniques.

Much of this list was/will not be covered in the Code Guild curriculum. Think of it as a guide for further study.

Note: it took me 10 years to learn all this, including a bootcamp, a CS degree, on the job learning, and a ton of self-study along the way! Don't be overwhelmed. This is a journey, and you are going to be here a while. Settle in and enjoy the ride!

*Note*: other instructors at Code Guild may not agree with this list, and that is ok! They are free to submit a pull request :)

**Update**: Other people who have added contributions to this list: [Zack Kollar](https://github.com/SeedyROM)

### The List

* Unix
  * "Unix is an IDE"
  * Mac and Linux both have a Unix interface under the hood
    * even Microsoft is moving in this direction
  * server environments are almost always unix-based
  * try to understand the oft-cited "Unix Philosophy"
    * see McIlroy's thoughts on pipes, ESR's writings, and Lampson's "Hints for Computer System Design"
* the command line: bash, grep, awk, sed, find, bash scripts, etc.
  * start with the built-in Unix commands, then move on to 3rd party "useful command line programs"
  * learn how to pipe commands together to compose new programs!
* Regular Expressions
  * "no one ever saved time by _not_ learning regular expressions"
* Git
  * rebasing, merging, etc.
  * keep in mind that git is a leaky abstraction, and so it helps a lot to learn the underlying data structures
* CSS basics: Box Model, etc.
  * a lot of programmers ignore learning CSS, but many of us end up working as "full stack" developers, and so when we have to do CSS it takes us longer than it should. Just spend some time to actually learn it, instead of googling every little thing you have to do =)
* Algorithms + Data Structures
  * Binary Search
  * Big O Notation
  * Stacks, Queues, Trees, Linked Lists, Graphs, Hash Tables
    * Bare minimum you *must* know these!
  * More advanced
    * Heaps
    * Red Black tree
    * Trie
    * Merkle tree
    * Markov Chains
    * Bloom Filter
* Security basics
  * Check out the OWASP top ten list for example
  * authentication vs authorization

* Databases
  * SQL vs NoSQL
  * CAP Theorem

* Testing
  * unit, integration, end-to-end, etc.
  * learn TDD so you can at least participate in the conversation, you might not agree with it

* Architecture basics
  * separation of concerns
  * "layered" architectures
  * microservices vs mono repos

* Design Patterns
  * Publish/Subscribe (aka "pubsub")
  * MVC (model view ccontroller)
  * lots more!
  * also keep in mind the patterns community has sort of split off into other things (like Scrum patterns for example) and so there are many "patterns" worth checking out beyond just "OOP patterns" 

* Low Level
  * binary
  * how floating point numbers are represented in bits vs integers
  * how memory addressing works
  * how CPU works (at a basic level)
  * logic gates
    * everything in a computer can be constructed from simple logic gates!
    * check out "Elements of Computing Systems" (aka "nand2tetris") if you want to walk through building a computer from scratch
      * there's a fun graphical version that covers part of the text here: [NandGame](http://nandgame.com/)
  * assembly language basics
    * gain a basic understanding of how assembly language works to illuminate how computers work in general
    * will also make you appreciate high level languages that much more!

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
    * many hypertext systems could have been built on top of the internet, the "World Wide Web" is just what we happened to end up with
      * see Nelson's Xanadu system for an example of an alternative vision

* Managing Complexity
  * Coupling
    * coupling is a source of complexity, reduce coupling!
  * Abstraction
  * Modularity
  * also worth pointing out that empirical software engineering research has identified "lines of code" as a primary source of complexity, meaning reducing lines of code is at least correlated with reducing complexity
    * check out VPRI's STEPS project to see this idea taken seriously

* Programming Language Theory basics
  * Syntax vs semantics
  * Static vs Dynamic semantics
  * Static vs Dynamic types
  * Syntactic Sugar
    * "Syntactic sugar causes cancer of the semi-colon"
    * what do you think is meant by this?
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
    * SHA1, SHA256, SHA3 (Keccak256)

* Caching
  * many problems are solved with a cache. You should understand why and how

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
* Object Oriented Programming
  * read [The Early History Of Smalltalk](http://worrydream.com/EarlyHistoryOfSmalltalk/), written by the man who coined the term "Object Oriented Programming", Alan Kay
    * this document really helps to understand what OOP is really about, in spirit

* Distributed Systems
  * The nine nines
  * Fault Tolerance
  * Availability
  * Consistency
  * Consensus
  * Peer to peer communication
  * also worth looking into the various programming models throughout history, some of which are still really good ideas that could be expanded on today. Some examples:
    * Linda Tuple Spaces
    * Actor Model

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
  * watch any of his talks on youtube (although many of his talk appear to be specific to Clojure, I generally get a lot out of them despite never having used Clojure before)
* Leslie Lamport
  * has invented many of the tools academics and distributed systems use
    * LaTeX
    * PAXOS Consensus Algorithm
    * Many more
  * Invented a formal specification language for computer programs called TLA+
    * See his series on this on youtube
* Linus Torvalds
  * Founded and started Linux, also created Git
  * Not a lot of talks, but his code is a great read
* Dennis Ritchie, Ken Thompson, Rob Pike, Doug McIlroy
  * all of these people were involved with creating Unix and the surrounding tools (including the C language, grep, pipes, etc.)
  * many of their old papers are still worth reading today
* Douglas Crockford
  * has great talks about javascript on youtube
* David Beazley
  * "Jimi Hendrix of Python"
  * has awesome live-coding talks on youtube, I particularly enjoyed the ones on concurrency
* Edsger W. Dijkstra
  * has some sharp criticisms of our industry that are worth reading (you can find many of these in his "manuscripts")
  * also made seminal contributions to the field, worth knowing about

### Papers

Read these papers. Being able to read papers is a super helpful skill when you get into more research-oriented roles. 

The following papers are on the more accessible side, so should make good practice.

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
  * it's just referenced so often, even still today, that I think everyone should read it
* Liu, Lu, Musuvathi, Nath - What bugs cause production cloud incidents?
* Leveson, Turner - Investigation of Therac-25 Accidents
* Niklaus Wirth - A Plea For Lean Software
* Tony Hoare - The Emperor's old clothes (ACM Turing award lecture)
* Vannevar Bush - As We May Think
* Chapters from Google's [Site Reliability Engineering](https://landing.google.com/sre/sre-book/toc/index.html)
  * chapters are largely self-contained essays, fairly easy to read, provides a peek behind the curtain regarding how Google operates internally
* Licklider - Man-Computer Symbiosis
* Bitcoin: A Peer-to-Peer Electronic Cash System [Whitepaper](https://bitcoin.org/bitcoin.pdf)
* Ken Thompson - Reflections on Trusting Trust
* Meta II - A Syntax-Oriented Compiler Writing Language
  * this paper will blow your mind; it presents a compiler that generates compilers which is also capable of compiling itself 
  * definitely see the [tutorial by James Neighbors](http://www.bayfronttechnologies.com/mc_tutorial.html) which helped me understand the paper
* The Design Philosophy of the DARPA Internet Protocols
  * this is more of a "why" paper than a deep technical dive on how the protocols work
* MapReduce: Simplified Data Processing on Large Clusters (2004)
  * good intro into distributed systems

### Programming Languages

Many students ask me about languages, probably more than anything else. "What programming language should I learn next?" I think this is a consequence of the fact that, for many people, when they are learning to program, the main thing they recognize as a learning objective is features of the language. Loops, if-statements, functions, classes, lists, tuples, dictionaries, etc. This has the consequence of them thinking that the natural next step after learning a language is to learn another language. This is a fine thing to do, but I think it's important to point out all of the other options besides just learning one language after another. You'll notice the vast majority of items on this list did not involve learning another programming language.

That being said, learning languages can be an extremely valuable thing, especially if done properly. The key is to learn a language that changes the way you think about programming. Most languages in the mainstream are not actually that different from each other, so care and judgement has to be taken when deciding how to spend your time.

Given that this list is largely for bootcamp grads, I will assume the reader has learned Python and/or Javascript. 

With all that said, here are my recommendations. Note I have just picked "families" of languages, as the specific one doesn't matter. Choose whichever implementation makes sense to you, the "big idea" of the language is what matters most.

* Lisp
  * choose one of: Common Lisp, Clojure, Racket, Scheme, etc.
  * to see the big idea of "code is data"
* ML
  * choose one of: SML, Ocaml, Haskell, Elm, etc.
  * to see how powerful a strong type system can be, and to gain experience with functional programming
* Smalltalk
  * choose one of: Squeak, Pharo, emulate an older one, etc.
  * to see the big idea of message passing, and how powerful a highly dynamic programming environment can be
* Prolog
  * choose one of SWI-Prolog, SICStus Prolog, GNU Prolog, etc.
    * there are also prolog-like systems developed for other languages (often found in lisps for example)
  * to see how a "declarative logic" language can use relations and constraints to search for solutions
* C
  * the only specific language on this list, also the lowest level and the most mainstream
  * so much of what we use is built up from C. It is simply too ubiquitous to ignore, and it is also pretty easy to learn the basics
  * the "low level" thinking required to be successful with C will help you understand how computers work
    * combined with learning assembly language, C allows you to almost "see through to the assembly", due to how straightforwardly it can be compiled (although modern compilers will optimize the generated assembly in ways you could never do by hand, in principle this "transparent" aspect of C is the "big idea")

If you learn Lisp, ML, Smalltalk, Prolog, and C, you will be a much better programmer for it! Even if your day job is javascript and your side projects are in Rust, you will be glad you spent the time on these "big idea" languages, as your skills and newfound knowledge can be applied in any language. If learning a language _doesn't_ help you program in other languages, it probably wasn't worth learning.

So if you are a bootcamp grad, please don't just learn Python -> Javascript -> Ruby -> (next hot thing)

And if you are a university grad, please don't just learn C -> C++ -> Java -> Go -> (next hot thing)

### Stuff I didn't mention

There is probably a ton of stuff I left out. I will update the list as I think of more things. However, I want to call specific attention to the fact that I did not mention javascript frameworks like React, or some other hot new thing. Hot New Things are hard to evaluate in the present, but I think most of them turn out to be not that important in the grand scheme of things. I want this list to be as timeless as possible, so I'm specifically leaving out things that aren't likely to matter in 20 years.

### "But I just want to know how to get a job!"

Well then you need to find another list! But the short version of that would be something like this (at the time of this writing):

* learn hot new javascript framework
* learn hot new state-management system for javascript framework
* learn basic "solutions architecting" and how to use the cloud providers' platform (AWS, Google Cloud, Azure) to deploy applications
* learn basic data structures and algorithms and practice interview questions
  * I recommend working through the book "Cracking the Coding Interview"
* learn how to self-promote and network

Honestly that's pretty much it. It's not easy, but it is simple.

## Alumni Contributions

The following list was provided by asking Code Guild alumni for a list of things they wish they would have learned more about during bootcamp.

I will add to this as more alumni contribute.

* Classes, specifically when to use classes over plain functions 
  * I think the following is a good overview: [classes vs data structures + functions](https://blog.cleancoder.com/uncle-bob/2019/06/16/ObjectsAndDataStructures.html)
  * although if you want to learn "real OOP", you should probably focus less on "classes" as a language feature in Python (or whatever) and just dive into something like Smalltalk which helps force the proper paradigm on you
* Environment Variables
* How to *efficiently* package Python code as a single executable file
* Algorithms + Data Structures
  * I know it's on my list above, but I just wanted to point out that graduates are saying "I wish I would have spent more time on this"
    * this is largely due to the interview process in our industry, and the emphasis placed on data structures and algorithms. So as grads start looking for jobs, they realize they need to know this stuff!
