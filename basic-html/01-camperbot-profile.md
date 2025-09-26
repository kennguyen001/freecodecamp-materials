# Lab 01 – Debug Camperbot's Profile Page

**Objective:** Fix Camperbot's profile page by correcting invalid HTML tags.

## 🧾 User Stories

1. Replace the non-existent `<heading2>` with a valid `<h2>` element.
2. Replace `<pp>` with proper `<p>` tags for paragraphs.
3. Fix the syntax error in the `<h3>` subheading.

---

## 🚦 Starting Code

```html
<h1>Hello from Camperbot!</h1>

<heading2>About</heading2>

<pp>My name is Camperbot and I love learning new things.</pp>

<h3>
  Background and Interests
  <h3 />
  <pp>I enjoy solving puzzles.</pp>
</h3>
```

---

## ✅ Solution

```html
<h1>Hello from Camperbot!</h1>

<h2>About</h2>

<p>My name is Camperbot and I love learning new things.</p>

<h3>Background and Interests</h3>
<p>I enjoy solving puzzles.</p>
```
