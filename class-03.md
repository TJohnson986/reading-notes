## Class 01 Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents
1. HTML Lists
1. Boxes
1. Switch Statements
1. Loops


#### HTML Lists
There are three differnet kinds of HTML lists: Ordered lists, unordered lists, and definition lists. Ordered lists are numbered, unordered lists are bulletized, and definition lists are made up of terms along with their definitions.

Ordered lists are created with the `<ol>` element, and each item placed within the `<ol>` tags are placed within open and close `<li>` tags. 

Unordered lists are created with the `<ul>` element and each item placed wihin the `<ul>` tags are placed within open and closing `<li>` tags.

Definition lists are created with the `<dl>` tags, and items within use the `<dt>` tag to contain the term being defined, and the `<dd>` tags to contain the definition. 


#### Boxes
CSS allows for several properties that affect the appearance of the boxes that make up a webpage. These include the dimentions of the boxes, borders around them, margins and padding outside or within them, and even show/hide boxes. 

By default a box is sized just big enough to hold it's contents, but this can be changed by using width and height properties. The most popular methods use pixes, percentages, or ems. Pixels are exact, percentages are relative to the size of the browser window, and ems are based on the size of the text within the box. 

Every box has a border, whether its visible or set to 0 pixels. It separates the edge of one box from another. Borders have width, color, and style properties. additional CSS 3 border options include border images, box shadows, rounded corners, and elliptical shapes.

Margins sit outside the border which can create a gap between the borders of ajacent boxes. 

Padding is the space between the border and the content inside the box. Padding can be helpful to increase readability.

The 'display' property allows you to make an inline element into a block element and vice versa. This can create options to allow a block level element to flow like an inline element but also keep the features of a block element.

#### Switch Statement
A switch statement starts with a varible that is the switch value. You can define different cases each with a different result so that if the switch value becomes one of the case values, that case's code will run. This is more efficient than if/else statements since all if/else statements are checked even if a match has been found.

Javascript is known to use weak typing because the data type for a value can change, whereas other languages require the variable data type to be specifed. 

Type coercion is the conversion of data to try to "make sense" of the operation rather than reporting an error. It can lead to unexpected values though, so it's best practice to use strict.


#### Loops
Loops check a condition, and if it's true the code will run. It will continue to be checked and run if true, only stopping when it returns false.

Different loop types are for loops, while loops, and do while loops. A for loop uses a counter as a condition, and instructs the code to run a specified number of times.