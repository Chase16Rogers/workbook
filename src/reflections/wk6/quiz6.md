# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
vue create project-name
```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
in the README.md it describes each of the commands needed to get it up and running
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for="item in state.collection" :key="item.id"
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
<template /> <script /> <style />
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Liskov Substitution Principle
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
<router-link :to="{name:}">
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The AppState is globally scoped where the state is only available in that component.
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Communicating with servers
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
root? The index.html forms the absolute basis of our application. The App.vue file is where we connect all of our pages before they are injected into the index. And the index.js/router.js is what "holds" all of our routes. I do not believe there is an actual element tag <root>
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
Style, scoped
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
const AppState/state = reactive({})
```