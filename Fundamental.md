# <a id="TOC">Fundamental concepts</a>

<!-- ## <a id="TOC">Table of contents</a> -->

## Syntax

<code>value</code>
<code>[identifer](#identifer)</code>
<code>variable</code>
<code>constant</code>
<code>scalar</code>
<code>literal</code>
<code>expression</code>
<code>heap</code>
<code>type</code>
<code>primitive types</code>
<code>reference</code>
<code>flag</code>
<code>lexical scope</code>
<code>code block</code>
<code>Object</code>
<code>this</code>
<code>arrow function</code>
<code>generator</code>
<code>async function</code>
<code>call, bind, apply</code>
<code>Array</code>
<code>instanceof</code>
<code>...spread</code>
<code>...rest</code>
<code>typeof</code>

## Statements

<code>if</code>
<code>[loops](#loops)</code>
<code>assignment</code>
<code>prototype</code>
<code>class</code>
<code>while</code>
<code>do..while</code>
<code>[for](#for)</code>
<code>for..in</code>
<code>for..of</code>
<code>for await</code>
<code>throw</code>
<code>try..catch</code>
<code>equality operators</code>
<code>logical operators</code>
<code>bitwise operators</code>
<code>break, continue</code>
<code>switch</code>
<code>new Error</code>

## Functions

<code>recursion</code>
<code>function</code>
<code>return</code>
<code>signature</code>
<code>argument</code>
<code>parameter</code>
<code>pure function</code>
<code>lambda</code>
<code>side effects</code>
<code>closure</code>
<code>partial</code>
<code>curry</code>
<code>chaining</code>
<code>higher order</code>
<code>callback</code>
<code>listener</code>
<code>pipe</code>
<code>memoize</code>
<code>factory</code>
<code>pool</code>
<code>wrapper</code>
<code>default parameters</code>

## Data structures

<code>array</code>
<code>instance</code>
<code>object</code>
<code>collection</code>
<code>hash table</code>
<code>linked list</code>
<code>queue</code>
<code>stack</code>
<code>deque</code>
<code>serialization</code>
<code>mixin, extend</code>
<code>iterator</code>
<code>typed arrays</code>
<code>Map</code>
<code>Set</code>
<code>weak collections</code>
<code>Proxy</code>
<code>Symbol</code>
<code>string parsing</code>
<code>timers</code>
<code>EventEmitter</code>
<code>RegExp</code>
<code>global</code>
<code>undefined</code>
<code>null</code>

## Process & style

<code>refactoring</code>
<code>code review</code>
<code>antipatterns</code>
<code>paradigm</code>
<code>algorithm</code>
<code>magic numbers</code>
<code>hardcode</code>
<code>complexity</code>
<code>decomposition</code>
<code>spaghetti</code>
<code>silver bullet</code>
<code>not invented her</code>
<code>dead code</code>
<code>unreachable code</code>
<code>duplicate code</code>
<code>exception</code>
<code>return early</code>
<code>linter</code>
<code>prettier</code>
<code>unittest</code>
<code>git</code>
<code>github</code>
<code>node.js</code>
<code>npm</code>


<!--  ## <a id="33"></a> Методы `call`, `apply`, `bind`  -->



### <a id="identifer">identifers</a>

```js
'use strict';

const INTERVAL = 500;
let counter = 0;
const MAX_VALUE = 10;
let timer = null;

const event = () => {
  if (counter === MAX_VALUE) {
    console.log('The end');
    clearInterval(timer);
    return;
  }
  console.dir({ counter, date: new Date() });
  counter++;
};

console.log('Begin');
timer = setInterval(event, INTERVAL);
```

<details><summary>output</summary>
  
```zsh
Begin
{ counter: 0, date: 2022-06-12T06:43:32.798Z }
{ counter: 1, date: 2022-06-12T06:43:33.299Z }
{ counter: 2, date: 2022-06-12T06:43:33.800Z }
{ counter: 3, date: 2022-06-12T06:43:34.301Z }
{ counter: 4, date: 2022-06-12T06:43:34.802Z }
{ counter: 5, date: 2022-06-12T06:43:35.304Z }
{ counter: 6, date: 2022-06-12T06:43:35.805Z }
{ counter: 7, date: 2022-06-12T06:43:36.306Z }
{ counter: 8, date: 2022-06-12T06:43:36.807Z }
{ counter: 9, date: 2022-06-12T06:43:37.308Z }
The end
```
</details>

[`↑ scroll up`](#TOC)

### <a id="loops">loops</a>

В JS имеется 5 операторов цикла: while, do/while, <code>[for](#for)</code>, for/of (и его разновидность for/await), for/in.

[`↑ scroll up`](#TOC)

### <a id="for">for</a>

```js
'use strict';

const MAX_VALUE = 10;

console.log('Begin');
for (let i = 0, j = 9; i < MAX_VALUE; i++, j--) {
  console.dir({ i, j, date: new Date() });
}
console.log('The end');
```

```zsh
Begin
{ i: 0, j: 9, date: 2022-06-12T07:05:42.170Z }
{ i: 1, j: 8, date: 2022-06-12T07:05:42.171Z }
{ i: 2, j: 7, date: 2022-06-12T07:05:42.172Z }
{ i: 3, j: 6, date: 2022-06-12T07:05:42.172Z }
{ i: 4, j: 5, date: 2022-06-12T07:05:42.172Z }
{ i: 5, j: 4, date: 2022-06-12T07:05:42.172Z }
{ i: 6, j: 3, date: 2022-06-12T07:05:42.172Z }
{ i: 7, j: 2, date: 2022-06-12T07:05:42.172Z }
{ i: 8, j: 1, date: 2022-06-12T07:05:42.172Z }
{ i: 9, j: 0, date: 2022-06-12T07:05:42.172Z }
The end
```

[`↑ scroll up`](#TOC)
