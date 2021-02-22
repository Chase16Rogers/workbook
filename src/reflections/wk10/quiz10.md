# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It groups the pages for an application and makes them available to the other pages similar to import.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Class has essentially taken over the javascript way of declaring methods, you still have to give them a type but it's functionally the same.
Struct seems similar to Classes but with more rules and less use. It seems to have a slimmer scope of types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The type it will return
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
The application from defaulting from an incomplete class definition
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Virtual allows it to inherit from the parent it is nested in.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only the code that is on the same page/in same class.
```