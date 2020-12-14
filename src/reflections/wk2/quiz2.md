# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a snippet of code wrapped up in a binding, it allows for modular use of code by supplying argument to parameters for each instance.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility, Open closed, Liskov substitution, Interface segregation, Dependancy inversion
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
index 2, because an array starts at index 0, then you count left to right.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends = them
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if (true) {variable = 15}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
This is the afterthought that runs after all of the code in the {}, i++ would prevent this from becoming an infinite loop and increase i by one each itteration.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model, the html is first accessed and the foundation of the DOM.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
undefined, boolean, number, string, bigint, symbol, object, function, null
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
parameter is similar to a variable, you use it in the function. An argument is the value the parameters recieves and applies to the function.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitives are basic types of data, they have a single value, like a number or boolean. reference are comlex and hold many values, like an object (pojo) or array.
```