# Day 2
__02/16/21__

## What is a list in c#

My understanding is that a list is simply a strictly typed JavaScript array, minus the cool stuff we can do with arrays. They do give us list methods, which seem both more stifling since I don't understand them yet, and liberating in how robust they are, some of them seem almost like magic. Lists are c# way of grouping similar data.

## What List methods seem like you might use often? Why?

.Add, .Remove, .contains, .find, .findAll, .FindIndex, .insert, .removeAt, .sort

I like these ones because they are similar to what I've used in javascript and have a better concept of their usefulness and applications. Perusing the list of methods I can definitely see how some of them are useful, and I might have to update my list of methods I like going forward. But right now my JavaScript brain is just trying to relate what it already knows.

## How would you retrieve an item from a list? What method could you use?

Any of the find methods would do the trick. Primarily I will use the ListName.find(l => l.id == id), not only because this is exactly the same as JavaScript, but because it is extremely useful. Not to mention I know "exactly" how this works. This also skips some of the steps other methods like findIndex would introduce to this process.

## Afternoon Challenge

https://github.com/Chase16Rogers/greg-control