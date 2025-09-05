---

title: "Test variables"
post_status: draft

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
