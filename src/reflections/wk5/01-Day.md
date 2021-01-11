# Day 1
__01/11/21__

## String query

A query string is simply the means by which an application is able to pass arguments to a server during a request. These arguments are useful in specifying exactly what information, how much, or which type is wanted from that server.

## Parameter Format

A query string begins with a " ? ", this initiates it, says that whatever follows are the parameters. Then a property with a value is given " ?count=20 " this is the parameter, it is my understanding that the server checks the property, then uses whatever value it was given in its processes. In order to add parameters the " & " is used. " ?property=value&diffProperty=diffValue " this can be repeated, not unlike the parameter/argument field in a function.

## My uneducated thoughts on the usefulness of query parameters, a dissertation.

Much like a function, being able to pass arguments into a server will give me essentially free reign over how the application is allowed to interact with the server. I can control the information recieved to be exactly what is needed for each instance. I can specify smaller values to reduce network load, potentially speeding up my application. I could even ask the server to do some simple calculations, which might break the RESTful server rules, but could ultimately be useful in reducing what code needs to be in my application.

## Afternoon Challenge

https://github.com/Chase16Rogers/burger-shack