# Javascript

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
    numArr
    (4) [1, 2, 3, 4]
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

### Mixins
Mixins are these pieces of code that you can mix with other objects to extend their functionality.

Basically, you can borrow features from different mixins to compose the kind of object you desire.

Mixinns can be achieved by,

1. Inhertance
2. Composition
3. 
