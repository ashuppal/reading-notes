class 03:

This topic matters because learning methods and implementing them correctly in the code are cruicial for rendering the expected results.
**React Docs - lists and keys**

What does .map() return?
.map() returns a new array populated with the results of calling a provided function on every element in the calling array.

If I want to loop through an array and display each value in JSX, how do I do that in React?
Use the map() method to iterate over the array. The function you pass to map() gets called for each element in the array. 
The method returns a new array with the results of the passed in function.

Each list item needs a unique _key___.

What is the purpose of a key?
A “key” is a special string attribute you need to include when creating lists of elements.
Keys help React identify which items have changed, are added, or are removed. 

**The Spread Operator**

What is the spread operator?
The JavaScript spread operator ( ... ) allows us to quickly copy all or part of an existing array or object into another array or object.

List 4 things that the spread operator can do.
1. Copying an array
2. Concatenating or combining arrays
3. Using Math functions
4. Using an array as arguments.

Give an example of using the spread operator to combine two arrays. www.tutorialspoint.com
To combine two or more arrays, you can either use the functional method []. concat(arr1, arr2) or the spread operator [...arr1,...arr2]. 
The merging outcome is kept in a new array, making these methods immutable.

Give an example of using the spread operator to add a new item to an array. *stackoverflow
If you want to use the spread operator to add items to the beginning of an array, just use the spread operator after the new values. For example:
let a = [1, 2, 3, 4, 5];
let b = [0, ...a];

Give an example of using the spread operator to combine two objects into one.*w3schools.com
The spread syntax is useful for combining the properties and methods on objects into a new object:
const obj1 = { a: 1, b: 2, c: 3 };
const obj2 = { d: 4, e: 5, f: 6 };
const obj3 = {...obj1, ...obj2}; 

## Things I want to know more about
Using different methods to extract data from objects.
