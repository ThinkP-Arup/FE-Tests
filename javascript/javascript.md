## JavaScript Test
#### Time : 
1. 
Write a function `isThreeDigit` that checks if a number is greater than or equal to 100 and less than 1000. `isThreeDigit(500)` should return `true`. The call `isThreeDigit(50)` should return `false`.

2.
we have an array as follows:
```
let nums = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
```
By using two `array.filter()` method create an array of even numbers.

3.

How can the operating system of the client machine be detected? Chose your Answers:

    * It is not possible using JavaScript.
    * Using the navigator object
    * Using the window object
    * Using the document object
    * None of these.
4.

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

5.
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

6.
What will the code below output to the console and why ? 
```
console.log(1 +  +"2" + "2");
```

7.
What is the output out of the following code? Explain your answer.

```
var a={},
    b={key:'b'},
    c={key:'c'};

a[b]=123;
a[c]=456;

console.log(a[b]);
```

8.
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

9.
The output of the following code snippet will be `undefined` and not 20 or 21 ! Why ?

```
var x = 21;
var girl = function () {
    console.log(x);
    var x = 20;
};
girl ();
```

10.
Consider the following 

```
console.log(1 < 2 < 3);     // returns true
console.log(3 > 2 > 1);     // returns false !!
```
Why does the second code prints `false` ?