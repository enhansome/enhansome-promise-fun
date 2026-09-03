# Awesome promise-fun with stars

I intend to use this space to document my promise modules, useful promise patterns, and how to solve common problems. For now though, you can see all my promise modules below.

## Contents

* [Packages](#packages)
* [FAQ](#faq)

## Packages

*Not accepting additions, but happy to take requests.*

* **[p-queue](https://github.com/sindresorhus/p-queue) ⭐ 4,265 | 🐛 7 | 🌐 TypeScript | 📅 2026-07-22**: Promise queue with concurrency control
* **[p-limit](https://github.com/sindresorhus/p-limit) ⭐ 2,919 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-31**: Run multiple promise-returning & async functions with limited concurrency
* **[p-map](https://github.com/sindresorhus/p-map) ⭐ 1,510 | 🐛 12 | 🌐 JavaScript | 📅 2026-08-27**: Map over promises concurrently
* **[pify](https://github.com/sindresorhus/pify) ⭐ 1,503 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-23**: Promisify a callback-style function
* **[p-retry](https://github.com/sindresorhus/p-retry) ⭐ 1,030 | 🐛 1 | 🌐 JavaScript | 📅 2026-09-01**: Retry a promise-returning or async function
* **[p-progress](https://github.com/sindresorhus/p-progress) ⭐ 768 | 🐛 0 | 🌐 TypeScript | 📅 2023-11-04**: Create a promise that reports progress
* **[delay](https://github.com/sindresorhus/delay) ⭐ 624 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-31**: Delay a promise a specified amount of time
* **[p-throttle](https://github.com/sindresorhus/p-throttle) ⭐ 519 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-08**: Throttle promise-returning & async functions
* **[p-cancelable](https://github.com/sindresorhus/p-cancelable) ⭐ 451 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-09**: Create a promise that can be canceled
* **[p-event](https://github.com/sindresorhus/p-event) ⭐ 450 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-14**: Promisify an event by waiting for it to be emitted
* **[p-memoize](https://github.com/sindresorhus/p-memoize) ⭐ 449 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-26**: Memoize promise-returning & async functions
* **[p-all](https://github.com/sindresorhus/p-all) ⭐ 345 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-18**: Run promise-returning & async functions concurrently with optional limited concurrency
* **[make-synchronous](https://github.com/sindresorhus/make-synchronous) ⭐ 332 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-13**: Make an asynchronous function synchronous
* **[p-timeout](https://github.com/sindresorhus/p-timeout) ⭐ 305 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-07**: Timeout a promise after a specified amount of time
* **[p-lazy](https://github.com/sindresorhus/p-lazy) ⭐ 286 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-28**: Create a lazy promise that defers execution until `.then()` or `.catch()` is called
* **[p-debounce](https://github.com/sindresorhus/p-debounce) ⭐ 238 | 🐛 4 | 🌐 JavaScript | 📅 2025-11-11**: Debounce promise-returning & async functions
* **[p-props](https://github.com/sindresorhus/p-props) ⭐ 201 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-21**: Like `Promise.all()` but for `Map` and `Object`
* **[p-min-delay](https://github.com/sindresorhus/p-min-delay) ⭐ 177 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-25**: Delay a promise a minimum amount of time
* **[p-wait-for](https://github.com/sindresorhus/p-wait-for) ⭐ 169 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-21**: Wait for a condition to be true
* **[p-mutex](https://github.com/sindresorhus/p-mutex) ⭐ 142 | 🐛 1 | 🌐 JavaScript | 📅 2025-07-06**: Ensure that only one operation accesses a particular resource at a time
* **[p-state](https://github.com/sindresorhus/p-state) ⭐ 133 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-23**: Inspect the state of a promise
* **[p-pipe](https://github.com/sindresorhus/p-pipe) ⭐ 131 | 🐛 0 | 🌐 TypeScript | 📅 2021-04-08**: Compose promise-returning & async functions into a reusable pipeline
* **[yoctodelay](https://github.com/sindresorhus/yoctodelay) ⭐ 120 | 🐛 0 | 🌐 JavaScript | 📅 2021-10-01**: Delay a promise a specified amount of time
* **[p-settle](https://github.com/sindresorhus/p-settle) ⭐ 96 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-11**: Settle promises concurrently and get their fulfillment value or rejection reason with optional limited concurrency
* **[p-defer](https://github.com/sindresorhus/p-defer) ⭐ 87 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-08**: Create a deferred promise
* **[p-locate](https://github.com/sindresorhus/p-locate) ⭐ 82 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-03**: Get the first fulfilled promise that satisfies the provided testing function
* **[p-filter](https://github.com/sindresorhus/p-filter) ⭐ 82 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-22**: Filter promises concurrently
* **[p-waterfall](https://github.com/sindresorhus/p-waterfall) ⭐ 79 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-11**: Run promise-returning & async functions in series, each passing its result to the next
* **[p-time](https://github.com/sindresorhus/p-time) ⭐ 74 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-05**: Measure the time a promise takes to resolve
* **[p-series](https://github.com/sindresorhus/p-series) ⭐ 73 | 🐛 0 | 🌐 JavaScript | 📅 2021-08-12**: Run promise-returning & async functions in series
* **[p-reduce](https://github.com/sindresorhus/p-reduce) ⭐ 73 | 🐛 0 | 🌐 JavaScript | 📅 2023-02-11**: Reduce a list of values using promises into a promise for a value
* **[p-immediate](https://github.com/sindresorhus/p-immediate) ⭐ 71 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-09**: Returns a promise resolved in the next event loop - think `setImmediate()`
* **[p-try](https://github.com/sindresorhus/p-try) ⭐ 62 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-16**: `Promise.try()` ponyfill - Starts a promise chain
* **[p-whilst](https://github.com/sindresorhus/p-whilst) ⭐ 57 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-16**: While a condition returns true, calls a function repeatedly, and then resolves the promise
* **[p-any](https://github.com/sindresorhus/p-any) ⭐ 56 | 🐛 0 | 🌐 JavaScript | 📅 2022-07-09**: Wait for any promise to be fulfilled
* **[p-reflect](https://github.com/sindresorhus/p-reflect) ⭐ 56 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-11**: Make a promise always fulfill with its actual fulfillment value or rejection reason
* **[p-each-series](https://github.com/sindresorhus/p-each-series) ⭐ 52 | 🐛 0 | 🌐 JavaScript | 📅 2022-07-08**: Iterate over promises serially
* **[p-forever](https://github.com/sindresorhus/p-forever) ⭐ 52 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-16**: Run promise-returning & async functions repeatedly until you end it
* **[p-race](https://github.com/sindresorhus/p-race) ⭐ 52 | 🐛 0 | 🌐 JavaScript | 📅 2022-12-13**: A better `Promise.race()`
* **[p-map-series](https://github.com/sindresorhus/p-map-series) ⭐ 51 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-09**: Map over promises serially
* **[p-is-promise](https://github.com/sindresorhus/p-is-promise) ⭐ 45 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-16**: Check if something is a promise
* **[p-times](https://github.com/sindresorhus/p-times) ⭐ 42 | 🐛 1 | 🌐 JavaScript | 📅 2021-10-04**: Run promise-returning & async functions a specific number of times concurrently
* **[p-some](https://github.com/sindresorhus/p-some) ⭐ 39 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-11**: Wait for a specified number of promises to be fulfilled
* **[p-do-whilst](https://github.com/sindresorhus/p-do-whilst) ⭐ 38 | 🐛 0 | 🌐 JavaScript | 📅 2024-08-29**: Calls a function repeatedly while a condition returns true and then resolves the promise

### `.then`/`.catch`-based packages

*You should generally avoid using `.then` except in edge cases.*

* **[p-tap](https://github.com/sindresorhus/p-tap) ⭐ 134 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-08**: Tap into a promise chain without affecting its value or state
* **[p-if](https://github.com/sindresorhus/p-if) ⭐ 64 | 🐛 0 | 🌐 TypeScript | 📅 2021-04-09**: Conditional promise chains
* **[p-catch-if](https://github.com/sindresorhus/p-catch-if) ⭐ 40 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-09**: Conditional promise catch handler
* **[p-log](https://github.com/sindresorhus/p-log) ⭐ 30 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-09**: Log the value/error of a promise
* **[p-break](https://github.com/sindresorhus/p-break) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2021-04-07**: Break out of a promise chain

## FAQ

### How can I run 100 async/promise-returning functions with only 5 running at once?

This is a good use-case for [`p-map`](https://github.com/sindresorhus/p-map) ⭐ 1,510 | 🐛 12 | 🌐 JavaScript | 📅 2026-08-27. You might ask why you can't just specify an array of promises. Promises represent values of a computation and not the computation itself - they are eager. So by the time `p-map` starts reading the array, all the actions creating those promises have already started running. `p-map` works by executing a promise-returning function in a mapper function. This way the promises are created lazily and can be concurrency limited. Check out [`p-all`](https://github.com/sindresorhus/p-all) ⭐ 345 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-18 instead if you're using different functions to get each promise.

```js
import pMap from 'p-map';

const urls = [
	'https://sindresorhus.com',
	'https://avajs.dev',
	'https://github.com',
	…
];

console.log(urls.length);
//=> 100

const mapper = url => fetchStats(url); //=> Promise

const result = await pMap(urls, mapper, {concurrency: 5});

console.log(result);
//=> [{url: 'https://sindresorhus.com', stats: {…}}, …]
```

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-03._
