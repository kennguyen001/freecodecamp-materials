# Lab 04: Build A Travel Agency Page

**Objective:** Build an app that is functionally similar to the example project. Try not to copy the example project, give it your own personal style.

---

## 🧾 User Stories

1. You should have a DOCTYPE declaration.
2. You should have an `html` element with `lang` set to `en`.
3. You should have a `head` element containing a `meta` void element with `charset` set to `utf-8` and a `title` with the text **Travel Agency Page**.
4. You should have a `meta` tag in your `head` element that contains a short description of your website for SEO.
5. You should have an `h1` element to present your travel destinations.
6. You should have a paragraph below the `h1` element introducing the travel opportunities.
7. You should have an `h2` element with the text **Packages**.
8. You should have a `p` element introducing briefly the various packages.
9. You should have an unordered list element with two list items.
   - The two list items should have the text **Group Travels** and **Private Tours**, respectively.
   - The text of each list item should be enclosed by an anchor element.
10. You should have an `h2` element with the text **Top Itineraries**.
11. You should have at least three `figure` elements, each containing an anchor element and a `figcaption` element.
12. The three anchor elements should have an `img` element with an appropriate `alt` attribute and a `src` attribute set to a valid image.
    - You can use:
      - `https://cdn.freecodecamp.org/curriculum/labs/colosseo.jpg`
      - `https://cdn.freecodecamp.org/curriculum/labs/alps.jpg`
      - `https://cdn.freecodecamp.org/curriculum/labs/sea.jpg`
13. All your five anchor elements should have an `href` attribute with the value of `https://www.freecodecamp.org/learn` and a `target` attribute with the value of `_blank`.

---

## ✅ Solution

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Travel Agency Page</title>
  </head>
  <body>
    <h1>Discover Vietnam</h1>
    <p>
      From the lantern-lit alleys of Hoi An to the misty peaks of Sa Pa and the
      emerald waters of Ha Long Bay, choose from guided tours and immersive
      excursions to experience Vietnam’s culture, cuisine, and nature.
    </p>

    <h2>Packages</h2>
    <p>
      Whether you travel solo, with friends, or as a family, pick from flexible
      group departures or tailor-made private itineraries across cities,
      heritage towns, and coastal retreats.
    </p>
    <ul>
      <li>
        <a href="https://www.freecodecamp.org/learn" target="_blank"
          >Group Travels</a
        >
      </li>
      <li>
        <a href="https://www.freecodecamp.org/learn" target="_blank"
          >Private Tours</a
        >
      </li>
    </ul>

    <h2>Top Itineraries</h2>

    <figure>
      <a href="https://www.freecodecamp.org/learn" target="_blank">
        <img
          src="https://cdn.freecodecamp.org/curriculum/labs/colosseo.jpg"
          alt="Old Quarter streets and historic architecture on a city heritage walk in Hanoi"
        />
      </a>
      <figcaption>
        Hanoi Heritage Walk — explore the Old Quarter, French Quarter, and
        lakeside temples with local storytellers.
      </figcaption>
    </figure>

    <figure>
      <a href="https://www.freecodecamp.org/learn" target="_blank">
        <img
          src="https://cdn.freecodecamp.org/curriculum/labs/alps.jpg"
          alt="Terraced hills and mountain scenery reminiscent of Sa Pa's highlands"
        />
      </a>
      <figcaption>
        Sa Pa Highlands Trek — terraced valleys, hill-tribe villages, and
        panoramic mountain viewpoints.
      </figcaption>
    </figure>

    <figure>
      <a href="https://www.freecodecamp.org/learn" target="_blank">
        <img
          src="https://cdn.freecodecamp.org/curriculum/labs/sea.jpg"
          alt="Emerald sea and limestone formations evocative of Ha Long Bay"
        />
      </a>
      <figcaption>
        Ha Long Bay Cruise — limestone karsts, hidden caves, and sunset sails on
        emerald waters.
      </figcaption>
    </figure>
  </body>
</html>
```
