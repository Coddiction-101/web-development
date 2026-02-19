# HTML Tags: Complete Guide – Structured Reference Notes (English)

## 1. Foundation of HTML Tags

HTML (HyperText Markup Language) is the core language of web development.
At the center of HTML are **tags**—the building blocks that give a webpage:

* Structure
* Meaning
* Formatting

Tags organize content and define how different parts of a webpage relate to each other.

---

# 2. What is an HTML Tag?

An HTML tag is a markup keyword used to define and structure web content.

You use tags to:

* Mark text as a heading
* Create paragraphs
* Insert images or videos
* Build lists and tables
* Define navigation and layout sections

### Basic Tag Structure

```html
<tagname> Content </tagname>
```

### Self-Closing Tags

Some tags do not require a closing tag:

```html
<br>
<img>
```

---

# 3. Tag vs Element

Understanding this distinction is essential.

| Term    | Meaning                                   |
| ------- | ----------------------------------------- |
| Tag     | The markup keyword itself (`<p>`, `<h1>`) |
| Element | Opening tag + content + closing tag       |

Example:

```html
<h1>Heading Text</h1>
```

* `<h1>` → Opening tag
* `Heading Text` → Content
* `</h1>` → Closing tag
* Entire line → Element

---

# 4. Categories of HTML Tags

HTML tags are broadly divided into:

1. **Semantic Tags** – Provide meaning
2. **Formatting Tags** – Change visual appearance
3. **Structural Tags** – Define layout structure

---

# 5. Semantic Tags (Meaning-Based)

These tags define the importance and purpose of content.

## Headings (`<h1>` – `<h6>`)

Used for titles and subheadings.

```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Section Heading</h3>
```

* `<h1>` is the most important.
* Only `<h1>` to `<h6>` are valid.

---

## Paragraph (`<p>`)

Used for normal text blocks.

```html
<p>This is a paragraph.</p>
```

---

## Anchor Tag (`<a>`)

Used to create hyperlinks.

```html
<a href="https://www.google.com">Visit Google</a>
<a href="mailto:example@email.com">Send Email</a>
<a href="tel:+911234567890">Call Now</a>
```

Key attribute:

* `href` → Destination link

---

## Lists

### Unordered List (`<ul>`)

Used when order does not matter.

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

### Ordered List (`<ol>`)

Used when sequence matters.

```html
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```

### List Item (`<li>`)

Defines each item inside lists.

---

## Table (`<table>`)

Used for tabular data.

```html
<table>
  <tr>
    <td>ID</td>
    <td>Name</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Ram</td>
  </tr>
</table>
```

* `<tr>` → Table row
* `<td>` → Table data cell

---

## Image (`<img>`)

Used to display images.

```html
<img src="image.jpg" alt="Description">
```

Important attributes:

* `src` → Image source
* `alt` → Alternative text (important for accessibility)

---

# 6. Formatting Tags

These tags affect visual appearance.

## Bold and Strong

```html
<strong>Important text</strong>
<b>Bold text</b>
```

* `<strong>` adds semantic importance.
* `<b>` is only visual.

---

## Italic and Emphasis

```html
<em>Emphasized text</em>
<i>Italic text</i>
```

* `<em>` adds meaning.
* `<i>` changes appearance only.

---

## Underline and Strike

```html
<u>Underlined text</u>
<s>Strikethrough text</s>
```

---

## Superscript and Subscript

Used in math and chemical formulas.

```html
2<sup>5</sup>
O<sub>2</sub>
```

---

## Preformatted and Code

```html
<pre>
Line 1
  Line 2
</pre>

<code>
console.log("Hello");
</code>
```

* `<pre>` preserves spacing.
* `<code>` displays code snippets.

---

## Line Break (`<br>`)

```html
Name: John<br>City: Delhi
```

Adds a new line.

---

# 7. Structural Tags (Layout)

These define the page structure.

## Core Document Structure

```html
<html>
<head></head>
<body></body>
</html>
```

* `<html>` → Root element
* `<head>` → Metadata
* `<body>` → Visible content

---

## Modern Layout Tags

```html
<header>Website Title</header>
<nav>Navigation Links</nav>

<main>
  <article>
    <section>Main Content</section>
  </article>
  <aside>Sidebar Content</aside>
</main>

<footer>Footer Info</footer>
```

Purpose:

* `<header>` → Top section
* `<nav>` → Navigation menu
* `<main>` → Primary content
* `<article>` → Independent content
* `<section>` → Content grouping
* `<aside>` → Sidebar
* `<footer>` → Bottom section

These improve:

* SEO
* Accessibility
* Screen reader support

---

# 8. HTML Attributes

Attributes provide extra functionality to tags.

Common attributes:

* `href` → Links
* `src` → Images
* `alt` → Accessibility text
* `id` → Unique identifier
* `class` → Styling group
* `style` → Inline CSS

Example:

```html
<h1 style="color: blue;">Main Heading</h1>
<img src="image.jpg" alt="Sample Image">
```

---

# 9. Emmet Shortcuts (Productivity)

Using VS Code with Emmet speeds up coding.

Examples:

```
ul>li*3
```

Creates three list items.

```
table>tr*3>td*3
```

Creates a 3x3 table.

---

# 10. Real-World Importance of Proper Tags

Correct tag usage improves:

* SEO ranking
* Accessibility
* Screen reader interpretation
* Code readability
* Maintainability

Large websites use the same fundamental tags:
`h1`, `p`, `ul`, `li`, `a`, `article`, etc.

---

# 11. Best Practices

1. Use semantic tags instead of generic ones.
2. Avoid excessive inline styling.
3. Maintain proper heading hierarchy.
4. Always use `alt` for images.
5. Keep code clean and indented.

---

# Concise Summary

* HTML tags define structure, meaning, and formatting.
* Tags + content = Element.
* Three main types: semantic, formatting, structural.
* Semantic tags improve SEO and accessibility.
* Attributes add functionality (`href`, `src`, `alt`, `id`, `class`).
* Modern layout tags (`header`, `nav`, `main`, `article`, `footer`) create meaningful page structure.
* Practice and documentation reading are essential for mastery.

---

## Core Takeaway

HTML tags are the building blocks of the web.
Mastering their purpose, structure, and correct usage forms a strong foundation for advanced topics like CSS, JavaScript, and full-stack development.
