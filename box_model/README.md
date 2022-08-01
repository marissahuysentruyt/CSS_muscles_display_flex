Tutuorial #4
------------

Reference: [How to Work with the Box Model in CSS](https://www.digitalocean.com/community/tutorials/how-to-work-with-the-box-model-in-css)

Border, padding, margin, width & height are all part of what we call the Box Model. This is basically a way of thinking of your content and containers on a web page. It shows the computed width of an element (final size, with padding, width, height, margins, borders included). This relates to the box-sizing property, which has a default value of content-box. Content-box to me is sort of manual. It requires the developer to remember all of the values of the borders, padding, width, etc. The border-box value allows some of those final values to calculated automatically, based on explicit requirements you might have in your stylesheet.

The border, padding and margin properties all have loads of shorthands. There is a cycle of how to target all the sides: it's always the top, then the right, bottom and finally left. Using borders can help you visualize your content's containers as you code. I use temporary borders all the time. 

Padding is the space between the content and its border. Margin is the space outside the border, before one element hits another. There is a built-in margin feature that allows for margin collapsing, if margins of 2 elements overlap. Margin can also accept negative and "auto" values, which padding cannot. Auto margins can be used for centering content that has a defined width (as long as it's smaller than the 100% of the available space). 

Fixed dimensions = pixels
Fluid dimensions = percentages (or ems/rems I believe)
Universal selector = *

Width & height enforce dimensions on the content. They aren't shorthand and can have questionable effects at times. Both of these properties can vary so much, so sometimes it's better (like with height) to not specify a value so that the browser can analyze the content first before making any decisions. 