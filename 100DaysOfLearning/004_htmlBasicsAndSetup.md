# HTML Basics: Setup & First Code

## 1. Introduction to Web Development

When starting web development, the first essential step is setting up a proper coding environment and understanding HTML deeply. Your first practical milestone is building a simple **“Hello World”** webpage. This foundational step helps you understand how websites are structured.

---

## 2. From Theory to Practice

In the beginning, networking and web concepts are often taught theoretically. However, real understanding begins when you connect theory with hands-on coding.

Your initial goals:

* Set up the development environment
* Write and run your first HTML code

---

## 3. What is a Coding Environment?

A coding environment is where you:

* Write code
* Edit and format code
* Run and test code

A popular tool is **Visual Studio Code (VS Code)**, which makes coding efficient and organized.

---

## 4. Introduction to HTML

### What is HTML?

HTML stands for **HyperText Markup Language**.

Important clarification:

* HTML is **not a programming language**.
* It is a **markup language**.

### Purpose of HTML

HTML defines the **structure** of a webpage.
It labels different parts of a webpage such as:

* Headings
* Paragraphs
* Images
* Articles
* Lists
* Forms

Whenever you define *what something is* on a webpage, you use HTML.

---

## 5. Why HTML is Important

Think of HTML as the **skeleton of a website**.

* Without HTML, there is no structure.
* CSS adds design and styling.
* JavaScript adds logic and interactivity.
* But HTML is always the backbone.

---

## 6. Roles of HTML, CSS, and JavaScript

| Technology | Role                    |
| ---------- | ----------------------- |
| HTML       | Structure and labeling  |
| CSS        | Styling and appearance  |
| JavaScript | Logic and interactivity |

* HTML defines **what** elements exist.
* CSS defines **how they look**.
* JavaScript defines **how they behave**.

---

## 7. Understanding Website Structure

Every website contains:

* Banner
* Navigation bar
* Headings
* Paragraphs
* Images
* Buttons
* Articles

Each section is labeled using HTML tags.

HTML helps answer:

* Where is the text?
* Where is the image?
* Where is the button?
* What is an article?

---

## 8. Setting Up HTML Development

### Step 1: Install VS Code

Download and install Visual Studio Code.

### Step 2: Install Extensions

Recommended extensions:

1. **Prettier** – Automatically formats code.
2. **Live Server** – Runs your webpage in real-time in the browser.

---

## 9. First Project: Hello World

### Steps

1. Create a folder → `Project One`
2. Inside it, create a file → `index.html`
3. Type `!` in VS Code and press Enter to generate boilerplate code.

### Folder Structure

```
Project One/
   └── index.html
```

### Basic HTML Boilerplate

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Learn Full Stack Development">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello World</title>
</head>
<body>
    Hello World!
</body>
</html>
```

---

## 10. HTML Tags, Elements, and Attributes

### 1. Tags

Examples:

* `<h1>` – Heading
* `<p>` – Paragraph
* `<img>` – Image
* `<article>` – Article section

Tags label content.

### 2. Element

An element consists of:

* Opening tag
* Content
* Closing tag

Example:

```html
<h1>Hello World</h1>
```

### 3. Attributes

Attributes provide extra information.

Example:

```html
<img src="image.jpg" alt="description">
```

* `src` → Image source
* `alt` → Alternative text

---

## 11. Structure of an HTML Document

### 1. `<!DOCTYPE html>`

Declares HTML5 version.

### 2. `<html>`

Root element of the entire document.

### 3. `<head>`

Contains:

* Metadata
* Title
* SEO information
* Linked stylesheets

### 4. `<body>`

Contains visible webpage content.

---

## 12. Using Live Server

After enabling Live Server:

* Click “Go Live”
* Browser opens automatically
* Page refreshes automatically when you save changes

---

## 13. HTML Best Practices

1. Write clean, properly indented code.
2. Use meaningful semantic tags.
3. Write comments for clarity.

### HTML Comment Example

```html
<!-- This is a comment -->
```

Comments are not visible in the browser.

---

## 14. Learning Through Documentation

Reading documentation is essential.

Recommended resources:

* MDN Web Docs
* W3Schools
* TutorialsPoint

Documentation helps you:

* Understand tags deeply
* Learn new updates
* Build professional habits

---

## 15. What You Will Learn Next

Upcoming topics include:

* Formatting tags
* Lists and tables
* Inline vs block elements
* Emmet for faster coding
* Forms and media tags
* SEO basics
* Navigation structure
* Design patterns

---

# Concise Summary

* HTML is a markup language used to structure webpages.
* It defines what elements exist (headings, paragraphs, images, etc.).
* HTML is the backbone; CSS styles it, JavaScript adds behavior.
* A proper setup includes VS Code, Prettier, and Live Server.
* Every HTML document has `doctype`, `html`, `head`, and `body`.
* Tags define structure, elements combine tags and content, attributes add extra information.
* Clean code, proper indentation, and documentation reading are essential for growth.

---

### Core Takeaway

Mastering HTML basics and environment setup is the first and most important step in becoming a professional web developer. A strong foundation makes advanced learning significantly easier.
