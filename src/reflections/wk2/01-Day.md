# Day 1
__12/07/20__

## Scope

Scope is where a variable has jurisdiction. The scope of a variable is where it is defined and usable. Var is scoped either for the entire page, or for a single function. Whereas the let and const are determined by {}. They can be global, in the sense that they affect the entire page, but that is completely conditional on their location within {}.

## Hoisting

Is the means by which the code reads variables. It seems like the most convenient place to keep them is at the top of whatever container they happen to be needed in, but the code will at least, hoist, the declared variable to the top of the page so they can at least be declared, but they'd still need to be defined above and before use, even if the hoisted variable is defined below the relevant code.

## Let Var Const usage

At the moment I have absolutely no plan to ever use var, it is seemingly inferior to let in almost every single way. I plan on using let almost everytime I need to declare a variable. It's parameters of use seem very reliable, I'm less likely to make a mistake, like double declaring the same variable and messing everything up, and I've already grown accustomed to let over var from the intro to programming, and I don't have any reason to switch. Const seems to be more specific in its usefulness. I honestly have a hard time imagining a situation where I would need a variable that can't be re-defined, but at the same time I believe that it could be useful, I'm just not at the level yet.