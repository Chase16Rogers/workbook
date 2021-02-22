# Day 1
__02/15/21__

## What are the three categories of data types? How are they different?

Value Type: Directly stores a value, is the most primitive straightforward data type.
Reference Type: Doesn't directly hold data, but points to a value type, we use this for basic bindings like variables.
Pointer Type: Most complex, can point to multiple value types.

## What are the Value-type data types? What differences do you notice from JavaScript?

Bool, byte, char, decimal, double, enum, float, int, long, sbyte, short, struct, uint, ulong, ushort.
There are a LOT more data types than we get in JavaScript, and they are much more specific about the exact amount of memory they are allowed to use, you're supposed to declare the smallest necessary data type.

## In your own words how do Reference types get stored in memory? How does this differ from Value types?

Refernce types get stored with a little address book. This book tells them exactly where the data they need to know is, so when they're asked what they know they can show us what we're asking for. They're kind of like a taxi driver, I guess... If reference types are taxi cabs, value types are houses. They are the kind of end route, they don't change much and they stay in the same place.

## Afternoon Challenge
https://github.com/Chase16Rogers/cs-rock-paper-scissors