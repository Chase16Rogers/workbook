# Day 2
__12/15/20__

## Why encapsulation

Encapsulation comes down to organization and efficiency. By grouping code into singular functionality, it prevents it from becoming too convulted to be read, and makes debugging easier. Additionally Encapsulation greatly increases the efficiency of programming by only running when it is called upon. Something asks it a question and it gives an answer. This makes not only the when and where a file should be ran easier, it allows the file to only run when it is specifically needed. 

## Underscore prefixes

The biggest problem with underscore prefixes was that they are much to flexible in use. There are no hard limits to stop a programmer from using a "private" method wherever it suits them. This is problematic because the private methods are by design capable of change without breaking the application. So if they are used in an area that doesn't allow for change problems can very easily occur.

## Creating privacy

In order to create a worthwhile private method closure needs to be taken into account. By limiting the scope of a function, it limits where it can be used. By making it inaccessible to other areas it becomes private in the sense that it is simply impossible to use elsewhere. This is achieved, so far, by putting the individual functions above the class on whichever page they are needed, this allows them to be used on that specific page, but will not be available in future instances of the class.