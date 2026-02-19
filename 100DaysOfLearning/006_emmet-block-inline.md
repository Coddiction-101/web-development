# Emmet for Faster HTML + Block & Inline Elements – Structured Reference Notes

---

# 1. Introduction

HTML is the foundation of web development. Writing HTML efficiently and understanding how elements behave (block vs inline) is essential for building clean and structured webpages.

Two key skills covered here:

* Writing HTML quickly using **Emmet**
* Understanding **block and inline elements**

Together, they improve both speed and clarity in development.

---

# 2. Writing HTML Faster with Emmet

## What is Emmet?

Emmet is a built-in productivity tool in **VS Code** and many modern editors.

It allows you to:

* Write short abbreviations
* Automatically expand them into full HTML structures
* Reduce repetitive typing
* Improve coding speed significantly

---

## Core Emmet Operators

| Symbol | Purpose             |
| ------ | ------------------- |
| `>`    | Child (nesting)     |
| `+`    | Sibling             |
| `*`    | Multiplication      |
| `{}`   | Insert text content |
| `()`   | Grouping            |
| `#`    | ID                  |
| `.`    | Class               |

---

## Practical Examples

### 1. Nesting (Parent → Child)

```
ul>li*3
```

Expands to:

```html
<ul>
  <li></li>
  <li></li>
  <li></li>
</ul>
```

---

### 2. Siblings

```
article+section
```

Creates:

```html
<article></article>
<section></section>
```

Both are on the same level.

---

### 3. Adding Text Content

```
p{This is my paragraph}
```

Creates:

```html
<p>This is my paragraph</p>
```

---

### 4. Grouping and Repetition

```
(tr>td*5)*2
```

Creates:

* 2 table rows
* Each row with 5 cells

---

### 5. IDs and Classes

```
p#para1
```

```html
<p id="para1"></p>
```

```
div.container
```

```html
<div class="container"></div>
```

Multiple classes:

```
div.lion.dog.cat
```

```html
<div class="lion dog cat"></div>
```

---

# 3. The `<div>` Tag – Generic Container

## What is Div?

`<div>` is a non-semantic container element.

It:

* Groups elements together
* Helps with layout
* Is heavily used for styling and structure

Example:

```html
<div class="container">
  <article>
    <p>Hello</p>
  </article>
</div>
```

The container div wraps everything inside it.

---

## Semantic vs Non-Semantic

| Type         | Examples                         | Meaning             |
| ------------ | -------------------------------- | ------------------- |
| Semantic     | `<article>`, `<nav>`, `<header>` | Describe purpose    |
| Non-Semantic | `<div>`, `<span>`                | No inherent meaning |

Use semantic tags when meaning matters. Use div for grouping/layout.

---

# 4. Block vs Inline Elements

Understanding this is critical.

---

# Block Elements

## Characteristics

* Start on a new line
* Take full available width
* Stack vertically

## Examples

* `<div>`
* `<p>`
* `<ul>`
* `<ol>`
* `<li>`
* `<section>`
* `<article>`
* `<h1>` to `<h6>`

Example:

```html
<div style="background-color:aqua;">
  This is a block element
</div>
```

The background stretches across the entire width.

---

# Inline Elements

## Characteristics

* Do not start on a new line
* Take only required width
* Sit beside other elements

## Examples

* `<span>`
* `<a>`
* `<b>`
* `<i>`
* `<img>`

Example:

```html
<span style="background-color:yellow;">
  This is inline
</span>
```

Background only covers text width.

---

# Changing Element Behavior with CSS

You can modify behavior:

```css
display: inline;
display: block;
```

* Convert block → inline
* Convert inline → block

This gives design flexibility.

---

# 5. Lists Using Emmet

### Unordered List

```
ul>li*7
```

Creates 7 list items.

---

### Ordered List with Paragraphs

```
ol>li>p*3
```

Creates:

* Ordered list
* Each item contains paragraphs

---

### Navbar Structure

```
nav>ul>li>a*4
```

Creates:

```html
<nav>
  <ul>
    <li><a href="#">Link</a></li>
    <li><a href="#">Link</a></li>
    <li><a href="#">Link</a></li>
    <li><a href="#">Link</a></li>
  </ul>
</nav>
```

Perfect for navigation menus.

---

## Vertical vs Horizontal Lists

By default:

* Lists are vertical.

To make horizontal:

```css
li {
  display: inline;
}
```

Common in navigation bars.

---

# 6. Anchor Tags (Hyperlinks)

## Basic Link

```html
<a href="https://example.com">Visit</a>
```

---

## Email Link

```html
<a href="mailto:someone@email.com">Send Email</a>
```

---

## Phone Link

```html
<a href="tel:1001">Call</a>
```

---

## Internal Navigation (Bookmarks)

Use ID:

```html
<h2 id="section1">Section 1</h2>
<a href="#section1">Go to Section 1</a>
```

---

# 7. ID vs Class

## ID

* Must be unique
* Used for specific targeting

```html
<p id="para1">Text</p>
```

---

## Class

* Can be shared
* Used for styling multiple elements

```html
<p class="info">Paragraph 1</p>
<p class="info">Paragraph 2</p>
```

---

# 8. Practice Strategy

To master these concepts:

* Experiment with Emmet shortcuts daily
* Test block vs inline behavior
* Build small layouts
* Change display properties
* Inspect websites using browser developer tools

Practice builds coding intuition.

---

# Concise Summary

* Emmet speeds up HTML development using abbreviations.
* Key operators: `>`, `+`, `*`, `{}`, `.`, `#`, `()`.
* `<div>` is a non-semantic container used for layout.
* Block elements take full width and start on new lines.
* Inline elements take only necessary width.
* CSS `display` property can change element behavior.
* IDs are unique; classes can be shared.
* Emmet is essential for professional-level coding speed.

---

# Core Takeaway

Efficiency in HTML comes from two skills:

1. Writing code fast (Emmet).
2. Understanding how elements behave (block vs inline).

When you combine both, your HTML becomes faster, cleaner, and more structured—laying a strong foundation for CSS, layout systems, and responsive design.

