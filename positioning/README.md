Tutorial 16
========

Reference: [How To Create Layout Features with Position and Z-Index in CSS](https://www.digitalocean.com/community/tutorials/how-to-create-layout-features-with-position-and-z-index-in-css)

Using the `position` and `z-index` properties are great ways to control the placement and layout/overlay of elements in comparison to one another. By default, elements are `position: static`. 

`Position: relative` unhinges elements from their static position, so that they can then be placed with the direction properties (`top, bottom, left, right`). Those 4 directions accept positive and negative numerical values. Using `auto` will rest those direction properties. The values are adjusting the position of the element in comparison to the default position. Those directions are affecting the default placement of the edges of the element. If any value is set to 0, that refers to its natural placement in the flow of content. 
  -`top` will move the element's top edge. Positive values move the element's top edge downward, negative move it upwards.
  -`left` moves the element's left edge. Positive values move the element's left edge to the right, negative move it left.
  -`bottom` will move the element's bottom edge. Positive values move the element's bottom edge upward, negative move it downwards.
  -`right` moves the element's right edge. Positive values move the element's right edge to the left, negative move it right.

`Position: absolute` once again unhinges elements from the natural flow of content, and also can use the 4 directional properties. The `absolute` value references an element's ancestry, and tries to find the next closest element that HAS a `position` value. Sometimes that can mean the entire browser window. 

`Position: fixed` will keep the element in the exact same spot, even if the window scrolls. Fixed elements will get collapsed as far as they can go, so often you'll have to add the directional values to maintain the design. 

By default, position will put elements further down in the HTML, layered on top of those that came before it. You can manipulate layering with `z-index`. I think about the "Z" in `z-index` as the z-axis in math, moving in 3-D space. 
