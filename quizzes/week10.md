# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
-It is used to set a scope within your project.

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
-class is a reference type and struct is a value type meaning that structs have a single value and do not change.

```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
-void

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
-public

```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
-That the data value will be text

```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
-It prevents anykind of return until it is inherited by another class

```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
-Virtual allows for the abstract to be overridden and for another class to inherit it.

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
-private, public, protected, internal.

```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
-When set to private it means that those classes or methods cannot be accessed externally.

```