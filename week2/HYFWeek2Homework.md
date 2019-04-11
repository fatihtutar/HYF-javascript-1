# Done according to the instructions at [HYF-JS1-Week2_Homework](https://github.com/HackYourFuture/JavaScript1/blob/master/Week2/MAKEME.md)

## Task 1
* Instruction 
1. Write a `console.log` statement saying "Hello World!" for each language that you know.

* **Solution**
```js 
console.log("Merhaba, Dünya") // Turkish
console.log("Bonjour le monde!") // French
console.log("Hallo wereld!")// Dutch
```
Notes:  ```for more information see that``` [webpage](www.webucator.com/blog/2010/03/saying-hello-world-in-your-language-using-javascript/)

## Task 2
* **Instruction** 

> 2\. Consider the following code:

```js
console.log('I'm awesome');
```

Copy the code in your `.js` file and run it. You will see that you will get a SyntaxError. Find a solution for this error. Hint: read the error message carefully, it also gives an indication of where the problem is.


  * **Error message** 
```js 
Uncaught SyntaxError: missing ) after argument list
```
* **Solution**
```js
console.log('I\'m awesome'); 
```

## Task 3

* **_Instruction_**
> 3\. Declare a variable `x` and initialize it with an integer, using these exact steps:  
3\.1 First, _declare_ your variable `x` (do not initialize it yet).  
3\.2 Add a `console.log` statement that explains in words what _you think_ the value of `x` is, like in this example:
3\.3 Add a `console.log` statement that logs the value of `x`.  
3\.4 Now _initialize_ your variable `x` with an integer.  
3\.5 Next, add a `console.log` statement that explains what _you think_ the value of `x` is.  
3\.6 Add a `console.log` statement that logs the value of `x`.  
 
 * **Solution**
 ```js 
 let x;
 console.log("the value of the x: for now \"undefined\"");
 console.log(x); // undefined
 x = 10;
 console.log("the value of my x after assignment is: " + x); // the value of my x after assignment is: 10
 console.log(x); // 10
 
 ```
 [TOP](#Done)
 
 ## Task 4
* **_Instruction_**