# Day 3
__01/13/21__

## Sub-document

A sub-document is a document in another document. In practice it seems just to be a means by which you store additional complex information that directly pertains to a parent object. You set the value of a property in the parent to equal an array with a single object. The object could be bound and called or directly stated in the property. 

## To use a sub-document

A sub-document is useful in cases where the number of relationships is limited. In cases where the data is used more to define certain aspects of an object, rather than to store a potentially active/growing dataset. By keeping everything together, you eliminate potential comlpications and further itterations/network requests, but give up the modularity that you would otherwise have by using links.

## Diggy Diggy Document

Mongoose sub-documents behave in the exact same way as javascript objects. First, you have to find the object you want to alter. Then you would have to drill into the object to specify which property the subdocument belongs on. " object.property || object[index]", the value of the property that houses a sub-document is an array so you would use an array method to actually interract with the sub-document. " object.property.push(newSubDocument) ". This process seems rather simple, because it is what we already know from vanilla javascript.

## Afternoon Challenge
https://github.com/Chase16Rogers/planetary-relations