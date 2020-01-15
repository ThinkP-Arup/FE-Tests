## JavaScript Test

#### 1.
Write a function `isThreeDigit` that checks if a number is greater than or equal to 100 and less than 1000. `isThreeDigit(500)` should return `true`. The call `isThreeDigit(50)` should return `false`.

#### 2.
we have an array as follows:
```
let nums = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
```
By using two `array.filter()` method create an array of even numbers.

#### 3.

How can the operating system of the client machine be detected? Chose your Answers:

    * It is not possible using JavaScript.
    * Using the navigator object
    * Using the window object
    * Using the document object
    * None of these.
#### 4.

What will the code below output to the console and why?

```
var myObject = {
    foo: "bar",
    func: function() {
        var self = this;
        console.log("outer func:  this.foo = " + this.foo);
        console.log("outer func:  self.foo = " + self.foo);
        (function() {
            console.log("inner func:  this.foo = " + this.foo);
            console.log("inner func:  self.foo = " + self.foo);
        }());
    }
};
myObject.func();
```

#### 5.
Consider the two functions below. Will they both return the same thing? Why or why not?

```
function one()
{
  return {
      bar: "hello"
  };
}

function two()
{
  return
  {
      bar: "hello"
  };
}
```

#### 6.
What will the code below output to the console and why ? 
```
console.log(1 +  +"2" + "2");
```

#### 7.
What is the output out of the following code? Explain your answer.

```
var a={},
    b={key:'b'},
    c={key:'c'};

a[b]=123;
a[c]=456;

console.log(a[b]);
```

#### 8.
What will the following code output to the console and why:

```
var hero = {
    _name: 'John Doe',
    getSecretIdentity: function (){
        return this._name;
    }
};

var stoleSecretIdentity = hero.getSecretIdentity;

console.log(stoleSecretIdentity());
console.log(hero.getSecretIdentity());
```

#### 9.
The output of the following code snippet will be `undefined` and not 20 or 21 ! Why ?

```
var x = 21;
var girl = function () {
    console.log(x);
    var x = 20;
};
girl ();
```

#### 10.
Consider the following 

```
console.log(1 < 2 < 3);     // returns true
console.log(3 > 2 > 1);     // returns false !!
```
Why does the second code prints `false` ?

#### 11.
The `pop()` method of the array does which of the following task ? 

>A. decrements the total length by 1

>B. increments the total length by 1

>C. prints the first element but no effect on the length

>D. None of the above 

#### 12.
What will happen if a `return` statement does not have an associated expression?

>A. It returns the value 0

>B. It will throw an exception

>C. It returns the undefined value

>D. None of the mentioned 

#### 13.
True False Rapid Fire: - whether the following statements are `true` or `false` and why ?

```
Question: Is 'false' is false?

Question: Is ' ' is false?

Question: What about {}?

Question: Tell me about []?

```

#### 14.
Consider the following code snippet
```
function f(o) 
{
     if (o === undefined) debugger;
}
```
What could be the task of the statement `debugger`?

#### 15.
Consider the following syntax
```
book[datatype] = assignment_value;
```
In the above syntax, the `datatype` within the square brackets must be

>A. An integer

>B. A String

>C. An object

>D. None of the mentioned 

#### 16.
How could you write a method on instance of a date which will give you next day? Write a code snippet.

#### 17.
How does JavaScript store dates in a `date object`?

>A. The number of milliseconds since January 1st, 1970

>B. The number of days since January 1st, 1900

>C. The number of seconds since Netscape's public stock offering.

>D. None of the above

#### 18.
Which of the following is not considered a JavaScript operator?

>A. `new`

>B. `this`

>C. `delete`

>D. `typeof`

#### 19.
Which of the following is the structure of an if statement?

>A. if (conditional expression is true)  then execute this code end if

>B. if (conditional expression is true)  execute this code end if

>C. if (conditional expression is true)   {then execute this code>->}

>D. if (conditional expression is true) then {execute this code}

#### 20.
What will you see in the console for the following example? Why ?

```
var a = 1; 
function b() { 
    a = 10; 
    return; 
    function a() {} 
} 
//
b(); 
//
console.log(a);    
```