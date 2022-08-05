Tutorial 7
===========

Reference: [How to Use Color Values with CSS](https://www.digitalocean.com/community/tutorials/how-to-use-color-values-with-css)

Articles can in fact have a header (typically to hold the title or h1) and a footer (usually for citations if necessary).

The hr (horizontal rule) element might not look like much, but it can still accept styles like margin, height, width, and border properties. 

The "inherit" value only works with the color property like borders and font colors...think foreground colors. Inherit is invalid for things like background-color or box-shadow, so you have to use "currentColor," which acts in the same way.

Hex values for colors are most common. Typically, these values are 6 characters long, including a combination of a-f, and 0-9. 

I hope to never ever have to manually convert hex codes into rgb(). Multiply the first hex number by 16, then add the second value (that value is just multiplied by 1). That should be your first rgb() value. You can continue to convert the hex in the same way. 

HSL (hue, saturation, lightness) uses degrees of the color wheel to generate colors. HSL can aid is creating cohesive/complimentary color palettes. 
