# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
you can bind a property using :prop, or you can simply {{variable}}
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Less network requests, which means it is able to render much faster, you can keep values in local variables on the application, and it is overall an easier process, at least using a good framework.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
On mounted runs a method once a component or page (.vue) is mounted to the page
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
V-model binds the element in the template to a variable in the script. Usually for pulling information out of an input field.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
These allow you to create events in your html, which will then run some JS method. @click, @submit.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if, v-else-if v-else
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
It provides a unique tag to the element being drawn, probably for allowing vue to keep track of each instance that is drawn.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
This allows you to implement unique elements from your component on a parent .vue, which allows for much more modularity.
```