# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
-var, let, and const although var is no longer used.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
-A subprogram designed for a particular task.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
-Single Responsibility, open/closed, liskov substitution, interface segregation, and dependency inversion principle. These principles are designed to make object oriented desings more manageable and easier to understand.
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
-index 2. Because arrays start at zero, which would be apple, and count up from zero. I beleive you can also console.log(fruit) and it will list the fruit with their index number.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
-By using the push method. you.push(...them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
-if (5 < 6){
  result = true
} else result is false
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
-Increment exspression. i++ to increase i by 1 every iteration.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
-Document Object Model. The HTML file.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
-Undefined, null, string, number, symbol, boolean, bigint, data properties, and accessor properties.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
-Parameters are names we give functions in the () of a function. Arguments are values that the function is passsed when the function is called.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
-A Pprimitive data type is data that is not an object and always has a value. Where as reference data types refer to objects and their value is defined by the programmer not by javascript.
```