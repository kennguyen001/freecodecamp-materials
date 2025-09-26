# Lab 02 – Debug a Pet Adoption Page

**Objective:** Fix Sally’s pet adoption page by correcting invalid HTML attributes and tags.

---

## 🧾 User Stories

1. Fix the `<img>` element:
   - Replace the `href` attribute with the correct `src` attribute.
   - Replace the `att` attribute with the correct `alt` attribute.
   - Remove the invalid `</img>` closing tag (since `<img>` is a void element).
2. Fix the `<a>` elements:
   - Replace both `src` attributes with the correct `href` attribute.

---

## 🚦 Starting Code

```html
<h1>Welcome XYZ Pet Adoption!</h1>
<p>Consider adopting a pet today. We have cats, dogs, rabbits and more.</p>

<h2>See our cats!</h2>
<img href="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" att="Two tabby kittens sleeping together on a couch."></img>

<h2>Adopt a cat!</h2>
<a src="/cats">Visit cats page</a>

<h2>Adopt a dog!</h2>
<a src="/dogs">Visit dogs page</a>
```

---

## ✅ Solution

```html
<h1>Welcome XYZ Pet Adoption!</h1>
<p>Consider adopting a pet today. We have cats, dogs, rabbits and more.</p>

<h2>See our cats!</h2>
<img
  src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg"
  alt="Two tabby kittens sleeping together on a couch."
/>

<h2>Adopt a cat!</h2>
<a href="/cats">Visit cats page</a>

<h2>Adopt a dog!</h2>
<a href="/dogs">Visit dogs page</a>
```
