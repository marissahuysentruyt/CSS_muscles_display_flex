Tutorial 19
========

Reference: [How To Style Figure and Image HTML Elements with CSS](https://www.digitalocean.com/community/tutorials/how-to-style-figure-and-image-html-elements-with-css)

Whenever using images, don't forget to add `alt` tags! They are very important descriptions for assistive technologies and help with accessibility. 

To make an image fluid, or responsive to browser resizing, you have to use the `width` property. That tells the image to take up 100% of the space it needs, but in relation to however large its parent container is. 

Figures and figure captions (`figcaption`) can give all readers more context about what images they are seeing. Images are placed inside `figure` tags, with `figcaption` descriptions. `Figcaption` content is different from `alt` tag content because it can give even further context to the image itself, like where it was taken (info that isn't clearly evident in the photo). Keep in mind that there are default styles (typically margins) applied to images and figures. 

The `picture` element is a way to have a source set of images that can be swapped out for each other when certain screen sizes are detected. `Picture` also requires `source` elements (containing the different image files), and a final `img` element to be used as the default. `Source` defines the location of the images (`srcset` attribute) and the media queries of when to use the different images (`media` attribute).

`Object-fit` is a property that controls the vertical and horizontal scaling an image might need. It is similar to `background-size` and can accept the same values (like `cover` or `contain`). `Object-position` is also similiar to `background-position` where your image is anchored to a specific area (like `bottom right` in the CSS file). 
