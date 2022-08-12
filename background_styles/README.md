Tutorial 12 
==========

Reference: [How to Apply Background Styles to HTML ELements with CSS](https://www.digitalocean.com/community/tutorials/how-to-apply-background-styles-to-html-elements-with-css)


The default state of any background-image is to repeat from the top left corner, down towards the right and bottom (background-repeat: repeat). When you use a property like background-repeat, you can determine if you want the image to repeat horizontally (repeat-x), vertically (repeat-y) or not at all (no-repeat) as well. 

When using background-position, the property can accept 2 values. It can also accept numeric values (like pixels and percentages). Numerical values in this case are referring to the element (a percentage of the element's width, a certain amount of pixels from the element's "edge").  

To resize background-images, you can use cover (scale the image up or down to completely fill the container, but possibly cut portions of the image off), contain (scale the image up or down to completely fill the container, without losing portions of the image) or with numerical values accompanied by auto. Numerical values can be percentages (setting the width to the defined value, and keeping the height proportioned), and the value of "auto" maintains the aspect ratio.  

Background-attachment gives the effect that your element is sliding over, hovering above the image. Fixed adheres the image to the browser viewport, not the container element. It does not scroll with the page around it. 

When using the background shorthand property, typically values can come in any order. However, if you want to apply the background-size property, it must come AFTER the background-position, separated by the forward slash. /

Linear gradients can be smooth, transitioning from color to color, etc. They can also have "stops." You can add degrees (adding the direction of the gradient), percents (which can set hard lines between colors). You can also pair these with images to create complex backgrounds. Just remember that the browser will layer the background elements as they appear in the code (things that come first in the code, will be on the top-most "layer" of the background)
