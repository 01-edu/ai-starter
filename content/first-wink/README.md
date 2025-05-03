## First Wink

> JSPowered Mode

### Context

You're making fantastic progress! You've reached a crucial stage in your journey where you’ll learn how to bring your robot to life using the JavaScript basics you've gained.

Don't worry if things feel a bit challenging—that's part of the process! Just remember to take it step by step and never forget to use Generative AI along with your peers to seek clarifications. You'll be amazed at how quickly you'll see results.

> Let's use all your learning and searching skills to bring your robot to life!

#### Reminder:

- Before you start coding, take a moment to think about what you want to achieve. You can even write out a rough plan or "PseudoCode" to help organize your thoughts. It makes the coding process much easier!

> You might encounter things you don't know yet, but by now, you know what to do! Search for it, ask your peers, and use clever prompts. ;)

- **Continue working on the HTML, CSS, and JS code you submitted for the `first-move` exercise, but start with an empty JavaScript file. Don't forget to rename the linked files to match this exercise and follow the new instructions!**

### Resources

We’ve provided some content to help you get started smoothly. Check it out!

- [Video](https://www.youtube.com/watch?v=m34qd7aGMBo&list=PLHyAJ_GrRtf979iZZ1N3qYMfsPj9PCCrF&index=13) on `querySelector`
- [Video](https://www.youtube.com/watch?v=ydRv338Fl8Y) DOM JS - Add an `event listener` to an element
- [Video](https://www.youtube.com/watch?v=4O6zSVR0ufw&list=PLHyAJ_GrRtf979iZZ1N3qYMfsPj9PCCrF&index=15) DOM JS - Set an `element's properties`
- [Video](https://www.youtube.com/watch?v=amEBcoTYw0s&list=PLHyAJ_GrRtf979iZZ1N3qYMfsPj9PCCrF&index=21) DOM JS - `classList`: toggle, replace & contains
- [Video](https://www.youtube.com/watch?v=pxlYKvju1z8&list=PLHyAJ_GrRtf979iZZ1N3qYMfsPj9PCCrF&index=16) DOM JS - Set an element's `inline style`
- [Memo DOM JS](https://github.com/nan-academy/js-training/blob/gh-pages/examples/dom.js)

### Instructions

#### Task 1:

Add a button to the top-right corner of the page with the `id` set to "eye-btn". This button will toggle (close or open) the left eye when clicked.

Add it to the HTML structure:

```html
<button id="eye-btn">Click to close the left eye</button>
```

And add the style in the CSS file:

```css
button {
  z-index: 1;
  position: fixed;
  top: 30px;
  right: 30px;
  padding: 20px;
}
```

#### Task 2:

Select the button in your JavaScript file by its `id`. This will allow the user to control the robot’s left eye.

```js
// Select the button element using its ID so we can interact with it in our JavaScript

// Example of selecting a button called btn-example
const myButton = document.getElementById("btn-example");
```

**`Prompt Example:`**

- "How do I use `getElementById` to select an HTML element by its ID?"

#### Task 3:

Write a function that will be triggered when the button is clicked.

This function will make the robot "wink" by toggling the `eye-closed` class on the left eye and changing the `button` text based on the current state of the eye.

1. Change the text content of the button: if the eye is open, display "Click to close the left eye"; if the eye is closed, display "Click to open the left eye".
2. Toggle the `eye-closed` class in the `classList` of the `eye-left` HTML element.
3. Change the background color of the `eye-left`: if the eye is open, set it to "red"; if the eye is closed, set it to "black".

**Code Example:**

```js
const button = document.getElementById('eye-btn');

const handleClick = (event) => {
  // Select the left eye by its ID and assign it to the variable eyeLeft
  const eyeLeft = ...;

  // Check if the eye is currently closed by looking at the eyeLeft background color. If it's 'black', that means it's closed.
  if (...) {
    /*
     - Set the button's text to: "Click to close the left eye"
     - Change the eyeLeft background color to red
    */
  } else {
    /*
    If the eye is open:
    - Set the button's text to: "Click to open the left eye"
    - Change the eyeLeft background color to black
    */
  }
  // Toggle the 'eye-closed' class on the 'eye-left' div
  eyeLeft.classList.toggle("eye-closed");
};

/* Register the event:
   Here we ask the button to call our `handleClick` function
   on the 'click' event, so every time it's clicked
*/
button.addEventListener('click', handleClick);
```

### Expected Result

You can see an example of the expected result [here](https://youtu.be/IQ6-3X3JBss).

**`Prompt Examples:`**

- "As a beginner, explain to me how I can change the text content and the background color of an `HTML element` using JavaScript?"
- "As a beginner, explain to me how to use `addEventListener` to make a button respond to a click event in JavaScript?"
