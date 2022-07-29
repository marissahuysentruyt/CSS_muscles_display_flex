Tutorial 2
---------

Resource: [How to Select an HTML Element to Style with CSS](https://www.digitalocean.com/community/tutorials/how-to-select-html-elements-to-style-with-css)

The first thing in this to tutorial to understand is the familial relationship of all the HTML elements. Things that are nested can be considered children, grandchildren, and so forth depending how deeply they are nested within parent elements. You can also have sibling relationships, where elements are at the same nesting level as others. 

With the nesting relationships in mind, combinator selectors can target more specific elements. You don't need to have direct parent-child relationships. The final target that should be styled is at the end of a list of element selectors, all separated by a space. Here's an example: 
    ul strong {
        color: dodgerblue;
    }
In this case, any strong element that is a descendant (not necessarily a child, or even ul li strong) of a ul will get this style. 

As you are using more semantic and accessible HTML elements, make sure to keep landmarks in mind as they are used with assistive technologies to scan/read the page. For this reason, there should only be a single header for elements like articles (makes sense!) It also helps to continue to keep the context of your content in mind when thinking of how to semantically structure your HTML. That is something I need to keep in mind, that what I'm creating is supposed to aid in communication.

Using element/type selectors, you can change entire chunks of your page in one place. Want all the div background-colors to be highlighter green? You can write: 
        div {
            background-color: chartreuse;
        }
one time in your stylesheet, and affect all the divs at once. You can also override inherited styles by specifying them in the stylesheet (i.e. bold font-weights for heading elements can be changed to regular/normal font-weights). 

Selector groups are just combining multiple selectors that get the same CSS styles. They are separated by commas and most often line breaks, like this: 
    h2, 
    h3 {
        color: blue;
    }
Since they get the same treatment, you can target your H2's & H3's in one place. This way of selecting HTML is a perfect example of DRY!

DON'T REPEAT YOURSELF!
====================