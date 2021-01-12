## Class 02 Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents
1. HTML Text
1. Intro to CSS

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
