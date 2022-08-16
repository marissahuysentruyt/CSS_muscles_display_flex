Tutorial 15 
==========

Reference: [How To Load and Use Custom Fonts with CSS](https://www.digitalocean.com/community/tutorials/how-to-load-and-use-custom-fonts-with-css)

A font stack ("font-family") is a selection of fonts that the browser attempts to load. If the browser can't access the first font, it moves to the next fallback font, and so on. The font family (font-weight, font-style) is all of the weight and style variations for a certain font. It's fastest (a.k.a more performant) to just use pre-loaded fonts that come on a user's computer. Those will load fastest. 

Instead of pre-loaded fonts, you can also use hosted fonts. This means your users temporarily download a font they may not have on their computers in order to view your site properly. However...more fonts = more downloads = more time to load. Even the number of styles and weights (which are all separate files) will need to be downloaded and run, impacting the site's performance.

`@font-face` is a set of definitions or rules for self-hosted fonts (perhaps they aren't provided on a hosting site). `@font-face` doesn't require any further parameters or argument (like `@media` does). Within the rule set, you have to name the font-family to help the browser load the correct font from your files. The src property references the location of those font files. You will also have to create rules for every variation of your font, including bold & italic. If you don't specify each variation, you may end up with faux bold/italic. 

Variable fonts are a single file, where variations about the font can be calculated in order to change it. This can give you better performance and a lot more possibility of design. With the `@font-face` rule, you'll still have to declare the src (just one format will do for most variable fonts). For font-weight, you can actually declare a range of values, thin to thick. The advantage here is that you can use any whole number to determine the weight of the font (as long as it's within the given range). 
