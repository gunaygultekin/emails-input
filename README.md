# emails-input
A simple js library for creating email block. This EmailsInput doesn't have any dependencies and can be used with any other form or app independently.

Here's demo

### NPM

npm i emails-input-jslibrary

[https://www.npmjs.com/package/emails-input-jslibrary](https://www.npmjs.com/package/emails-input-jslibrary)

### Usage:

* To use the EmailsInput you can simply add a reference to the .js file at the end of the body of your html and the .css file in the head of your html page.  

* Email block is created by pressing Enter, entering comma, or by losing focus on the input field.

* The input has too many emails, the user is able to scroll.

* When multiple comma-separated emails are pasted (e.g., “gig@com, max@max.com”), they will be converted into multiple email blocks.

* That's it.
  
### Methods:

The plugin exposes some methods that you can use:

* **emailsInput.render()** - This will initialize the EmailsInput and create UI. 

* **emailsInput.addEmail()** - This will add a random email to email block.

* **emailsInput.getEmailCount()** - This will shows an alert with valid emails count.