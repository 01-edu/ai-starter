## Colorful Legs

> JSPowered Mode

### Context

Your robot is cool! But you can make it even more striking! At the very least, let it show off its colorful legs to everyone!

> Follow the instructions, ask your peers if you're stuck, and stay motivated because you're close to the goal!
> Pay attention to every hint provided in the subject!
> Continue working on the code from the last exercise, and update the file names accordingly!

### Instructions

Just like you made your robot's arms special in the last exercise, you'll now do the same for its legs!

Follow the steps below:

#### Task 1:

Add another button to the top-right corner of the page with the ID `leg-color` that will change the color of the robot's legs. Include it in the HTML structure:

```html
<button id="leg-color">Robot's Leg Colors</button>
```

Style the button in the CSS file:

```css
#leg-color {
  position: fixed;
  top: 240px;
  right: 30px;
  padding: 10px;
  margin-bottom: 20px;
  z-index: 2;
}
```

#### Task 2:

In the JavaScript file, as in the previous exercise, retrieve the following elements:

- The button with the ID `leg-color`.
- The left and right leg elements with the IDs `leg-left` and `leg-right`.
- Apply a random color to both legs by modifying their `backgroundColor`.

### Expected Result

You can see an example of the expected result [here](https://youtu.be/vnzQ0R-Ixl0).

**`Prompt Example:`**

- "What mistakes should I avoid while changing the background color of multiple elements in JavaScript?"
