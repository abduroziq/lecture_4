# ARRAY  MAETHODS
* 1) ## pop() 
* 2) ## shift() 
* 3) ## push()
* 4) ## unshift()
* 5) ## concat()
* 6) ## slice()
* 7) ## forEach() 
* 8) ## map() 
* 9) ## find()
* 10) ## filter()
* 12) ## toReversed()
* 11) ## reduce()
* 13) ## toSorted()
* 14) ## join()
* 15) ##  includes()
* 16) ## indexOf()
* 17) ## splice()
* 18) ## toString()


# push()
>The push() method adds one or more elements to the end of an array and returns the
new length of the array.
The element(s) to add to the end of the array.
    

# pop()
>The pop() method removes the last element from an array and returns that element.
This method changes the length of the array. 

# unshift() 
>The unshift() method adds one or more elements to the beginning of an array and
returns the new length of the array.
unshift(element0, element1, /* … ,*/ elementN) 

# shift ()
> The pop() method removes the last element from an array and returns that element.
This method changes the length of the array


# tuString ()  
>The toString() method returns a string representing the specified array and its
elements.
A string representing the elements of the array.
Syntax: toString() 


# concat()
>The concat() method creates a new array by merging (concatenating) existing arrays:

>const myGirls = ["Cecilie", "Lone"];
const myBoys = ["Emil", "Tobias", "Linus"];

>const myChildren = myGirls.concat(myBoys);
The concat() method does not change the existing arrays. It always returns a new array.
>
>The concat() method can take any number of array arguments:

# slice()
>The splice() method adds new items to an array.
>
>The slice() method slices out a piece of an array.
>The splice() method can be used to add new items to an array:
>The first parameter (2) defines the position where new elements should be added (spliced in).
>
>
>The splice() method returns an array with the deleted items:
With clever parameter setting, you can use splice() to remove elements without leaving "holes" in the array:
>The first parameter (0) defines the position where new elements should be added (spliced in).
>
>The second parameter (1) defines how many elements should be removed.
>
>The rest of the parameters are omitted. No new elements will be added.
>
>The slice() method slices out a piece of an array into a new array.
>The slice() method creates a new array.
>
>The slice() method does not remove any elements from the source array.

# reduce()
> The reduce() method executes a user-supplied "reducer" callback function on each element
of the array, in order, passing in the return value from the calculation on the preceding
element. The final result of running the reducer across all elements of the array is a single
value.

# filter() 
>The filter() method creates a shallow copy of a portion of a given array, filtered down to
just the elements from the given array that pass the test implemented by the provided
function. 
# tostorted ()
> The toSorted() method of Array instances is the copying version of the sort() method.
It returns a new array with the elements sorted in ascending order.

# spread()
>The spread (...) syntax allows an iterable, such as an array or string, to be
expanded in places where zero or more arguments (for function calls) or
elements (for array literals) are expected. In an object literal, the spread syntax
enumerates the properties of an object and adds the key-value pairs to the object
being created.

# rest()
>he rest parameter syntax allows a function to accept an indefinite
number of arguments as an array.

# 