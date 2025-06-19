---
title: "Building a Contact Form in HTML and JavaScript 5.0"
post_status: "trash"
post_date: "2025-06-19"
post_excerpt: "A simple tutorial on building a contact form using HTML and vanilla JavaScript."
featured_image: "_images/devops.png"
taxonomy:
  category:
    - web-development
    - tutorials
    - best-practices
  post_tag:
    - HTML
    - JavaScript
    - cloud
custom_fields:
  author_name: "Melissa Patenaude"
---

Creating a custom contact form with HTML and JavaScript is a common beginner project that builds foundational frontend skills. In this post, we'll walk through a simple implementation and discuss how to enhance it for production use.

## 🔧 Step 1: HTML Structure

```html
<form id="contactForm">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required />
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required />
  
  <label for="message">Message:</label>
  <textarea id="message" name="message" required></textarea>
  
  <button type="submit">Send</button>
</form>
```
## ⚙️ Step 3: JavaScript to Handle Submission

```javascript
document.getElementById("contactForm").addEventListener("submit", function(e) {
  e.preventDefault();
  
  const data = {
    name: document.getElementById("name").value,
    email: document.getElementById("email").value,
    message: document.getElementById("message").value
  };

  console.log("Form submitted:", data);
  alert("Thanks for contacting us!");
});
```
