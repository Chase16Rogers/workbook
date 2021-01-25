# Day 2
__01/19/21__

## Props?

Props are essentially variables, variables that get passed along in the vue framework. Specifically they get passed from a parent, typically a page to a child, which is always a component.

## Use props

They're not only used in a carrot head routine, they are used to pass information from one page to a component. This doesn't sound like much as most of the data can be found in the appstate, however this allows for extremely simple instancing, say you're using a for in loop to itterate over an array in your appstate, instead of trying to keep track of each instance by modeling with child templates, you pass along the entire object you're looking at when drawing, making it so that you don't have to go to any lengths whatsoever to keep track of what you need to draw

## Getting props

On the component you essentially need to declare that you are expecting props of a certain name. In a props property you specify that name and its data type, then you can simply reference the specific prop in the template, or pass the props property to setup() to access that information, which means you don't have to manually itterate over an array to find the exact object you want to access, because it is simply passed by the prop.

## Afternoon Challenge

https://github.com/Chase16Rogers/vue-nasa