# Day 1
__02/22/21__

## What does inheritance accomplish in c#?

It defines a relationship between two classes. This relationship makes the child(derived) have all of the properties of the parent(base). This reduces repetition in code, if multiple classes have the same properties. But most importantly this makes code much more modular. Essentially the parent's and children become so intertwined that either can be called by referencing the other.

## How does member inheritance work in c#? Does a class inherit all members of the base class?

The derived class always has all of the members of the base class. They can then make alterations as they see fit using override. However that would alter what the derived class passes to it's children. The scope is something like a staircase. As you go up you step on more stairs, and the only way to not have stepped on a step is to unstep/ step down.

## How does accessibility affect inheritance?

Accessibility plays a pivotal role in inheritance as it strictly defines what a base is allowed to pass on. Private is strictly private. So only publicly scoped classes get passed on to the children. Which I've already experienced while using the MVC pattern, While I mostly make everything public at the moment, There has been a time or two where I maybe set a set on one of my models properties to private, just to experiment with scoping.

## Afternoon Challenge

https://github.com/Chase16Rogers/inherit-vacation