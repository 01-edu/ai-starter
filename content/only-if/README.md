## Only If

> Mindful AI Mode

### Context

You are close to achieving ultimate power! Are you ready to command your robot using conditions? In JavaScript, conditions allow you to control what your robots do based on different situations.

Let's have some fun with it!

### AI-Powered Learning Techniques

**Interactive Learning Technique:**
This type of prompt engages you in active problem-solving by providing challenges or tasks that require applying concepts. You can also compare your results with your peers!

Find examples throughout the subject ;)

### Concepts

### Conditions in JavaScript

Conditions in JavaScript are like decision points. They allow you to execute different actions based on whether a condition is true or false.

```js
if (condition) {
  // Code to execute if the condition is true
} else {
  // Code to execute if the condition is false
}
```

For example:

```js
let batteryLevel = 75;

if (batteryLevel > 50) {
  console.log("Robot is ready to patrol!");
} else {
  console.log("Robot needs to recharge.");
}
```

### Truthy and Falsy

In JavaScript, all values are either `truthy` or `falsy`. Truthy values validate conditions, while falsy values do not.

#### Falsy Values:

- `undefined` and `null`
- Numbers: `0` and `NaN`
- Empty string: `''`
- Boolean: `false`

**All other values are `truthy`!**

### Logical Operators

### AND Operator (&&)

The AND operator combines conditions:

```js
// Example: let robot = { status: 'active', battery: 75, name: 'RoboGuard' };

if (robot.status === "active" && robot.battery > 50) {
  console.log("Robot " + robot.name + " is active and has sufficient battery.");
}

// Output: Robot RoboGuard is active and has sufficient battery.
```

### OR Operator (||)

The OR operator combines conditions:

```js
if (robot.type === "security" || robot.type === "assistant") {
  console.log(robot.name + " is available for tasks.");
}
```

### `else if` Keyword

Chain conditions using `else if`:

```js
if (temperature < 8) {
  console.log("Very cold!");
} else if (temperature < 16) {
  console.log("Still too cold...");
} else if (temperature < 24) {
  console.log("Getting warmer");
} else if (temperature < 32) {
  console.log("Nice :)");
} else {
  console.log("Too hot!!!");
}
```

#### **`Prompt Example`**:

- "Give me an easy coding challenge involving conditions in JavaScript, and provide feedback on my solution."

### Instructions

#### Task 1:

Your robot must always seek the truth.

- Check if the value of the provided variable `truth` is truthy. If so, log the string: `The truth was spoken.`
- Otherwise, log the string: `Lies!!!!` because the value of the provided variable `truth` is falsy.

#### Task 2:

Your `RoboGuard's traveling company` has a special promotion for robot members aged between 18 (inclusive) and 25 (inclusive).

**Note:** The variable `ticket` has already been declared, so do not declare it again.

1. Assign the message "You cannot benefit from our special promotion" to the variable `ticket`.

2. Use an `if` statement to check that all these conditions are true:

- `user.age` must be greater than or equal to `18`.
- `user.age` must be less than or equal to `25`.
- `user.activeMembership` must be `true`.

3. If all conditions are true, update the variable `ticket` with the message: "You can benefit from our special promotion."

> Hint: Use the AND operator in your condition!

#### Task 3:

Your RoboGuard is selling plane tickets, each costing `9.99$`. The RoboGuard must confirm that the customer robot has the means to buy this ticket.

The customer robot may have enough cash **or** possess a voucher.

Check if the provided variable `customer` can afford the ticket:

- If the customer has enough `cash` (`customer.cash` property)
**OR**
- If the customer has a `voucher` (`customer.hasVoucher` property is true)

If so, `increment` the provided variable `ticketSold` value by `1`.

> Hint: Use the OR operator in your condition!
