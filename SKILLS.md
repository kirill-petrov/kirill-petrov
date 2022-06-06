# Personal Roadmap of Software Engineering Skills

⬜ Optional, 🟦 Required for All, 🟨 Required for JS, 🟩 Learned, 🟥 Declined

## Fundamental concepts

### Syntax

<code>🟦 value</code>
<code>🟦 identifier</code>  
<code>🟩 variable </code>  
<code>🟩 constant</code>  
<code>🟦 scalar</code>  
<code>🟩 literal</code>  
<code>🟩 expression</code>  
<code>🟦 heap</code>  
<code>🟩 type</code>  
<code>🟩 primitive types</code>  
<code>🟦 reference</code>  
<code>🟦 flag</code>  
<code>🟩 lexical scope</code>  
<code>🟦 code block</code>  
<code>🟩 Object</code>  
<code>🟩 this</code>  
<code>🟩 arrow function</code>  
<code>🟨 generator</code>  
<code>🟩 async function</code>  
<code>🟩 call, bind, apply</code>
<code>🟩 Array</code>  
<code>🟨 instanceof</code>  
<code>🟩 ...spread</code>  
<code>🟩 ...rest</code>  
<code>🟩 typeof</code>

## Fundamental concepts

| Syntax | Statements            | Functions             | Data structures      | Process & style       |
| ------ | --------------------- | --------------------- | -------------------- | --------------------- |
|        | 🟩 if                 | 🟩 recursion          | 🟩 array             | 🟦 refactoring        |
|        | 🟦 loops              | 🟩 function           | 🟦 instance          | 🟦 code review        |
|        | 🟦 assignment         | 🟩 return             | 🟩 object            | 🟦 antipatterns       |
|        | 🟨 prototype          | 🟦 signature          | 🟦 collection        | 🟦 paradigm           |
|        | 🟦 class              | 🟦 argument           | 🟩 hash table        | 🟦 algorithm          |
|        | 🟩 while              | 🟦 parameter          | 🟦 linked list       | 🟦 magic numbers      |
|        | 🟩 do..while          | 🟩 pure function      | 🟩 queue             | 🟦 hardcode           |
|        | 🟩 for                | 🟦 lambda             | 🟩 stack             | 🟦 complexity         |
|        | 🟩 for..in            | 🟦 side effects       | 🟦 deque             | 🟦 decomposition      |
|        | 🟩 for..of            | 🟩 closure            | 🟦 serialization     | ⬜️ spaghetti         |
|        | 🟨 for await          | 🟦 partial            | 🟦 mixin, extend     | ⬜️ silver bullet     |
|        | 🟩 throw              | ⬜️ curry             | 🟨 iterator          | ⬜️ not invented here |
|        | 🟩 try..catch         | 🟩 chaining           | 🟨 typed arrays      | 🟦 dead code          |
|        | 🟦 equality operators | 🟦 higher order       | 🟩 Map               | 🟦 unreachable code   |
|        | 🟦 logical operators  | 🟩 callback           | 🟩 Set               | 🟦 duplicate code     |
|        | 🟦 bitwise operators  | 🟦 listener           | ⬜️ weak collections | 🟦 exception          |
|        | 🟩 break, continue    | ⬜️ pipe              | ⬜️ Proxy            | 🟦 return early       |
|        | 🟩 switch             | ⬜️ memoize           | ⬜️ Symbol           | 🟩 linter             |
|        | 🟩 new Error          | 🟦 factory            | 🟩 string parsing    | 🟩 prettier           |
|        |                       | 🟦 pool               | 🟩 timers            | 🟦 unittest           |
|        |                       | 🟦 wrapper            | 🟨 EventEmitter      | 🟩 git                |
|        |                       | 🟨 default parameters | 🟩 RegExp            | 🟩 github             |
|        |                       |                       | 🟩 global            | 🟩 node.js            |
|        |                       |                       | 🟩 undefined         | 🟩 npm                |
|        |                       |                       | 🟩 null              |                       |

## Multi-paradigm programming

| Theory                         | OOP basics            | Abstractions         | Patterns     |
| ------------------------------ | --------------------- | -------------------- | ------------ |
| 🟦 Procedural programming      | 🟦 constructor        | ⬜ struct, record    | 🟦 Singleton |
| 🟦 Imperative programming      | 🟦 new                | ⬜ Mutable state     |              |
| 🟦 Structured programming      | 🟦 Static method      | ⬜ Immutable state   |              |
| 🟦 Non-structured programming  | 🟦 Method             | ⬜ Enum              |              |
| 🟦 Functional programming      | 🟦 Async method       | 🟦 Linked list       |              |
| 🟦 Prototype-based programming | 🟦 Getters, Setters   | 🟦 Doubly list       |              |
| 🟦 Object-oriented programming | 🟦 Public fields      | 🟦 Unrolled list     |              |
| ⬜ Object-based programming    | 🟦 Private fields     | 🟦 Circular list     |              |
| 🟦 Generic programming         | 🟦 Field declarations | 🟦 Trees             |              |
| 🟦 Concurrent computing        | 🟦 Inheritance        | 🟦 Graphs            |              |
| 🟦 Asyncronous programming     | 🟦 Parent class       | 🟦 Functor           |              |
| 🟦 Parallel programming        | 🟦 Polymorphism       | 🟦 Functional object |              |
| 🟦 Reactive programming        | 🟦 Abstract class     | ⬜ Monad             |              |
| ⬜ FRP (Functional-reactive)   | 🟦 Interface          | 🟦 Generator         |              |
| 🟦 Automata-based programming  | 🟦 Encapsulation      | 🟦 Iterator          |              |
| 🟦 Domain-specific languages   | ⬜ Hidden class       | 🟦 Async Iterator    |              |
| 🟦 Multi-paradigm programming  | ⬜ Object form        |                      |              |
| ⬜ Metaprogramming             | 🟦 instance           |                      |              |
| ⬜ Actor model                 | ⬜ Introspection      |                      |              |
|                                | ⬜ Reflection         |                      |              |

## Asynchronous programming

| Async contracts        | JavaScript & Node.js specific  | Theory              | Techniques               |
| ---------------------- | ------------------------------ | ------------------- | ------------------------ |
| 🟦 Callback-last       | 🟩 Timers                      | 🟩 Event Loop       | ⬜ async.js library      |
| 🟦 Error-first         | 🟦 setImmediate                | 🟦 Async error      | ⬜ Async composition     |
| 🟦 Promise             | 🟦 nextTick                    | 🟩 try..catch       | ⬜ Rx.js                 |
| 🟩 Async function      | ⬜ AbortController             | 🟦 Non-blocking     | 🟦 Sequential async      |
| 🟩 await               | 🟦 Promise unhandled rejection | 🟦 Async I/O        | 🟦 Parallel async        |
| 🟦 Generator           | 🟦 Promise double resolve      | 🟦 Pattern Reactor  | 🟦 Promise.all           |
| 🟦 Async Generator     | 🟦 child_process               | ⬜ CAS operations   | 🟦 Promise.allSettled    |
| 🟦 Async Iterator      | 🟦 worker_threads              | ⬜ epoll            | 🟦 Promise.race          |
| 🟦 Thenable            | 🟦 Atomics                     | ⬜ kqueue           | 🟦 Promise.any           |
| 🟦 EventEmitter        | 🟦 Blockeing operations        | ⬜ Completion ports | ⬜ Web Locks API         |
| ⬜ Cancelable callback | 🟦 Non-blocking loop for Array | ⬜ Event ports      | ⬜ Async Pool            |
| ⬜ Cancelable Promise  | ⬜ High resolution clock       | 🟦 libuv            | ⬜ Thread Pool           |
| 🟦 Asynchronous Queue  | 🟩 Callback hell               | 🟦 Race conditions  | 🟦 callbackify           |
| ⬜ Future              | 🟦 Promise hell                | 🟦 Dead locks       | 🟦 promisify             |
| ⬜ Deferred            |                                | 🟦 Live locks       | ⬜ IPC                   |
| 🟦 Observer            |                                | ⬜ Actor Model      | ⬜ Channel API           |
| ⬜ Async Collector     |                                |                     | ⬜ Revealing Constructor |
| ⬜ Coroutine           |                                |                     |                          |
| ⬜ Goroutine           |                                |                     |                          |

## Node.js and backend

| Internals            | Theory                       | Network           | Technique        | Problems             |
| -------------------- | ---------------------------- | ----------------- | ---------------- | -------------------- |
| 🟦 Nonblocking I/O   | 🟦 I/O bound tasks           | 🟩 HTTP(S)        | 🟦 Logging       | 🟦 Memory leaks      |
| 🟩 Event Loop        | 🟦 CPU bound tasks           | 🟦 TCP/SSL        | 🟦 Testing       | 🟦 Resource leaks    |
| 🟩 commonjs          | 🟦 Memory bound tasks        | 🟦 UDP            | ⬜ CI/CD         | 🟦 Blocking code     |
| 🟩 ECMA modules      | 🟦 Multilayer approach       | 🟦 TLS            | 🟦 Readable      | 🟦 Data race         |
| 🟦 Network API       | 🟦 Separation of concerns    | 🟦 Websocket      | 🟦 Writable      | 🟦 Graceful Shutdown |
| ⬜ Addons            | 🟦 Inversion of control      | ⬜ SSE            | 🟦 Transform     | 🟦 Dependencies      |
| ⬜ N-API             | 🟦 Dependency injection      | ⬜ HTTP/3 (QUIC)  | ⬜ back pressure |                      |
| ⬜ Webassembly       | 🟦 GRASP for JS and Node.js  | ⬜ Long polling   | 🟦 Buffer        |                      |
| 🟩 npm               | 🟦 SOLID for JS and Node.js  | 🟩 REST           | 🟦 Console       |                      |
| 🟩 node_modules      | 🟦 GoF for JS and Node.js    | 🟦 RPC            | 🟦 Inspector     |                      |
| 🟩 package.json      | ⬜ Distributed systems       | 🟩 Routing        | 🟦 Reliability   |                      |
| 🟦 vm isolation      | ⬜ Highload applications     | 🟦 IP sticky      | 🟦 Quality       |                      |
| 🟦 command line args | 🟦 DDD                       | 🟦 DoS            | 🟦 Availability  |                      |
| ⬜ Node.js CLI       | 🟦 Clean architecture        | 🟦 DDoS           | 🟦 Flexibility   |                      |
| 🟦 Streams           | 🟦 Domain in the middle      | 🟦 XSS            |                  |                      |
| 🟦 Clustering        | 🟦 Message Queue             | 🟦 Path traversal |                  |                      |
| ⬜ Load balancing    | 🟦 Transport-agnostic server | 🟦 CSRF           |                  |                      |
| ⬜ Serverless clouds | 🟦 Framework-agnostic app    | 🟦 DNS            |                  |                      |
| ⬜ FaaS clouds       | ⬜ Interactive applications  | 🟩 Fetch          |                  |                      |
| 🟦 Debugging node.js | ⬜ Real-time applications    | 🟦 zlib           |                  |                      |
| 🟦 crypto            | 🟦 CQS and CQRS              |                   |                  |                      |
| ⬜ SharedArrayBuffer | 🟦 Event Sourcing            |                   |                  |                      |
| 🟦 child_process     | 🟦 Shared memory             |                   |                  |                      |
| 🟦 worker_threads    |                              |                   |                  |                      |
