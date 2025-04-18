## The Smooth Operator

> Mindful AI mode  
> Unlike the song, smooth operators in JavaScript help you perform various calculations and manipulations with ease.

### AI-Powered Learning Techniques

**Step-by-Step Instruction Technique:**

This type of prompt encourages the AI to provide detailed, step-by-step instructions for learning new concepts.

> Find examples across the subject ;)

## Concepts:

### Math Operators

In JavaScript, operators are symbols that perform operations on variables and values. Let's explore the most common types of operators you'll encounter.

For now, let's focus on the ones you probably already know:

- `+` Addition
- `-` Subtraction
- `/` Division
- `*` Multiplication

These operators are used in the same way we write them in math:

```js
console.log(5 + 7); // -> 12
console.log(5 * 5); // -> 25
console.log(7 - 5); // -> 2
console.log(9 / 3); // -> 3
```

Operators are evaluated using classic precedence rules:

```js
console.log(1 + 5 * 10); // -> 51
```

You can use parentheses `()` to enforce precedence:

```js
console.log((1 + 5) * 10); // -> 60
```

Operators produce a value, so they can be assigned to variables:

```js
let halfMyAge = 33 / 2;
let twiceMyAge = 33 * 2;
```

#### **`Prompt example`**:

"Can you provide step-by-step examples of basic math operations in JavaScript?"

### Placeholders

JavaScript allows you to include expressions within strings using template literals. This is done using backticks `` ` `` and the `${}` syntax to include expressions.

#### Example

```js
console.log(`5 + 10 = ${5 + 10}`); // -> 5 + 10 = 15
```

**Note:** This only works with backticks `` ` ``, not with double quotes `"` or single quotes `'`.

#### **`Prompt example`**:

"Can you provide a step-by-step guide on how to use template literals to create a string that includes variable values in JavaScript?"

### Instructions

#### Task 1:

Your code must use the given variable `smooth` as the initial value.

> When in doubt, always test your code with `console.log()` and the Run button.  
> However, when the platform provides an already existing variable to manipulate, like the `smooth` variable here, if you want to use or display it, you must do so with the Submit button.  
> You'll then see the result in the code editor console output, as this variable is not available in Run mode but only in Submit mode.

```js
console.log("smooth = ", smooth);
let lessSmooth = smooth - 5;
console.log("lessSmooth = ", lessSmooth);
```

Declare the following variables:

- `lessSmooth`: This is `1` less than `smooth`.
- `semiSmooth`: This is half the value of `smooth`. _(It's still pretty smooth!)_
- `plus11`: This is `smooth` plus `11`.
- `ultraSmooth`: This is the square of `smooth`. _(Now that's smooth!)_

#### Task 2:

We will provide two variables, `name` and `age`, which will be defined by us.

Declare your robot's `presentation` variable with the value:  
`Hello, my name is NAME and I'm AGE years old.`  
Make sure to replace `NAME` and `AGE` with the appropriate values provided by us.

---

> BGM:  
> [Sade - Smooth Operator - Official - 1984](https://www.youtube.com/watch?v=4TYv2PhG89A)
