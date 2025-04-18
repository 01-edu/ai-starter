## Embedded Organs

> Brainpower Mode

### Context

Congratulations! You've outlined the overall structure of your robot friend. Now it's time to bring it to life by adding its essential components. Let's equip your robot with its vital organs! To achieve this, we'll introduce the concept of nesting elements within others. This approach will allow you to build a fully functional robot, one step at a time.

> Don't be intimidated by the complexity of the tasks. Break them down into smaller, manageable steps.

### Instructions

Currently, your `<body>` contains a single layer: `face`, `upper-body`, and `lower-body` are all at the same level. However, as you know, a face includes two eyes, a nose, and a mouth—and within that mouth, there’s a tongue, and so on. Any element can serve as a container for other elements.

#### Task 1

Add new elements and organize them into different layers. Convert the following list of organs into an HTML structure using the corresponding tags:

```html
<section id="face">
  <div id="eyes">
    <p id="eye-left"></p>
    <p id="eye-right"></p>
  </div>
</section>

<section id="upper-body">
  <div id="arm-left"></div>
  <div id="torso"></div>
  <div id="arm-right"></div>
</section>

<section id="lower-body">
  <div id="leg-left"></div>
  <div id="leg-right"></div>
</section>
```

#### Task 2

Update your CSS file to add rules for the `section` tags: set `display` to "flex" and `justify-content` to "center". This will turn the `section` tags into [flex containers](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox), centering the elements inside them.

#### Task 3

Add the following CSS to your file to style the newly added nested elements:

```css
div,
p {
  border: solid 1px black;
  padding: 10px;
  margin: 0;
  border-radius: 30px;
}

#face {
  align-items: center;
}

#eyes {
  display: flex;
  background-color: yellow;
  justify-content: space-between;
  align-items: center;
  border-radius: 50px;
  width: 200px;
}

#torso {
  width: 200px;
  background-color: violet;
}
```

### Code examples

Here’s an example of nesting multiple elements:

```html
<div id="first-element">
  <span id="second-element"></span>
  <div id="third-element">
    <p id="fourth-element"></p>
  </div>
</div>
```

### Expected output

Here’s what you should see in the browser:
![](https://github.com/01-edu/public/raw/master/subjects/nesting-organs/nesting-organs.png)

> From now on, you can customize the `background-color` of the following sections in the CSS code to match your theme:  
> \#face  
> \#upper-body  
> \#lower-body  
> Not sure which colors are available? [This list might help](https://letmegooglethat.com/?q=css+color+list).

### Notions

- [Anatomy of an HTML element](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#anatomy_of_an_html_element)
- [Nesting HTML elements](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#nesting_elements)
- [Flexbox layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox). You can practice with [Flexbox Froggy](https://flexboxfroggy.com/).
