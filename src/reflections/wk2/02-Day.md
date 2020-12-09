# Day 2
__12/08/20__

## What the function? 

  The first, and in my opinion most sensical/straightforward way to write a function is to declare it.
{ function name(parameter) }. The function keyword starts things off by declaring what comes next is in fact a function. Then name and parameter so you can use it later.

  The second way to make a function is to express it. Essentially you create a variable that is the value that will be returned by the function.
{ let name = function(parameter)} You can then use the variable in place of invoking the function? At least as far as retrieving the return.

  The last way to create a function is to use the Arrow. This is a rather "short-handed" way to invoke a function, but it allows for some serious shortcuts in calling objects or properties. Often used alongside higher order functions.

  As far as functionality, it is my understanding that only declared functions can be invoked as pure code snippets, while the other two are similar they are restricted by their required use of return. The only other major difference in functionality is that expressed functions aren't hoisted, so where they are placed could actually matter.

  ## Argumentative parameters

  Parameters are the means by which we allow our functions to recieve input externally. It lets us set what should come in and where it goes when it does. Arguments are the outside data coming in and being processed. I think of these a lot like modular variables. 
  { let parameter = argument } when the argument is withing the parameter field of a function. This is what allows a function to be reuasable, because it's not bogged down by specific variables, "any" value can enter and get processed.

  ## Higher functions

  Higher functions are functions that use another function. The only ones I currently am familiar with are the ones pre-built into JavaScript. Like .find() findIndex() and forEach(). I also have .map() and .filter() in my notes with some basic use cases, but I'm not as comfortable with those yet. For .find(), we create a function that targets and returns the specific object/property we want to find. 