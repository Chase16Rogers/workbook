# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous is the traditional, one after the next. 
Asychronous takes a slight detour to allow a time consuming request to occur before synchronously running the rest of it's code.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is a means by which to check if some object has changed/ been acted on.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open / closed, open to be used, closed to be changed
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is a function that is called once an asynchronous promise is resolved. A higher order function is a function that operates on another function, this is relevant because often in the case of a callback, it will be called by whichever function established the asynchronous promise.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is a means by which to handle aaynchronous code in JS. It returns two values, either a resloved if the asyn is successful, or a rejected if it fails. You would capture an error by including a catch in the promise callback, this is what is triggered in the case of a rejected.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
get, put, post, delete
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Program Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The service
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
By bundling everything together you make it more readable, modular, and debuggable.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
A code in the 200's usually means it worked.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
This error means the server had some issue that prevented it from fulfilling the request.
```