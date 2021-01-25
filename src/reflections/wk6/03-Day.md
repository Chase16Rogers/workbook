# Day 3
__01/20/21__

## The circle of lifecycle hooks

Lifecycle hooks essentially keep track of the state of the application. They can be used to time methods, like only run this when a particular page is mpunted to the DOM. Do this before you draw that. This makes dynamic changes to the DOM incredibly simple and streamlines the whole drawing process.

## Lifecyle use hooks

Lifecycle hooks are used to dynamically time the functionality of an application. 99 times out of 100 you only want certain information to appear on the DOM at particular points in time. Maybe it's just when the page is loaded, or some navigation takes place, but this makes drawing only on such instances possible. They also make rather convenient network request triggers. Because you only want to make a request when it is absolutely necessary, being able to keep track of where the user is can be indespensible in controlling when to make requests to which endpoints in the api.

## Mounting hooks

Mounting hooks are the best hooks. They essentially keep track of when a particular component is "mounted" visible on the DOM. This is where the api and page drawing I mentioned before comes into play. By keeping track of when a particular element is meant to be mounted to the DOM you can run whatever code is needed to successfully display/run the element being mounted, and inversely you can blow away the information that could affect another part of the application when dis-mounting a particular element. Allowing for much more complicated and modular code.

## Afternoon Challenge

https://github.com/Chase16Rogers/vue-megslist