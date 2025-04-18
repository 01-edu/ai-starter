## Class it!

> Brainpower Mode

### Context

You're almost done creating your being! A few elements still need some refinement, and then we'll bring it to life!

### Resources

We’ve provided some content to help you get started smoothly. Check it out!

- Video: [CSS - Set & style with CSS class](https://www.youtube.com/watch?v=-U397k4VloU&list=PLHyAJ_GrRtf979iZZ1N3qYMfsPj9PCCrF&index=6)

### Instructions

If you look at your page, you’ll notice that some elements come in pairs: the eyes, the arms, and the legs. These are identical organs, one on the left and one on the right, sharing the same shape. To avoid duplicating styles, we won’t use their `id` for styling. Instead, we’ll use a [`class`](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors). Unlike an `id`, a `class` can be assigned to multiple elements, allowing a common ruleset to apply to all HTML elements with that class.

#### Task 1

Create the following three classes, apply the specified rulesets, and assign them to the corresponding HTML elements:

- Class `eye`:
  - `width`: 60 pixels
  - `height`: 60 pixels
  - `background-color`: "red"
  - `border-radius`: 50%
  - Assigned to `eye-left` & `eye-right`
- Class `arm`:
  - `background-color`: "aquamarine"
  - Assigned to `arm-left` & `arm-right`
- Class `leg`:
  - `background-color`: "dodgerblue"
  - Assigned to `leg-left` & `leg-right`

Additionally, you can assign multiple classes to the same element. Create a class `body-member` that sets the `width` to 50 pixels and the `margin` to 30 pixels. Add this class to the `class` attribute of the following elements: `arm-left`, `arm-right`, `leg-left`, & `leg-right`.

### Code examples

Define a class `my-first-class` and style it with a `color` of `"blue"` and a `background-color` of `"pink"`:

```css
.my-first-class {
  color: blue;
  background-color: pink;
}
```

Apply classes to HTML elements:

```html
<div class="my-first-class"></div>
<div class="another-class"></div>
<div class="my-first-class another-class"></div>
```

### Expected output

Here’s what you should see in the browser:
![](https://github.com/01-edu/public/raw/master/subjects/class-that/class-that.png)

> Need help? Ask your tablemate.

### Notions

- [CSS class](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors)

