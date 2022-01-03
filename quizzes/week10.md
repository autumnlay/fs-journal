# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
  Providing a way to keep one set of names separate from another. Keeps the class names declared in one namespace does not conflict with the same class names declared in another.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
  Structs are value types, classes are reference types
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
  a public void one
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
 that this method is going to return a string
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
  It hides internal details in the class
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
  It allows the method Start() to be modified.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
  public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
  It can only be accessed with-in the same class.
```