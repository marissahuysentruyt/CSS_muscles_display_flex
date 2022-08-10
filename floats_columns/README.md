Tutorial 11
==========

Reference: [How To Use Float and Columns to Lay Out Content with CSS](https://www.digitalocean.com/community/tutorials/how-to-use-float-and-columns-to-lay-out-content-with-css)

Floats and columns were what was used to create layouts before flexbox and grid. 

Anytime you add the float property to an element, it might be floating in one direction, while the remaining wrapping content goes in the other. However, if the floating elements' content is longer, sometimes you may have to adjust the width manually in the CSS. To get an element to stop wrapping, you utilize the clear property. Whatever has clear on it, will not conform to the wrapping it may have had due to other floating elements.

With images, be sure to use "max-width" so that they are able to shrink and grow according to their parent containers, but so that they also do not grow beyond their maximum pixel size. Additionally, we can use negative margins to utilize bigger empty spaces as screen sizes increase. 

The columns property creates a dividing line and basically determines how an element will separate into columns. You can specify how many columns, if there is a gap between the columns, and whether or not you want to see that vertical rule line between columns. Another property is break-inside: avoid, which tells the browser to continue the content to the end of the column, and then break into another column. This prevents paragraphs from being at the bottom of one columns AND the top of the next. 
