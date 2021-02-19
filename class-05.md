## Class 05 Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents
1. Images
1. Color
1. Text

#### Images
Images can be used to set the tone for a site in less time than reading a description. Images should be relevant, convey info, be instantly recongnizable, and fit the color scheme. 

It is a good practice to create a folder for all of the images that the site uses. This folder may contain subfolders to help with organization.

To add an image to a page, use an `<img>` element. It must contain the path to the image, and may also include alt text and titles to for assistive viewing. The height and width can also be determined within this img element.

There are three rules for creating images: 
1. Save images in the right format (i.e. jpeg, .gif, .png)
1. Save images in the right size. The image itself should be the same size as it will appear on the site, or it may look distorted.
1. Measure images in pixels

#### Color
There are three different ways to specfy colors in CSS:
1. RGB - Determines color by amount of red, green, and blue is used (i.e. rgb(100,100,90))
1. Hex - uses a 6-digit code starting with a # that represent amount of red, green, and blue. 
1. Pre-defined - 147 predefined colors in CSS 

Additionally, there are three other values that determine the look of the color
1. Hue
1. Saturation (amount of gray in color)
1. Brightness (amount of black in color. Full brightness is no black)

`color` - determines color of text
`background-color` - determines color of the box. By default if not specified, the background is transparent

Contrast is an important consideration or readability. If the background and foreground colors are too similar, it is difficult to differentiate the two and read the text. Too much contrast can also be difficult to read.

Opacity was introduced in CSS3 and is a value between 0.0 and 1.0, where 0.5 would be 50% opacity.

CSS3 also introduced HSL colors, which stands for Hue, Saturation, and Lightness. HSLA includes an opacity value.

#### Text
There are two groups to control the appearance of text - those that directly affect the font and it's appearance including the typeface, and those that would have the same effect on text no matter what font. 

Typefaces: 
- Serif fonts have extra details on the ends of the letters, known as serifs. Considered easier to read in print
- Sans-Serif fonts have straight ends and are a clearer design. Considered easier to read on screens.
- Monospace font letters each have a fixed width, commonly used for code because it aligns nicely.

Typefaces allow for options beyond the basics, but are subject to copyright and licenses.

`font-family` property specifies the typface that should be used for any text inside the element. Site visitors will need to have that font actually installed in order to use. This may require several options separated by commas to ensure the text can be displayed. 

`font-size` property specifies the size of the font. This can be done by pixels, and em's. 

The default size of text in a browser is 16 pixels. Percentage or ems adjustments are determined from there.

`font-weight` is used to style text as normal or bold

`font-style` is used to style text as italics

`text-transition` can be used to change the case of text either to all lowercase or uppercase.

`text-decoration` can be used to underline and strikethrough

`line-height`,`letter-spacing`, and `word-spacing` are all used to control the spacing around the words and letters to help with style and readability.

`text-align` allows you to control the alignment of the text.

`text-indent` allows the first line of text to be indented. Amount of indent can be specified. 

Styling links - alows you to change how links appear both as not yet visited, and visited.

There are other interaction related appearance changes, such as hover, active, and focus. 


#### JPG vs. PNG vs. GIF
**JPG** used for natural scenes or photographs where variation in colors and intensity is smooth. 

**PNG** used for images that need transparency, contain text and has sharp edges like logos.

**GIF** image format that contain animations. 

Never knew this!

Two types of compression - lossless and lossy. 
  - Lossless compression allows for an original image to be reconstructed after it's been compressed. 
  - Lossy is irreversible, once an image is compressed it cannot be brought back to original form. 

JPEG's are lossy
PNG's are lossless
GIF's are lossless

Transparency - Only PNG's support this. GIFs do, but not well.

