## First Hello

> JSPowered Mode

### Context

Your robot winked, but now you can make it talk too! Or at least, make it say its first hello to the world!

> Follow the instructions, ask your peers if you're stuck, and stay motivated because you're close to your goal!
> Follow every hint provided in the subject!
> Continue from the code in the last exercise, and update the file names accordingly.

### Instructions

Now that you know how to make your creation move, how about making it communicate its first words to the world?

After completing these tasks, you'll be able to display and hide `Hello World` in the `torso` of your robot by clicking a second button.

#### Task 1:

Add a second button in the top-right corner of the page that will display some text when clicked. Include it in the HTML structure:

```html
<button id="speak-button">Click me to speak</button>
```

Add the button style in the CSS file:

```css
button#speak-button {
  top: 100px;
}
```

Also, add this class to style the text we will add:

```css
.words {
  text-align: center;
  font-family: sans-serif;
}
```

#### Task 2:

In the JS file, as in the previous exercise, select the HTML `button` element with the id `speak-button` and add an `event listener` for the `click` event. This should trigger a `function` that will:

- Select the torso element with `id="torso"`.
- Check if a `div` with the class `words` already exists inside the torso element.
- If it exists, remove the existing `div`.
- Otherwise:
  - Create a new HTML element of type `div`.
  - Set its text content to "Hello World".
  - Assign it the class name `words`, as defined in the CSS.
  - Use the `append` method to add the new `div` inside the torso element.

### Code Example:

```js
// Select the button with id 'speak-button'

//...Here

// Function triggered when clicking the new button
const handleSpeakClick = (event) => {
  // Select the torso element where the text will be added or removed
  const torso = document.querySelector("#torso");

  // Check if a div with the class 'words' already exists inside the torso
  const existingDiv = document.querySelector("#torso .words");

  if (existingDiv) {
    // If the "Hello World" text exists, remove it from the torso
  } else {
    // If the "Hello World" text does not exist, create and append it
    // Create a new div element
    // Add the 'words' class to the div
    // Set the text content to "Hello World!"
    // Append the new div to the torso element
  }
};

// Attach the handleSpeakClick function to the 'speak-button' button
//...Here
```

### Expected Result

You can see an example of the expected result [here](https://youtu.be/PuyEdAA0wy4).

**`Prompt Example:`**

- "How can I add and remove text in an element with a button click in JavaScript?"
