# Lab 05: Build A Video Compilation Page

**Objective:** Build an app that is functionally similar to the example project. Try not to copy the example project, give it your own personal style.

---

## 🧾 User Stories

1. You should have a `main` element as the only child of the `body` element.
2. You should have an `h1` element with the topic of your page.
3. You should have a paragraph introducing the topic of your page below your `h1` element.
4. You should have three `section` elements below your first paragraph.
5. Each `section` should contain an `h2` element, a paragraph, and an `iframe` element, in this order.
6. The three `iframe` elements should have a `src` attribute set to a valid video.
7. Each `iframe` element should also have a `title` attribute to describe the embedded content, and a `height` attribute and a `width` attribute to set the element to a proper size.

---

## ✅ Solution

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Video Compilation Page</title>
  </head>
  <body>
    <main>
      <h1>Web Development Tutorials</h1>
      <p>
        Learn the essentials of front-end web development with these
        beginner-friendly video tutorials. Explore HTML, CSS, and JavaScript to
        start building your own interactive websites.
      </p>

      <section>
        <h2>HTML Basics</h2>
        <p>
          Understand the structure of web pages using HTML. This video
          introduces elements, attributes, and how to create a solid foundation
          for your site.
        </p>
        <iframe
          src="https://www.youtube.com/embed/pQN-pnXPaVg"
          title="HTML Full Course for Beginners"
          width="560"
          height="315"
          allowfullscreen
        >
        </iframe>
      </section>

      <section>
        <h2>CSS for Beginners</h2>
        <p>
          Learn how to style your web pages with CSS. This tutorial covers
          colors, fonts, layouts, and responsive design techniques.
        </p>
        <iframe
          src="https://www.youtube.com/embed/1Rs2ND1ryYc"
          title="CSS Full Course for Beginners"
          width="560"
          height="315"
          allowfullscreen
        >
        </iframe>
      </section>

      <section>
        <h2>JavaScript Essentials</h2>
        <p>
          Add interactivity to your websites with JavaScript. This video
          explains variables, functions, events, and DOM manipulation.
        </p>
        <iframe
          src="https://www.youtube.com/embed/W6NZfCO5SIk"
          title="JavaScript Full Course for Beginners"
          width="560"
          height="315"
          allowfullscreen
        >
        </iframe>
      </section>
    </main>
  </body>
</html>
```
