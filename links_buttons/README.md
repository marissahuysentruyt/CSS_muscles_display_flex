Tutorial 8 
=========

Reference: [How to Use Links & Buttons with State Pseudo-Classes in CSS](https://www.digitalocean.com/community/tutorials/how-to-use-links-and-buttons-with-state-pseudo-classes-in-css)

Links are for interacting with different URLS (navigation). Buttons are used to do something, like trigger events in JavaScript (save, submit, pull up a modal window, etc.). To a user they're roughly the same, but in code, they serve quite different purposes and should be coded as such. 

Vendor prefixes are things like -webkit, or -moz. To completely get rid of default styles of a button, you need to use those vendor prefixes for certain properties, as well as background-color, border, margin, padding, color, font, & text-align. 

Pseudo-classes are defined by a colon. Hovers, focus, active and visited are the most common pseudo-classes. The focus state is especially helpful for accessibility. You can also string multiple pseudos together, like "visited:hover" to regain previous styles. 

Transitions help blend different states of styles together, so it's not abruptness and jarring. There's a lot of properties, like property (or name), duration, timing-function, that can all be shorthanded into the transition property. 

In testing the :focus, I saw that the "this tutorial" & "No thank you" links aren't able to be tabbed to. In Chrome, they work just fine. 
