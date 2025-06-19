---
title: "Building a Contact Form in HTML and JavaScript"
slug: "contact-form-html-js"
author: "Melissa Patenaude"
categories: ["Web Development", "Tutorials"]
tags: ["HTML", "JavaScript", "Forms", "Frontend"]
thumbnail: "https://stg-aembit-statging.kinsta.cloud/wp-content/uploads/2025/05/ChatGPT-Image-May-8-2025-02_59_42-PM.png"
status: "publish"
date: "2025-06-19 10:30:00"
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

## ⚙️ Step 2: JavaScript to Handle Submission

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
