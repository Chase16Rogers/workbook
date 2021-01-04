# Day 3
__12/16/20__

## Handler

The two main operations of a handler are get and set. They are very simailar in that they watch for an event before running their code. Get runs whenever a value, whenever an item is accessed, where as set runs if a value/item is modified.

## Get undefined

By default the get operation is designed to return a value, not unlike a function, however, if a Get is run without a defined return it returns undefined, the fix is rather simple as you only need to return a value to prevent it from defaulting.

## Benefeting from ProxyObjects

By using proxy objects we open ourselves to a world of convenience, it allows us to set listeners, so instead of calling a draw function every single time an action takes place, we can call it whenever a change is made that needs to be drawn. I don't fully understand it, but it also seems it is possible to "lock" values to where they cannot be easily altered, which seems extremely useful, especially in the case of unique IDs, that need to stay exactly the same, no matter what.