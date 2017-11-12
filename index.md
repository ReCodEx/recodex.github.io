---
layout: default
---

### Introduction

ReCodEx is a system for testing people's programming skills. Our primary target 
are technical universities. These often have programming courses that require 
the students to write programs that have to be checked by teachers. By checking 
the basic properties (the source code compiles and the program works correctly 
for a defined set of inputs) automatically, ReCodEx lets teachers focus on more 
important parts of the course, while also providing students with continuous 
feedback.

The system is highly customizable - it allows testing simple programs in C, but 
also in languages such as Java, Python, Prolog or Haskell. Even complicated 
scenarios such as testing parsers based on flex, yacc and bison or running 
highly parallel programs on a NUMA machine are feasible.

We use modern technologies everywhere in our infrastructure - source code 
submitted by students is run in a sandbox based on Linux kernel namespaces and 
CGroups to ensure safety, the backend is based on microservices that communicate 
over the network so that the system can be scaled up and our frontend is a 
React.js application that communicates with the backend through a REST API.

### Where To Go Now?

If you are interested in the project, you can get more information from our 
[wiki](https://github.com/ReCodEx/wiki/wiki). You can also read the source code 
of all ReCodEx components on [GitHub](https://github.com/ReCodEx). 

### Student Project Topics

ReCodEx started as a student project, and therefore, it is open to being 
expanded upon by other such projects. There are many possible topics, some of 
which we list here. If you are interested in any of them, feel free to contact 
us.

- **CLI frontend** - We would love to see a command line application for 
  bootstrapping solutions for assignments and submitting them. Git integration 
  would also be welcome.
- **Full-fledged Android app** - We already implemented a basic Android 
  application that could be improved upon in many ways.
- **Windows sandbox** - A prototype sandbox for .NET assemblies, WrapSharp, was 
  already implemented. It could benefit from a thorough security audit before 
  being integrated with the rest of our backend. Also, the possibility of 
  implementing a general-purpose sandbox for Windows should be researched.
- **Web frontend finalization** - The web frontend is a large React/Redux 
  application that could be improved in numerous ways.
