# deepComparison
Deep comparison in JS. Practice from the ebook EloquentJS. See README for more info.
From EloquentJS:
    
 "The == operator compares objects by identity. But sometimes you’d prefer to compare the values of their actual properties.

Write a function deepEqual that takes two values and returns true only if they are the same value or are objects with the same properties, where the values of the properties are equal when compared with a recursive call to deepEqual.

To find out whether values should be compared directly (use the === operator for that) or have their properties compared, you can use the typeof operator. If it produces "object" for both values, you should do a deep comparison. But you have to take one silly exception into account: because of a historical accident, typeof null also produces "object".

The Object.keys function will be useful when you need to go over the properties of objects to compare them."


**self planning**
//create fx with 2 args
//check to see if args are strictly equal first, in case numbers are given etc.
//check to make sure both args are objects
//make place to store the keys for the args if they are objects
//check to ensure objects are same length
//loop through all of keys for a keys storage spot
//if any b key does not coincide with corresp. a key, or if the keys arent equal, return false
//if you make it this far, return true bc they are deeply equal
