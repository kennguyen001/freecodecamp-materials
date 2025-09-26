# Lab 03: Build A Recipe Page

**Objective:** Fulfill the user stories below and get all the tests to pass to complete the lab.

---

## 🧾 User Stories

1. You should have a `<!DOCTYPE html>` declaration.
2. You should have an `<html>` element with `lang="en"`.
3. You should have a `<head>` element containing:
   - a `<title>` element with the name of your recipe
   - a `<meta>` element with a `charset` attribute set to `UTF-8`
4. You should have a `<body>` element.
5. You should have an `<h1>` element with the name of your recipe.
6. You should have a `<p>` element that introduces the recipe below the `<h1>`.
7. You should have one `<h2>` element with the text **Ingredients** for the ingredients section.
8. You should have an unordered list (`<ul>`) with at least four list items (`<li>`) that lists your ingredients below the first `<h2>`.
9. You should have a second `<h2>` element with the text **Instructions** for the instructions section.
10. You should have an ordered list (`<ol>`) with at least four list items (`<li>`) that lists the recipe steps in order, below the second `<h2>`.
11. You should have one `<img>` element with:
    - a `src` attribute set to a valid image URL (e.g., `https://cdn.freecodecamp.org/curriculum/labs/recipe.jpg`)
    - an `alt` attribute describing the image

---

## ✅ Solution

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Strawberry Banana Smoothie</title>
  </head>
  <body>
    <h1>Strawberry Banana Smoothie</h1>
    <p>
      This quick and healthy smoothie is packed with fresh fruit and makes the
      perfect breakfast or afternoon pick‑me‑up.
    </p>

    <img
      src="https://cdn.freecodecamp.org/curriculum/labs/recipe.jpg"
      alt="A glass of strawberry banana smoothie with fresh fruit on the side."
    />

    <h2>Ingredients</h2>
    <ul>
      <li>1 ripe banana</li>
      <li>1 cup fresh or frozen strawberries</li>
      <li>1/2 cup plain yogurt</li>
      <li>1/2 cup milk (dairy or non‑dairy)</li>
      <li>1 tablespoon honey or maple syrup (optional)</li>
    </ul>

    <h2>Instructions</h2>
    <ol>
      <li>Peel the banana and add it to a blender.</li>
      <li>Add the strawberries, yogurt, and milk.</li>
      <li>Blend until smooth and creamy.</li>
      <li>Taste and add honey or maple syrup if you’d like extra sweetness.</li>
      <li>Pour into a glass and enjoy immediately.</li>
    </ol>
  </body>
</html>
```
