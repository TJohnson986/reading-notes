## Class 03 Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents
1. React Lists and Keys
1. The Spread Operator
1. Passing Functions Between Components

#### React Lists and Keys
- What does .map() return? **
- If I want to loop through an array and display each value in JSX, how do I do that in React? *embedding the JS map() function into the HTML element using curly braces*
- Each list item needs a unique ____. *Key*
- What is the purpose of a key? *To give the elements a stable identity. Typically use and ID*

#### The Spread Operator
- What is the spread operator? *Expands an iterable object array into lists of arguments*
- List 4 things that the spread operator can do. *Copy an array, concatenate or combine arrays, match functions, adding item to a list*
- Give an example of using the spread operator to combine two arrays. *[...arr1,...arr2] returns all of the elements of both arrays*
- Give an example of using the spread operator to add a new item to an array. *If you have an existng array arr1, you can dclare a new variable and assign [item1, item2, ...arr1] and it will combine those new items into the new declared array*

#### Passing Functions Between Components
- In the video, what is the first step that the developer does to pass functions between components?
- In your own words, what does the increment function do?
- How can you pass a method from a parent component into a child component?
- How does the child component invoke a method that was passed to it from a parent component?