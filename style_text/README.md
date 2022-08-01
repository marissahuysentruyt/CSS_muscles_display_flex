Tutorial 3
=========

Resource: (How to Style Text Elements with Font, Size & Color in CSS)[https://www.digitalocean.com/community/tutorials/how-to-style-text-elements-with-font-size-and-color-in-css]

Typography helps communicate the content (this is a theme I need to remember!). Hierarchy in HTML helps give distinction and order to the content. There's a difference between visual hierarchy (which you can control with CSS) and semantic hierarchy (which helps the browser accurately interpret elements). Headings are a great way to differentiate content, as well as font styles, like font-family, font-weight and font-style. All of these can help more clearly communicate what needs to be communicated.

With some font styles, you can "get away" with faux styles. Italic is a good example. Sometimes an italic version of a font doesn't exist, but you can artificially create an italic by using the <em> tag, getting the browser to slant the text for us. Additionally, as you start changing default font sizes, you will also adjust default styles for related elements. For example, if you change the body font size to be 18px as we did in the tutorial, the headings and even spacing increased proportionally. A formula that came up in the Marcotte book as well as this tutorial was "target / base = result" with a slight decimal adjustment :nerd_face: 

There's a LOT of different ways to specify color: HSL (hue, saturation, lightness), HEX (hexidecimal), named (literally the common name of a color), and RGB (red, green, blue). It's important to keep base styles in mind, especially when you start thinking of accessibility. Darker colors on light backgrounds, and light colors on darker backgrounds work well. Contrast between colors becomes critical to consider. 