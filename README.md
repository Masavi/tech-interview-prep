# TI Prep Breakout

In this breakout session, you'll have an opportunity to review the content you've learned already in preparation for your upcoming Tech Interviews. For this breakout, be ready to share any questions that you have relating to Tech Interviews.

### Tools and Technologies
---
- Git & Github -> Version Control Systems (VCS) (priority)

Important aspects about VCS:
1. COMMITS (Time travel): (A.K.A. Moving between commits!!!)
2. HISTORY (Log and messages in commits): Allow us to keep track of our history and understand changes over time.
3. BRANCHES (Parallel time lines): They allow to work in a cleaner way, and not get in the way of other developers.

GIT: the actual program running in my computer that allows me to keep track of changes in a given directory/folder.
REPOSITORY: folder/directory that is being managed by git.
GITHUB: a website that centralizes everything to be access

- Node.js and NPM (priority)

#### What is JavaScript?
Why is this a basic language? Everything on the web has 3 technologies:
- HTML
- CSS
- JS

"JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. Read more about JavaScript."

Note: JavaScript can be executed in different ways. Each browser has its OWN ENGINE to run JavaScript.
The most popular engine is V8 Engine that the Google Chrome team developed.

#### What is Node.js?
Environment where we can code with JavaScript. It's JavaScript running OUTSIDE OF THE BROWSER!.
We take the engine from the browser, install it in our computers and the we are able to run JS in our computer.
TRIVIA: Node.js is built on top of V8 Engine.

#### What is NPM?
Node Package Manager and it allows us to install other people's programs and use them as our own. We call these 
programas PACKAGES.

### JS Basic Topics
---
- Data Types
  - Number
  - Boolean
  - String
  - Truthy/Falsy
  - Objects (unorganized list of key:value pairs)
    - Arrays (an organized list of data) (index, ordered 0,1,2,3,4...)
- Variables (space in memory that stores a value)
  - Types
    - var (Variable. Global, not that used)
    - let (Variable. Can also be used as globals, altough they are more used inside of a scope)
    - const (Constant. Doesn't allow you to change the value stored in memory)
- If statements (change the flow of the code execution, depending on true/false expression A.K.A. conditions)
- For loops (change the flow of the code execution, it allows us to repeat something and access an index over time)
- Functions (blocks of reusable code)
  - Scope (things that are accessible depending on the context/place they are found)
    - global
    - local
  - Normal Functions 
      const variable = function () {}
      function notAnonymous() {}
      define their own context for "this"
  - Arrow Functions
      const variable = () => {}
      DON'T define their own context for "this", they inherit it.

    THE MOST IMPORTANTE DIFFERENCE BETWEEN THESE TWO IS "this".
- Debugging
  Process of finding where things are going wrong. It's a lot about using console.log and following the data and the execution of the program.

### Testing
---
  - Types of testing (unit and integration)
  - Why to test
    - Test runners (mocha)
    - Assertion libraries (chai)

### Object Oriented Programming (OOP)
---
Programming paradigm where we have this "boilerplates" which are classes, and we have the abilty
to create copies from classes that are instances.

It allows you to encapsulate properties and behaviours inside of a block of code that you can reuse, this is the CLASS.

It's all about classes and objects. Objects are instances of classes, and classes define how objects are gonna be created.
JavaScript is not by definition an OOP language, but we can implement OOP features thanks to ECMAScript.

Classes in JS are "syntantyc sugar". We are always doing thins on top of Prototypes!!!.

### JS Advanced Topics
---
- Higher Order Functions
  Functions that receive other functions as arguments. We call this functions inside as callbacks.
- Callbacks
  Functions that are passed into HIGHER ORDER FUNCTIONS as arguments.
- Closures (PRIORITY)
- ECMAScript (6 and Beyond) ECMAScript 6
- Recursion (PRIORITY)

  GNU (popular because of linux and free software!)
  G: GNU:
    - G: GNU...
      - G: GNU
      - N: is Not
      - U: Unix...
    - N: is Not
    - U: Unix

- Asynchronous JavaScript
  - Synchronous code (runs sequentially)
  - Async code (runs separate from the main thread (or the main sequence))
    - Functions/Methods provided by external forces (browser, or other APIs)
  - Promises
    It's a way of envolving things that may be resolved or rejected. That way you can handle the resolution or rejection separately.

### TCP/IP Protol Family
---
The protocol family that makes the internet possible. Thanks to this we have the "Client-Server Architecture"
- Networking (the way that computers and devices interact with each other)
- TCP/IP (the most important protocol family tranfer-control-protocol/internet-protocol)
  - It helped as a foundatioun for the Hyper-Text Transfer Protocol

### HTTP
---
Allows us to to talk between clients and servers between HTTP Requests (GET, POST, PUT, PATCH, DELETE, etc...)
This is the way that we can share data across different computers.

- JSON: we usually exchange data between clients and servers and JSON format.
- APIs: Application Programming Interfaces -> waiters and waitresses of the internet!

### Web Servers
---
Are computers that enable you to talk to them through HTTP requests!
Every Web Server is an API, but NOT ALL APIs are web servers!

- Express.js
  We can build our own web servers and we can serve web pages or simply data.

