## I Win Arguments

> Mindful AI mode

### Context

You’ve reached the final mission to unlock your full potential, which will bring your robot to life and make it fully functional!

The last step involves mastering the use of `arguments` in functions. By learning how to use and manage these `arguments` effectively, you can unlock the full potential of your robot and truly bring it to life.

Let’s dive in!

### AI-Powered Learning Techniques

**Code Chunking Technique:**

This technique encourages you to break down larger pieces of code into smaller, manageable chunks.

Each chunk is explained individually, helping you understand the purpose and functionality of each part.

Find examples throughout the subject. 😉

### Concepts

#### One Argument

As mentioned earlier with methods, functions can take arguments. These arguments are always placed between parentheses `()`.

Let’s revisit the examples we used for function calls:

Remember this example of a function call?

```js
//       ↙ method
console.log("Hello There!"); //<-
//                 ↖ The string 'Hello There!' is
//                   the argument of console.log()
```

Now, let’s adapt `myFirstFunction` so that it takes one argument: `arg1`.

```js
let myFirstFunction = (arg1) => {
  //<-arg1 is inputted between the parentheses
  console.log(arg1); // arg1 can be used inside the scope of the function
  //            ↖   arg1 is "transferred" to be the argument of console.log()
}; //<-end of the scope of the function
```

When the function is called, it displays the output of `console.log(arg1)`.

```js
myFirstFunction("using my first arg"); // "using my first arg"
```

If you want to change what the function logs, instead of modifying `myFirstFunction`, you just need to modify the `argument` in the `function call`.

```js
myFirstFunction("another arg"); // "another arg"
myFirstFunction("and another one"); // "and another one"
myFirstFunction("and one more"); // "and one more"
```

#### More Arguments

We’ve seen how to add `one` argument to a function. Now, let’s learn how to add `two (or more)` arguments.

To add a second argument `arg2`, simply add a comma `,` after `arg1` and then include `arg2`.

```js
let myFirstFunction = (arg1, arg2) => {
  //<-arg1 and arg2 are inputted between the parentheses
  console.log(arg1, arg2);
  //            ↖   arg1 and arg2 are "transferred" to be the arguments of console.log()
};
// Now we call the function
myFirstFunction("first arg", "second arg");
// "first arg"
// "second arg"
```

For additional arguments, repeat the same process: add a comma `,` followed by the next argument.

> Note: You can name your arguments however you like. Just ensure you use the correct names inside the function’s scope.

#### Return Value

In addition to accepting arguments, functions can also `return` values.

Return values are the `outputs` that a function provides after completing its task.

Let’s adapt `myFirstFunction` so that it `returns` a value instead of just `logging` it.

```js
let myFirstFunction = (arg1) => {
  return arg1; // the function now returns the value of arg1
};
```

When the function is called, it returns the value of `arg1`:

```js
let result = myFirstFunction("using my first return");
console.log(result); // "using my first return"
```

If you want to change what the function `returns`, instead of modifying `myFirstFunction`, you just need to modify `the argument` in `the function call`.

```js
let anotherResult = myFirstFunction("another return");
console.log(anotherResult); // "another return"
```

#### **`Prompt Example`**:

- "Can you guide me through creating and using a JavaScript function that takes multiple arguments, starting from a basic function without arguments, then adding single and multiple arguments?"

### Instructions

#### Task 1:

You are the general’s aide responsible for transmitting communications to the other `RoboGuards`.

1. Create the `battleCry` Function:

- This function should take `one argument` and display it in the `console`.
- The battlefield is vast, so ensure that `the argument is uppercased` before displaying it.

2. Create the `secretOrders` Function:

- Sometimes, communications need to be given quietly.
- This function will do the `same` as `battleCry`, except it will `lowercase` the argument before sending it.

> Hint: Do you remember methods?

#### Task 2:

As the leader of the RoboGuard forces, you’re not just preparing for battle—you’re also forming dynamic duos of robots to work together on special missions.

1. Create the `duos` Function:

- This function will take `two arguments`, representing the **names** of **two robots**.
- It will `log them` together with a space, the word **and**, another space, and end the sentence with an **exclamation mark**.

> Example output: "robotOne and robotTwo!"

2. Create the `duosWork` Function:

- This function will take `three arguments`: the **names** of two robots and the **task** they will perform together.
- It will `log them` together in a sentence describing their task with the same formatting as below.

> Example output: "robotOne and robotTwo are saying hi!"

#### Task 3:

Rick’s robot knows its purpose. (Remember? "He passes butter.")

- Define the function `passButter` that returns the string "The butter."

**"Your hard work is paying off. The only limit to your impact is your imagination and commitment." – Tony Robbins**
