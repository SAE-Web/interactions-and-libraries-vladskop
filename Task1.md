## Part 1

1. Create a new HTML document. In the body, create a hyperlink with a unique id and with an href of '/next-page'.


2. Click on the link-what happens? Remember this is what a hyperlink does-it's the default action.  To prevent this, we'll need to add code.


3. In your JS file, you'll need to create a variable that will be a handle to the link. We do that by writing something like `document.getElementById(<your id>)`


4. Now that you have a handle, we need to find out when the link is clicked. We do this by adding an event listener. You can do this by adding `element.onClick()...` or `element.addEventListener('click',...)`. In the function part of the listener, simply write something that will let you know it's been clicked.


5. Now, create a variable and set it to 0. Make it so that each time the link is clicked, add 1 to the variable.


6. Find a way to show the value of the variable you created in step 5, so that when the user clicks on the link, they will be able to see the value update.


## Part 2
Create a slider that runs between 1 and 10. In order to be able to find out when the slider changes, you'll need to use the 'onChange' signal. Implement this using the techniques you developed in part 1 so that when the slider changes, there is a number to the right of it that updates.

## Part 3
For this exercise you will a text input field and an empty div. Using the methods developed above, make it so that when the user types more than 5 characters into the input box, their text appears in the div.
