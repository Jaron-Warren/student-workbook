# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
a namespace is how programs are "organized" and which programs share with each other or the path taken to "using" for another program.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
unlike classes, structs are value types and do not require heap allocation. A variable of a struct type directly contains the data of the struct, whereas a variable of a class type contains a reference to the data, the latter known as an object.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Transient class
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
the return value type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
abstract means this class can't be instantiated on it's own, must be used by another class by inheritance.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual keyword modifies the method and allows for it to be overridden in it's derived class.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
can be accessed only by code in the same class.
```