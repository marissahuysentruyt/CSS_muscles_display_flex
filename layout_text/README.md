Tutorial 6
----------

Resource: [How To Lay Out Text with CSS](https://www.digitalocean.com/community/tutorials/how-to-lay-out-text-with-css)

Always make sure to have a fallback font that can use a machines default fonts in case a custom font won't load or is missing certain characters. Continue to use units like rem's or em's since you'll have more control over proportions & ratios as projects progress. The font shorthand property requires at least the font-size and family, but will overwrite other individual properties a selector might have (be careful when using). To include line-height in the shorthand, it is required to use / immediately after the font-size. Other values for font can be: font-stretch, font-style, font-variant, and font-weight.  

Line length is not really something I've ever thought about, but the physical length of a line of text can contribute to the user's perceived effort it takes to actually read it. Longer lines = more effort = bad. Shorter lines can help a reader scan more quickly. According to a talk on [responsive typography](https://www.youtube.com/watch?v=hjXPAtBJd-Y), an ideal line length is somewhere between 45-75 characters. 

The unit "ch" stands for character count. The line-height refers to the space between lines of text (based on the baselines/bottom of the text). This tutorial also reminded me of the rem & em relationships, as well as the margin collapse feature of CSS.

The adjacent sibling combinator is signified by a plus sign (+). This allows you to target and style the last element in that selector, that is specifically the first sibling to the first element in the selector. 

For text-align, the default value for this properties changes based on what language the browser is set to (ltr languages will have left as default, while rtl languages will have right as default). Text transform controls capitalization formatting of text. This can be useful to change heading formats without having to access the HTML, however that can sometimes negatively affect how screen readers interpret the content. 
