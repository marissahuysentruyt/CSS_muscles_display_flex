Tutorial 20
=======

Reference: [How to Style Common Form Elements with CSS](https://www.digitalocean.com/community/tutorials/how-to-style-common-form-elements-with-css)

Default browser styles are all different when working with form fields. 

The `appearance` property is a way to remove special styling from form elements (radio buttons and checkboxes are removed completely, and even get rid of the default dropdown/select arrows). A lot of browsers still require a prefix before this property is considered valid (like `-webkit` for Chrome/Safari/Edge/Opera or `-moz` for Firefox). Once you remove the default styles, you can add and customize fields as you choose. 

With radio buttons and checkboxes, EVERYTHING gets removed, including the selection indicators. You will have to add those back in manually (most likely with the `:checked` pseudo-selector) so when interactions happen, the user knows. When you use `:checked`, you can even implement custom SVGs to show that a selection has occurred. 

Buttons should perform an action: in this case, submit the form, or reset the form. These 2 buttons do the exact opposite of each other, so it is extremely important that they look very different. 

Outline is a great way to utilize the browser's focus state. Sometimes it's necessary to remove the default styles, so you can add your own to match the design better. 
