## Listed

> Mindful AI Mode

### Context

Sometimes, we don't need a key; we just want a list of things. JavaScript has a special type for that, called an array.

In JavaScript, arrays are essential tools for efficiently managing these lists.

Let's explore them together!

### AI-Powered Learning Techniques

**Example-Based Learning Technique:**
This type of prompt encourages the AI to provide concrete examples to illustrate concepts, making them easier to understand and apply.

Look for examples throughout the subject. 😉

### Concepts

### Understanding Arrays

Arrays are special types of objects in JavaScript used to store lists of items. Unlike objects, arrays don't have keys for each element, just a list of values.

**Example of an Array**

Here's an example of an array:

```js
let batteryLevels = [
  80, // <- no keys!
  60,
  90,
  50,
];

// Or, for brevity, we often write them on a single line like this:

let batteryLevels = [80, 60, 90, 50];
```

### Indexes in Arrays

The position of an element in an array is called its `index`, starting from `0`. So, our `batteryLevels` array is roughly equivalent to writing this object:

```js
let batteryLevelsObject = {
  0: 80,
  1: 60,
  2: 90,
  3: 50,
};
```

### Accessing Array Values

To access a value in an array, use the index inside square brackets:

```js
let batteryLevels = [80, 60, 90, 50];
console.log(batteryLevels[0]); // -> 80
console.log(batteryLevels[3]); // -> 50
console.log(batteryLevels[6]); // -> undefined
```

### Using the `.length` Property

Arrays keep track of how many elements they contain using the `.length` property:

```js
console.log([].length); // -> 0
console.log([80].length); // -> 1
console.log([80, 60, 90, 50].length); // -> 4
```

### Replacing an Array Value

You can replace an array value by accessing it via its index and assigning a new value:

```js
let robotTasks = [
  "Charging",
  "Cleaning",
  "Maintenance",
  "Patrolling",
  "Greeting",
];

// Let's say I want to change 'Charging' to 'Upgrading'
robotTasks[0] = "Upgrading";

console.log(robotTasks);
```

Now, the array looks like this:

```js
["Upgrading", "Cleaning", "Maintenance", "Patrolling", "Greeting"];
```

#### **`Prompt Example`**:

- "How does accessing an array element differ from accessing an object property?"

- "Can you think of a scenario where using an array to store values would be more beneficial than using separate variables?"

### Instructions

#### Task 1:

Declare a variable `components` that contains 4 strings, one for each robot component: `"motor"`, `"sensor"`, `"battery"`, and `"camera"` (in that order).

#### Task 2:

We provide you with a variable `robotParts` that contains some elements. You will need to access them and assign their values to variables:

- A variable `firstPart` for the first element of the `robotParts` list.
- A variable `lastPart` for the last element of the `robotParts` list.
- A variable `comboParts` as an array of 2 elements: the last and the first element of the `robotParts` list, in that order.

Example: if `robotParts` is `[1, 2, 3]`

- `firstPart` would be `1`
- `lastPart` would be `3`
- `comboParts` would be `[3, 1]`

#### Task 3:

- Replace the third element of the provided `replaceComponents` array with the string `'enhanced'`.

Example:

```js
let replaceComponents = ["motor", "sensor", "battery"];
// expect -> ['motor', 'sensor', 'enhanced']
```

- Swap the first and second elements of the provided `swapComponents` array using a variable `temp`.

_Hint: Use a `temp` variable to store the first element. You must modify the array `swapComponents`, not create a new one!_

Example:

```js
let swapComponents = ["motor", "sensor", "battery"];
// expect -> ['sensor', 'motor', 'battery'] (last element is untouched)
```

> "Programming is like building a robot. You start with the basics, but the fun really begins when you start swapping parts and adding enhancements!"
