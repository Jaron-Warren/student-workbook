# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var
let
const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a block of predefined code that can be ran over and over again with placeholder values called "parameters"
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
a set of guidelines for software developers on how to make clean and understandable classes
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2, arrays start at 0
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
array.prototype.push.apply(you, them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if (1 > 2) {
  congradulations! you can't do math!
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
incrementer, it runs at the end of each loop. i++
```

```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
document object model, index.html file
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
6 primitives: undefined, boolean, number, string, bigint, symbol; 2 structurals: object, function; and structural root: null.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
parameters are defined with the function, arguments are passed into the function where the parameters are.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
primitive values are stored in memory on the stack and reference values (JS objects) are stored in the heap. When you assign variables to an existing object it will reference the same value in the heap and so the two values are linked to the same pointer in memory.
```