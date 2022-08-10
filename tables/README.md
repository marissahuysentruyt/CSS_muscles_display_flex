Tutorial 10
=========

Reference: [How to Style a Table with CSS](https://www.digitalocean.com/community/tutorials/how-to-style-a-table-with-css)

In this tutorial, we've added the "media" attribute to the link tag in our HTML. This designates which devices the content is made for. Our case is "all." 

The caption element should always be included within your table elements to assist with accessibility. It is not included within the actual table cells. 

Tables are built with rows, not columns. To add more "columns," you must insert more td/th (table data/date heading) tags, nested within tr (table row) tags. By default, there are gaps between table cells ("border-collapse: separate"), but you can change that using the "border-collapse: collapse" property. You can target everything in a table just as you would most elements in HTML, with classes, combinators, specificity, etc. In order to merge cells, which you cannot do with CSS, you have to use the colspan attribute. 
