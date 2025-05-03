## Play with Variables

> Mindful AI Mode

### Context

If things ever feel overwhelming, take a moment to connect with your peers. Collaborating can help you think, share ideas, and move forward together.

> Keep Going!

### AI-Powered Learning Techniques

**Clarification Technique:**

This type of prompt encourages the AI to explain a concept in detail, helping you gain a deeper understanding.

> Look for examples across the subject 😀

## Concepts

### Escape Characters

**Quote delimiters** can be tricky to handle.

Since they are used to delimit text, you need a way to include them in your text without breaking the syntax.

For example, if you want to include a `'` _(single quote)_ in your text but are using single quotes as delimiters:

```js
console.log('I keep trying, I can't give up!');
// Too bad! A single quote ruined the string. Get it?
```

The `\` _(backslash)_ is used to escape such characters:

Whenever there is a _special_ character in your string, placing a `\` in front of it will **escape** it. This tells JavaScript to treat the following character as a literal, rather than as a delimiter or a special character.

```js
console.log("I keep trying, I can\'t give up!");

// Output: I keep trying, I can't give up!
```

#### **`Prompt Example`**:

"As a beginner, how do I include special characters in a string in JavaScript? Provide simple examples too."

### Assign and Reassign

The `let` keyword is used to declare new variables.

> Note: You cannot have multiple variables with the same identifier, as JavaScript wouldn't know which one to reference.

If you redeclare a variable, it will cause an error!

However, you can use the `=` (assignment operator) to change its value.

> Note: Variables declared with `const` cannot be reassigned. This ensures the value remains constant, protecting your code from errors. However, you can always use `let` if reassignment is needed.

> Also, you might encounter older code that uses `var`. Since 2015, we have been moving away from `var` due to its problematic behavior. Avoid using it! If you see code with `var`, try to find a more recent example, as that code is likely outdated.

#### **`Prompt Example`**:

- "As a beginner, what is the difference between `let` and `const` in JavaScript?"
- "As a beginner, how do I reassign a value to an already declared variable in JavaScript?"

### Instructions

#### Task 1:

- Create a `escapeFromDelimiters` variable that includes all three types of quotes _(`` ` ``, `"`, and `'`)_.

- Create a `escapeTheEscape` variable that includes a backslash _(`\`)_.

#### Task 2:

- The variable `power` has already been declared and will be used during the tests.

- Reassign the `power` variable to the string value `levelMax` without redeclaring it.

---

> “How did I escape? With difficulty. How did I plan this moment? With pleasure.” \
> ― Alexandre Dumas, *The Count of Monte Cristo*
