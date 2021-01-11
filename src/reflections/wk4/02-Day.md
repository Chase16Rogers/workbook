# Day 2
__01/05/21__

## Solid, liquid, and gas

The three states of a promise are:
Pending - The promise is called and the asynchronous code is initialized, the request is sent to the server and now we wait.
Resolved - The asynchronous code finishes and we have what we asked for and everything is good in the world.
Rejected - The asynchronous code finished but we didn't get what we wanted, usually resulting in an error message.

## The heavenly chain

Chaining is the promise solution to callback hell. This allows for entire functions to be run, open and closed in a tight line in response to an asychronous request, essentially if a promise comes back resolved it gives it a tidy list of functions to run in sequence as a result. The syntax of this code happens to be more pleasing, more ordered than nesting the functions, so it is superior. 

## Then catch

Then is used if a promise is resolved, usually running whatever code is necessary to process whatever data was sent/recieved.
Catch is used if a promise is rejected, usually throwing up an error to start the debugging process.

kind of like the case default used in a switch, it will try to run the case, but use the default if things don't work out.

## Afternoon Challenge

https://chase16rogers.github.io/gregs-list/