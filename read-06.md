# Node.js

## What is Node.js?
- >Node.js® is a JavaScript runtime built on Chrome’s V8 JavaScript engine.
- >Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library.
- **Note**
>The V8 engine is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, including Brave, Opera, and Vivaldi. It was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.

### Node.js in simple words is a program that is used for JavaScript execution on local machines (JavaScript runtime)

## Remarks
- *node -v* run this command to check node's version installed.
- Node.js is compatible with ES6 and beyond.
- *node index.js* run this command to execute a js code.

### Installing a Package Globally
 - *npm install -g jshint* 
 - *jshint index.js*

### Installing a Package Locally
- *npm init -y*
- *npm install lodash --save*

## Main use of Node.js
- >running JavaScript on the serve

## The Execution Model of Node.js
- Node.js is event-driven; such that everything happens in Node is in reaction to an event
- Node.js is single threaded

## Downside of Node.js - cause Node.js is single threaded (crashing the entire process)
- >Errors should be handled carefully; 
- >blocking I/O calls should be avoided,
- >CPU-intensive operations should be handed off to a worker thread

### Node.js is most suitable for builing apps that require real-time interaction

## Advantages of Node.js
- It allows the developer to code in one language, which increased the productivity.
- It speaks JSON
- Speed 
- Scalability