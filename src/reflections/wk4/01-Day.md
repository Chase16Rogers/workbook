# Day 1
__01/04/21__

## Highway to callback

The primary sign of callback hell is a ton of closing brackets and parentheses lined up one after another. The code also takes on a pyramid like shape.

{
  {
    {
      {
        Nice cozy nest
      }
    }
  }
}

This is caused by writing code in a visually logical manner, the code runs top to bottom, so stacking actions after eachother makes sense. "Run this line after that line." But things start to stack up really quickly so without taking steps to keep your code nice and tidy, you'll probably find yourself in a world of hell, callback hell, that is.

## Asynchronous

Asynchronous simply/ litterally means out of sync, it is a process that is able to perform outside of the top to bottom single thread of javascript. In practice it tells the code to run once a certain requirement has been met, usually a lengthy operation, like communicating with a server. This allows the end user to continue to interact with the website when it would have been otherwise disposed. The callback still exists in this situation, just not in it's hellish state. The function that runs once the async is finished is now the callback, nut now it's probably in a much neater package as it is it's own function.

## Rules of three

Rule number 1: Keep the code shallow - I'm pretty sure this implies the superficial sort of shallow, you should be able to take one glance and be able to make a judgement, binding names should be obvious, keep convolusion/mystery to minimum.

Rule number 2: I find this to heavily emphasize the single responsibility principle of SOLID, keep your functions as short as possible by limiting how much each is allowed to handle.

Rule number 3: Handle every single error - This comes down to having a fallback if anything fails, if the network doesn't return what you asked for, as a developer I need to know when it happened and preferably why it happened, so by building in errors to handle when the software errors, I'll be able to perform more capably.

## Afternoon Challenge

https://chase16rogers.github.io/pop-quiz/