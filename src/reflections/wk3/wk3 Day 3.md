# Read Advancing with JS > An Intro to Javascript Proxy Objects and answer the following questions

Today we continued to learn MVC design and classes, along with object destructuring and appstate subscribing. afternoon work: https://github.com/Jaron-Warren/gregslist-mvc

## What are the two common operations that we will set in the handler?

get and set

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?

change the proxy for get and it's two parameters - the object and the property being accessed. (traps) handler is object with set of traps (custom override)

## What are some of the benefits of the proxy object that we are using in our structure for applications?

Making custom rules for access or setting information on specific onjects. Can protect specific properties, enforce data type and structure on objects.