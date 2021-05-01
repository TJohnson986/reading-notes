## Class 04 Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents
1. HTML Links
1. CSS Layouts
1. JS Functions, Methods, Objects


#### HTML Links
Links can be used to: 
- Link from one website to another
- Link from one page to another of the same site
- Link from one part of a web page to another of the same page
- Open a new browser window 
- Start an email program to address an email to someone

Links are created using `<a></a>` tags, and anything in between those tags are a clickable link called the link text. The href attribute is where the link goes.

URL stands for Uniform Resource Locator - each page has it's own unique URL, starting with the site's domain name, then the path to the specific page. 

Absolute URLs link to a different website and include the full URL. 

Relative URLs are links within the same site which are just the local path. 

When building larger websites, its a good idea to organize pages into folders or directories. 

Email links use a mailto: attribute to open an email program and address an email to the specified user. 

To open a link in a new window, use target=_blank" after the URL.

To link to a different part of the same page, you can utilize HTML id attribute and HTML elements. 


#### CSS Layouts
**CSS treats each HTML element as if it's in it's own box. This box will either be block-level or inline.**

Block level start on a new line and act as the main building blocks.

Inline flow between surrounding text. 

These elements can sit inside each other and be considered containng or parent elements.

**CSS has positioning schemes -** 
- Normal flow: block-level elements are always a new line, never next to each other
- Relative Positioning: Moves an element from the normal flow, shifting it a certain direction without affecting other nearby elements. 
- Absolute positioning: Positions element in relation to it's containing element. 


#### JS Functions, Methods, Objects
Functions and methods - Functions consist of a series of statements that perform a specific task. Methods are same as functions except that they are created inside an object. 

Objects - made up of properties and methods

A function is declared by giving it a name, then writing the statements of the function within sets of curly braces. 

A function is called by using the function name followed by parenthesis. Parameters can be entered into the function by entering them into the parenthesis. 