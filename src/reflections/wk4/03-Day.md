# Day 3
__01/06/21__

## Async Await

Like any other higher order function, async and await take a process that is excessively common, and kind of clumpy to write, and make it neat and easy to use. It essentially contains a complex promise bound to a single key word, which can then be used in code. This eliminiates the repetitive syntax used for chaining, making the code not only easier to write, but to read.

## Await after Async

In order to use async in a function, the initial declaration must in some way be prefaced by the Async key word, then the await is used in the function before whatever asynchronous action is called. It is also good practice to call the function from within a try/catch statement, this allows for more accurate errors and easier debugging, but to my understanding the async await will continue to function without some method for handling a rejected output, assuming the output is resolved.

## Good things come to those who Await

The benefits of async and await are in their ease of use. You have less code to write, which means you're less likely to make a typo. They are easier to read, because they only point out where the asynchronous code is, but everything else can continue to "run" and look like it's synchronous. Because the syntax is simple it's easier to debug, and avoids some of the shortfalls that a vanilla promise would have. (debugger breaking)

## Afternoon Challenge

https://chase16rogers.github.io/pokedex/