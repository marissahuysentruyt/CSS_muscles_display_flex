Tutorial 14 
===========

Reference: [How To Use the Display Property to Manipulate the Box Model in CSS](https://www.digitalocean.com/community/tutorials/how-to-use-the-display-property-to-manipulate-the-box-model-in-css)

The display property of elements is very powerful. An element with display: block will take up the full width of its parent container. They are usually rendered on new lines, stacked one on top of another from top to bottom. Inline elements don't typically take up the entire width of their parent containers, so they can sometimes can sit next to each other, in the direction of the content flow. Simply: blocks will break the flow, while inline won't. 

Inline-block combines properties of block & inline elements. It keeps the element in the flow of the rest of the content, while maintaining box model properties like margins & padding. You can use inline-flex, inline-grid, and inline-table. Inline-block doesn't disrupt the flow of content, doesn't take up full width

Every element of a table has its own default display property, and many times it can be helpful to change that property when screens get smaller & items start scrolling horizontally. Just be careful not to make the data inaccessible to screen readers. 

Display: none completely removes an element, both visually and from the DOM. The element will be completely hidden. 


