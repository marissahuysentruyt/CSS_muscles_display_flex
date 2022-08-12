Tutorial 13
=========

Reference: [How to Use Relationships to Select HTML Elements with CSS](https://www.digitalocean.com/community/tutorials/how-to-use-relationships-to-select-html-elements-with-css)

Descendant Combinators: think of a family tree of parents, siblings, children, ancestor, etc. The final selector is the one that actually is getting targeted for styles. Descendants can add specificity. 

If you want to target direct, immediate children of a parent element use ">". Sibling combinators can be used to select further sibling elements. In the case of ".general-sibling p ~ p," the CSS is actually selecting all of the p elements after (~) the initializing selector (".general-sibling p"). Adjacent siblings can be indicated with the "+". In the case of ".adjacent-sibling p + p" you are selecting a paragraph that is immediately after another paragraph (they have to be touching), both of which are within .adjacent-sibling. 

:first-child, :last-child, and :only-child are all pseudo-classes. Using :nth-child can help select specific children of certain parent elements based on their numeric sequence. This pseudo-class can also accept values like even and odd (think striping in a table).  
