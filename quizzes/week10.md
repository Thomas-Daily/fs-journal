# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
- to declare a scope that contains a set of related objects
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
- Class combines the fields and methods into a single unit, a struct is a collection of variables of different data types under a single unit.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```

- Void

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
- Starts a process by specifying the name of an application and a set of command line arguments.

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
- That the data type will be a string of letters and numbers.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
- Hide the internal details and show only the functionality
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
- It overides the base class member in its derived class based on the requirement.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
- Private, public, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
- Only things directly in where the class or method was called.

```