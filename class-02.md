## Class 02 Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents
1. HTML Text
1. Intro to CSS
1. Basic Javascript Instructions

#### HTML Text
There are two different kinds of text markup in HTML: Structural and Semantic. 

Examples of structural markup are heading tags, such as <\h1>, <\h2>, etc. Other examples are <\p> for paragraph, <\b> for bold, and <\i> for italic. These will each have a direct impact on the layout and look of text on the page. 

Examples of semantic markup include <\em> for emphasis, and <\blockquote>. Using each of these will alter the look of text, however that is not their intended use. Semantic markup is rather used for screen readers or search engines for extra information beyond plain text. Additional examples include <\abbr> for abbreviations and <\cite> to include reference information. 


#### Intro to CSS
CSS creates rules for how groups of elements should appear, rather than individually stylng each element. For example changing the background color for all paragraphs in the body in one rule. 

The page is made up of different boxes, and CSS can be used to apply specific styling to each of these boxes. 

CSS rules use HTML elements, and how they should be displayed. There are two parts to a CSS rule, a selector and a declaration. 

The selector is going to be the HTML element, and the declaration is how the element should be styled. The declaration is two parts: a property and a value separated by a colon. 

It's usually best practice to include CSS rules in a separate document that is linked to the HTML page, rather than use inline styling. But if there is minimal styling to specific elements, inline styling can work. 

CSS style rules follow an order. If selectors are identical, the last one will apply. If a selector is more specific than another, it will apply. Parent/child inheritance will also apply to CSS rules. 


#### Basic Javascript Instructions
A script is a series of instructions that a computer can follow in order, one by one. Each instruction is called a statement, and each statement should end with a semicolon. 

Javascript is case sensitive!

Each statement should start on a new line, and end with a semicolon. The semicolon tells the interpreter when that step is over and to move on. Statements can be organized in code blocks, which are surrounded by curly braces. 

Comments help explain what your code does and makes it easier to read and understand, but has no effect on the live page and is not visible. 

A variable is used to store bits of information in a script. The "var" keyword is used to create or declare a variable. You must declare a variable with a name, then assign it a value using the assignment operator "="

A few data types in JavaScript are:
- numeric: strictly numbers
- strings: letters and other characters enclosed in single quotes
- boolean: either true or false

In order to use a character like a single quote inside a string, you must **escape** the character by using a \ backslash. 

There are six rules for naming variables: 
1. The name must begin with a letter, dollar sign, or an underscore. Never a number. 
1. The name can contain letters, dollar sign, or underscore, but not a dash or period. 
1. Cannot use JavaScript keywords
1. Variables are case sensitive.
1. Use a name that describes what the variable stores.
1. If the variable name uses more than one word, use camelCase

An array is a special kind of variable that stores a list of values. You should consider using an array when working with a list or set of values that are related to each other. Values in arrays are accessed as if they are in a numbered list, starting with zero.

#### Basic Loops and Decisions in JavaScript
Decision making is broken down to either true or false. A condition is defined and evaluated, and depending on whether the reponse to that condition is true or false the path is determined. There are comparision operators that will compare two values, 