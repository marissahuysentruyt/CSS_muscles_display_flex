 Tutorial 9
 =========

 Reference: [How to Select HTML Elements Using ID, Class, & Attribute Selectors in CSS](https://www.digitalocean.com/community/tutorials/how-to-select-html-elements-using-id-class-and-attribute-selectors-in-css)

 To target more specific elements, you can use attributes, and especially id's and classes. ID's are indicated in the CSS with the pound sign, and should be unique to a single element within the HTML. Classes are reusable, indicated by a period/dot in CSS. You can also combine classes to create even more specific targeted elements (this may override other styles).

 The attribute selector is shown with [brackets]. This is saying that any element that has an attribute of whatever is inside those brackets should be selected. You can also specific elements + attribute selectors such as abbr[title]. This selector is targeting any abbr element that has a "title" attribute. 

 More advanced attribute selectors: 
    [href=""] => select any element with an href attribute equal to "whatever is in the quotes"
    [href^=""] => select any element with an href attribute that starts with "whatever is in the quotes"
    [href*=""] => select any element with an href attribute that includes "whatever is in the quotes" somewhere
