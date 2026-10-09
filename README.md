# Review Session — From How the Web Works to JavaScript

### Exercises covering everything so far

Take your time. These are all things you've already learned, so if one feels hard, look back at the lesson PDF for that topic. If you get stuck, write down exactly where, and we'll go through it together.

Work in one folder called `review-exercises` with sub-folders `part-1` to `part-6`. Push everything to your own GitHub when done.

---

## Part 1 — How the Web Works (no code)

**1.1 Trace a URL.** Pick any website. Write 4-5 steps describing what happens from the moment you press Enter until the page appears. Use these words: browser, server, request, response.

**1.2 Frontend or backend?** For each item, write "frontend", "backend" or "database":

- the buttons you click
- the list of all registered users
- the code that checks your password
- the colors of the page

**1.3 Explain it simply.** In 3 sentences, explain the difference between HTML, CSS and JavaScript to a friend who has never coded.

---

## Part 2 — HTML

**2.1 Build a page skeleton.** Create `index.html` with the full skeleton: `<!DOCTYPE html>`, `lang`, `charset`, `viewport`, `title`.

**2.2 Semantic structure.** Inside it, build a page about a business of your choice using: `header`, `nav` (with 3 links), `main` (with 2 `section`s), and `footer`. Do not use `<div>` anywhere.

**2.3 Image and form.** Add one image with proper `alt` text, and a small contact form with 2 inputs and a textarea, each with a properly connected `<label>` (matching `for` and `id`), plus a submit `<button>`.

---

## Part 3 — CSS

**3.1 Connect and style.** Create `styles.css`, link it to your page, and set a `background-color`, a `font-family` and a `line-height` on `body`. Add `box-sizing: border-box` for all elements.

**3.2 CSS variables.** In `:root`, define 3 color variables and 2 spacing variables. Use them to style your buttons and headings.

**3.3 Layout.** Turn your `nav` into a row with Flexbox. Then put 3 cards in a Grid with 3 columns on desktop and 1 column on mobile (use one media query). Test in DevTools at 375px and at desktop width.

---

## Part 4 — JavaScript: Variables, Types, Operators

Do these in a file called `part-4.js` and check the results in the Console.

**4.1** Create variables for a product name, a price and a quantity. Calculate the total and print it with a template literal, like: `Total for 3 Haircut: 75`.

**4.2** Predict each result before running it, then check. Write your prediction in a comment first:

```jsx
console.log(5 === "5");
console.log(10 > 3 && 2 > 5);
console.log(typeof "42");
console.log(Number("42") + 8);
```

**4.3** Fix this code. A price was stored as text, so the total is wrong:

```jsx
const price = "25";
const fee = 10;
console.log(price + fee); // we want 35
```

Explain in one sentence why it was wrong.

---

## Part 5 — JavaScript: Conditions, Functions, Arrays, Objects

Do these in `part-5.js`.

**5.1 Condition.** Write an `if / else if / else` that prints a message based on a ticket price: under 18 pays 5, 18 to 60 pays 10, over 60 pays 7.

**5.2 Function.** Write a function `calculateTotal(price, quantity)` that returns the total. Call it 3 times with different numbers and print each result.

**5.3 Array and object.** Create an array of 3 services, each an object with `name` and `price`. Then:

- print the name of the second service
- add a fourth service with `.push()`
- print how many services there are with `.length`

**5.4 Put it together.** Write a function `checkSlot(slot)` that uses an array of booked times and `.includes()`. It returns "Available" or "Already booked". Test it with 2 slots.

---

## Part 6 — DOM and Events (bonus)

Do these on your HTML page from Part 2.

**6.1 Change the page.** Use `querySelector` to select your main heading and change its text with `textContent`.

**6.2 Click toggle.** Add a button. When it is clicked, toggle a class that changes the background color of one section.

---

## Final Challenge — Mini Services Page

Combine everything into one small page:

1. Semantic HTML (header, nav, main, footer).
2. CSS with variables and a Grid of cards.
3. A JavaScript array of 3 service objects.
4. JavaScript that creates one card per service and adds it to the page.
5. A button that toggles a highlight on all the cards.

It does not need to be beautiful. It needs to work, be readable, and use only things we have learned.

---

## Submission

Push everything to your own GitHub with clear commit messages. We'll review it together in the next session.

## A Note on AI

You can use AI to understand an error or explain a concept you forgot. Do not use it to write the answers. If you cannot explain a line of your own code, rewrite it until you can.

---

**MilcodeUni · milcodeuni.tech**# review-exercises-mock-exam-bm
