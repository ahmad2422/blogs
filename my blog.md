---
title: "Understanding Variables in JavaScript"
slug: "variables-in-js"
date: "2025-06-01"
status: publish
categories:
  - JavaScript
tags:
  - variables
  - let
  - const
  - beginners
---

In JavaScript, **variables** are used to store data that you can reuse and change in your program. The most commonly used keywords to declare variables are `let`, `const`, and `var`.

## 🧱 Declaring Variables with `let`

The `let` keyword allows you to create a variable that **can be changed** later.

```javascript
let name = "Alice";
console.log(name); // Output: Alice

name = "Bob";
console.log(name); // Output: Bob
```

You can see above that we first set `name` to `"Alice"` and later changed it to `"Bob"`.

## 🔒 Using `const` for Constants

Use `const` when you **don't want the value to change**.

```javascript
const pi = 3.14159;
console.log(pi); // Output: 3.14159

// This will cause an error:
// pi = 3.14;
```

Once a `const` variable is set, you **cannot assign a new value** to it.

## ⚠️ What About `var`?

The `var` keyword is the **old way** of declaring variables and should generally be avoided because it doesn't follow block scope.

```javascript
var message = "Hello";
console.log(message);
```

In most cases, it's better to use `let` or `const` to avoid confusion.

## 💡 Quick Summary

- Use `let` when the value may change (e.g., `let score = 0;`)
- Use `const` when the value should stay the same (e.g., `const baseURL = "https://api.example.com"`)
- Avoid `var` unless you have a specific reason

## 📌 Example: A Small Program

Here’s a full example that combines all of the above:

```javascript
const siteName = "LearnJS";
let visitors = 10;

console.log(`Welcome to ${siteName}!`);
console.log(`You have ${visitors} visitors today.`);

visitors = 15;
console.log(`Updated visitors: ${visitors}`);
```

Notice how we use a template string with backticks (`` ` ``) to insert `siteName` and `visitors` into a message.

---

Now you understand how to use `let`, `const`, and `var` in JavaScript. Start writing your own variables and play around with them!
