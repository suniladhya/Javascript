# Javascript
[1](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/src/questions/coding-questions.md)
Javascript is more of a functional programming rather than object oriented.

[Excellent blogging on JS](https://medium.com/javascript-scene/)

* [Functional programming](https://codewords.recurse.com/issues/one/an-introduction-to-functional-programming)
[2](https://www.recurse.com/blog) is more into solving the expression rather than sticking with objects.
* Do Every thing with Fuction( input-> output)

### Non Functional:(Imperative Style)
declare name
greeting = "Hi "+ name
Console.log(greeting);

### Funtional:(in terms of function)
function greet(name){
greeting = "Hi "+ name
Console.log(greeting);
}

### Pure and Impure:
Function that return only value instead of doing sth else is Pure function.

function greet(name){
greeting = "Hi "+ name
return greeting;
}

### Higher Order Funtion
Functin (within function)^n

### Don't Iterate
Instead of For use

_map filter reduce_

![](https://api.ning.com/files/-3i3rVffQH2bautHoYhtuyn-BhEFBMR3TNXJzACS9ATLysgH7VID6G3-DRqv65rcjsIwZ7riHJZ9rtS9XGWzIc326dpaeNvF/bor55.PNG)

### Avoid Mutabillity
numArr = [1, 2, 3, 4]
numArr[0] = 7;

### No Mutation
    numArr.Map(
    function (x){
        if(x==1){
            return 7;
        }else
            return x
    });

### Persistent data structures for efficient immutability
* mori
* immutable js
Structural sharing

## Basic function:
concat

copyWithin
    //places in next indexes & modifies the current array
    fruits =                  ["Banana", "Orange", "Apple", "Mango"]
    fruits.copyWithin(2, 0) //["Banana", "Orange", "Banana", "Orange"]

filter
    // Returns an array satisfying the function
    Note: filter() does not execute the function for array elements without values.
    Note: filter() does not change the original array.

Map
    //

Find, FindIndex
    //Finds value, index
    numArr = [1, 2, 3, 4]
    numArr.findIndex(x=>x>2)
    2
    numArr.find(x=>x>2)
    3
    Note: find() does not execute the function for empty arrays.
    Note: find() does not change the original array.

reduce <> reduceRight

Push <> unshift

pop <> shift

Remove duplicates from a array

Reverse a string

[1](https://stackoverflow.com/questions/9229645/remove-duplicate-values-from-js-array)
[2](http://techsith.com)
[3 Closures](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36)
[4 Tips tricks(http://javascriptissexy.com/12-simple-yet-powerful-javascript-tips/)

## Task Runner
* [Gulp](https://coder-coder.com/gulp-tutorial-beginners/)

### Mixins
Mixins are these pieces of code that you can mix with other objects to extend their functionality.

Basically, you can borrow features from different mixins to compose the kind of object you desire.

Mixinns can be achieved by,

1. Inhertance
2. Composition
3. 
