## Class 01 Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents
1. HTML Structure
1. Extra Markup
1. ABC of Programming

#### HTML Structure
HTML is the structure of the webpage, and uses elements to describe the structure of pages. For each element, there is an opening and a closing tag.

Tags are a character within a set of angle brackets. If it's an open tag, it will simply have a left angle bracket, then the element, then a right angle bracket. If it's a closing bracket it is the same with an addtion for a forward slash after the left angle bracket. 

Attributes provide more information about the contents of an element and appear in the open tag. They're made up of a name, and a value, separated by an equals sign. 

There are basic elements that make up an HTML webpage structure, such as:

- `<html>` - required first and last tags
- `<body>` - entire visible webpage
- `<head>` - contains info about the page, but nothing visble on the page
- `<title>` - The text that shows on the browser tab

#### Extra Markup
There have been newer versions of HTML released over the years, adding additional features over previous versions and removing old unnecessary code. HTML5 is the latest version and curently being used. A DOCTYPE declaration can be used at the very beginning of HTML code to tell the browser which version of HTML the page will use. 

There are additional markup elements that can be used in HTML code that make it easier for human readability. Using comments through HTML code is a good way of describing what is happening at that section, leaving notes for yourself or someone else to read and understand later, etc. 

Using an ID attribute provides better flexibility and options in things like CSS, since it allows for specific elements to have separate styling than others of the same nature. The id attribute is known as a global attribute since it can be used on any element. 

Every HTML element can also use a class attribute. This allows for a set of elements to be treated differently than other elements rather than individual elements. 

Another example of extended markup are block elements and inline elements:
- Block elements - appear to start a new line in the browser window
  - `<h1>, <p>, <ul>, <li>`
- Inline elements - continue in the same line as neighboring elements
  - `<a>, <b>, <em>, <img>`

#### ABC of Programming