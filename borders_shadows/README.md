Tutorial 17
========

Reference: [How To Style HTML Elements with Borders, Shadows, and Outlines in CSS](https://www.digitalocean.com/community/tutorials/how-to-style-html-elements-with-borders-shadows-and-outlines-in-css)

Borders are the outside of an element, and contain the padding and content. You can target all sort of border properties like width, color, style and even which specific border side (top, left, right, bottom). 

Border radius can take several different units like pixels, percentages, ems/rems. 

Text shadows can be used to create something like a glow effect, but they have to be used carefully because they can make the text harder to read if done too harshly. Subtle is key!

Box shadow order matters! The very first shadow you define will be layered on top of subsequent shadows you may define. You can use box shadows to create depth and highlights. 

Outline is the property that `:focus` states use to highlight an element. Outline is much like border, except that it DOESN'T affect the box model at all (which makes it perfect for accessibility needs), and you can't target specific sides with directions (top, bottom, left, right). Each browser's outline looks and interacts with the content slightly differently, so you might have to disable the outline first, before being able to modify it to your liking. 
