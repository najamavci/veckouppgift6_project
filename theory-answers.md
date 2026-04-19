# Theory Answers - in English

These answers are based on the uploaded assignment and should be adapted into your own words before submission.

## 1a. What kinds of HTML elements can you see on the W3Schools page?
Common examples you can usually find on a W3Schools page:
- headings (`h1`, `h2`, `h3`)
- paragraphs (`p`)
- links (`a`)
- images (`img`)
- lists (`ul`, `ol`, `li`)
- buttons (`button`)
- navigation/menu elements
- sections and containers (`div`, `section`)
- code examples (`pre`, `code`)
- tables (`table`, `tr`, `td`)
- forms or input fields on some pages (`input`)

## 1b. What kinds of elements exist on the Wikipedia page about Thutmose II?
Typical examples on a Wikipedia page:
- page title (`h1`)
- paragraphs (`p`)
- links (`a`)
- images (`img`)
- captions
- infobox/table-like content
- headings and subheadings (`h2`, `h3`)
- lists (`ul`, `li`)
- references/footnotes
- navigation elements

## 1c. Parsons problem
This part must be solved in the linked exercise itself. The task is to drag the mixed code lines into the correct order so they match the screenshot.

## 1d. Find errors in the HTML
Original code:

```html
<main>

<section>

<h1> Find the error

<p> This is an example of an HTML file. It contains several errors.

<img Let's show a nice image. />

<p> Can you find them all? </p>

</p>

</main>
```

### Errors
1. The `<h1>` tag is missing its closing tag `</h1>`.
2. The first `<p>` tag is missing its closing tag before the next content starts.
3. The `<img>` tag is written incorrectly. It needs attributes such as `src` and `alt`.
4. There is an extra closing `</p>` near the end.
5. The `<section>` tag is never closed with `</section>`.
6. The image line contains text inside the tag in an invalid way.

### Corrected version
```html
<main>
  <section>
    <h1>Find the error</h1>
    <p>This is an example of an HTML file. It contains several errors.</p>
    <img src="image.jpg" alt="A nice example image">
    <p>Can you find them all?</p>
  </section>
</main>
```

## What else is required?
Besides building the pages, the assignment also requires:
- at least one code review in a group
- submission through Google Forms
- a public GitHub repository
- completing the HTML course on Codecademy
- reading the W3Schools HTML tutorial and HTML element reference

