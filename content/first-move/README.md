## First Move

> Brainpower Mode

### Context

Glad to see you again! It's amazing how far you've come today. You're just one step away from discovering a simple yet impressive example of what we can achieve with JavaScript. This will give you a glimpse of how JavaScript works alongside HTML and CSS to make your robot more engaging! By using JavaScript, you'll be able to control and interact with your creation, adding dynamic features that bring it to life.

So far, you haven't learned much about JavaScript (but don't worry, you will soon!). For now, we want to show you an example of how powerful JavaScript can be in modifying your robot.

In this exercise, you'll follow the steps to change your robot's eyes from open to closed using JavaScript. Does it sound simple? Yes, but later you'll make your robot even more dynamic by adding a button to open and close its eyes! Of course, that's something you'll tackle once you've learned more about JavaScript.

Think of this as a puzzle that challenges you to use your brain, follow hints, and make things work—even if it seems tricky (it’s not!). Isn't problem-solving your brain's superpower?

> Follow the instructions, ask your peers if you get stuck, and stay motivated because you're close to achieving the Shape Crafting goal!
> Pay attention to every hint provided in the instructions!

### Instructions

- For the JavaScript (JS) files, when you need to link one, it will be named like this: `name-of-the-exercise.js`.

Still with us? Great! Now, let's get to the serious part. To control your creation, you'll need to connect its brain: JavaScript.

First, define this new class in `your CSS file`:

```css
.eye-closed {
  height: 4px;
  padding: 0 5px;
  border-radius: 10px;
}
```

#### Task 1

Next, [link a JS script](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script) to your HTML file.

#### Task 2

In your JavaScript file, you'll close the left eye of your robot. To do this, first target the `eye-left` HTML element by its `id` using the [getElementById](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById) method.

#### Task 3

After targeting the eye, [set its style](https://developer.mozilla.org/en-US/docs/Web/API/ElementCSSInlineStyle/style#setting_styles) to change its background color to "black". Finally, modify its shape by adding a new class to it. Use the [classList.add()](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList) method for this step.

### Code Examples

#### Example 1

To target the `nose` HTML element by its `id` using `getElementById`:

In the HTML file:

```html
<!-- HTML -->
<div id="nose"></div>
```

In the JS file:

```js
const nose = document.getElementById("nose");
```

#### Example 2

To change the color of the nose to red:

```css
.nose-red {
  width: 20px;
  height: 20px;
  background-color: red;
  border-radius: 50%;
}
```

```js
nose.classList.add("nose-red");
```

#### Example 3

To change the background color of the nose to yellow:

```js
nose.style.backgroundColor = 'yellow';
```

### Expected Output

> By the way, do you like the new background color you chose earlier? Me too.  
> To personalize your robot even more, feel free to adjust the inclination of its arms to reflect the personality you've envisioned!  
> Adding a [rotation](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/rotate) to the `arm` class is a great way to achieve this.

This is what you should see in the browser:  
[![personalize-bring-it-to-life-dom-example.png](https://i.postimg.cc/Df5pcWN1/personalize-bring-it-to-life-dom-example.png)](https://postimg.cc/pyhBWdRd)

### Resources

Here are some resources to help you get started smoothly. Check them out!

- Video: [Link a JS script to your HTML file](https://www.youtube.com/watch?v=jMvsQm-p1gM&list=PLHyAJ_GrRtf979iZZ1N3qYMfsPj9PCCrF&index=7)
- Video: [JS variables explained](https://www.youtube.com/watch?v=XNjhAMhyVJo&list=PLDa5D3mQAy7Sj0s4J6R5HT2xsEXkYuYFL&index=3)
- Video: [DOM JS - getElementById](https://www.youtube.com/watch?v=34kAR8yBtDM&list=PLHyAJ_GrRtf979iZZ1N3qYMfsPj9PCCrF&index=8)
- Video: [DOM JS - Set an element's inline style](https://www.youtube.com/watch?v=pxlYKvju1z8&list=PLHyAJ_GrRtf979iZZ1N3qYMfsPj9PCCrF&index=15)
- Video: [DOM JS - classList: add & remove](https://www.youtube.com/watch?v=uQEM-3_4vPA&list=PLHyAJ_GrRtf979iZZ1N3qYMfsPj9PCCrF&index=17)
- [Memo DOM JS](https://github.com/nan-academy/js-training/blob/gh-pages/examples/dom.js)
