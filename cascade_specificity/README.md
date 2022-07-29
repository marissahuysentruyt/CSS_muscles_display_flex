Tutorial 1
----------

Resource: (How to Apply CSS Styles to HTML with Cascade & Specificity)[https://www.digitalocean.com/community/tutorials/how-to-apply-css-styles-to-html-with-cascade-and-specificity]

This tutorial is all about utilizing CSS "inline" and using the style tag in an HTML document. 

Inline styles happen directly in the opening tag of a single HTML element, using the style attribute. In this style attribute, you may write CSS properties & values. Nested HTML elements (like a strong tag) will automatically inherit styles from their parent elements. You can directly target those nested elements by adding their own style attributes. 

By using the style HTML tag, you can write full-blown CSS, most often in the head of your HTML doc (but not always). By using the style element, you can affect different HTML elements on the page all at once. 

With an external CSS file, you can style multiple HTML pages at once. However, with larger & larger CSS files, you run into the cascade (because the browser reads & applies changes from the top-down). It is exceedingly important to structure your CSS file in a way that avoids overrides and cascade issues. Specificity in the styles is just referring to how you target a specific HTML element. 

Beware of !important...this is a last-ditch effort to force a style and shouldn't be used frequently. Write a comment to explain why it was used if you must (i.e. JavaScript loaded inline styles, which are at the bottom of the cascade and cannot be deleted from the HTML), after exhausting all other options. 
