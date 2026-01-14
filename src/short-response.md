# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: HTML Structure

What is the difference between the `<head>` and `<body>` sections of an HTML document? What kind of content goes in each? 

**Your Answer:**
In HTML, the purpose of the `<head>` tag is to contain all the meta links as well as to provide the `<title>` of the page. The `<body>` tag is where all the website content will go. You can think of it as the entirity of a blank page where you will do your creative work.

## Question 2: Semantic HTML

Why should we use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything?

This is important to do because it provides structure to improve organization to our website. This creates separation of concerns, as every tag serves a purpose. 

It also serves for accessability purposes. It's easier for screen readers to identify the semantic tags and fascilitate webpage navigation.
ORGANIZATION, ACCESABILITY FOR IMPAIRED PEOPLE: EASIER FOR THE READER.

## Question 3: CSS Selectors

Given the following HTML:

```html
<ul>
  <li class="vegetable">Carrots</li>
  <li class="vegetable">Broccoli</li>
  <li class="fruit" id="favorite">Mango</li>
</ul>
```

Write THREE different CSS rules:

1. One that makes ALL list items have a `yellow` background
2. One that makes only the vegetables have `green` text color
3. One that makes only the Mango `bold`

**Your Answer:**

```css
ul {
  background-color: yellow;
}

.vegetable {
  color: green;
}

#favorite {
  font-weight: bold;
}
```

## Question 4: The Box Model

In your own words, explain the four parts of the CSS box model (content, padding, border, margin). What is the purpose of each part?

**Your Answer:**

## Question 5: Box-Sizing

What problem does `box-sizing: border-box` solve? Why do we include it in a CSS reset at the top of our CSS files?

**Your Answer:**

## Question 6: Display Property

What is the difference between `display: block`, `display: inline`, and `display: inline-block`? Give an example of when you might use `inline-block`.

**Your Answer:**
