# 🌐 HTML Mastery

> **Learning HTML from fundamentals to professional level — without copy-paste coding.**

![HTML](https://img.shields.io/badge/HTML5-Mastery-orange?style=for-the-badge\&logo=html5\&logoColor=white)
![Status](https://img.shields.io/badge/Level-1%20%7C%20Fundamentals-blue?style=for-the-badge)
![Learning](https://img.shields.io/badge/Learning-In%20Progress-yellow?style=for-the-badge)

---

## 🎯 My Goal

Master HTML by **understanding, writing, debugging, and building** rather than simply copying code.

### My learning system

```text
🧠 Learn
   ↓
💡 Understand
   ↓
⌨️ Write myself
   ↓
🧪 Test
   ↓
🐛 Debug
   ↓
🏗️ Build
   ↓
📦 Commit
   ↓
🚀 Push to GitHub
```

---

# 📚 HTML Level 1 — Fundamentals

## 1️⃣ What is HTML?

**HTML = HyperText Markup Language**

HTML is used to define the **structure and content of webpages**.

HTML tells the browser what different pieces of content are:

```text
Heading
Paragraph
Image
Link
Form
Table
Section
etc.
```

> HTML is a **markup language**, not a programming language.

---

# 🌍 How a Webpage Works

When a user opens a website:

```text
👤 User
   │
   ▼
🌐 Browser
   │
   ▼
🌍 Internet
   │
   ▼
🖥️ Web Server
   │
   ▼
📄 HTML Response
   │
   ▼
🌐 Browser reads HTML
   │
   ▼
🖥️ Webpage appears
```

---

# 🧱 HTML + CSS + JavaScript

A webpage can be understood using three major technologies:

```text
┌─────────────────────────────┐
│           WEBSITE           │
├─────────────────────────────┤
│                             │
│  HTML       → Structure     │
│  CSS        → Design        │
│  JavaScript → Behaviour     │
│                             │
└─────────────────────────────┘
```

### 🏠 Simple analogy

```text
HTML       → 🧱 Structure of a house
CSS        → 🎨 Paint & decoration
JavaScript → ⚡ Behaviour & interaction
```

---

# 🏷️ HTML Tags

HTML uses **tags** to describe content.

General structure:

```html
<opening-tag>
    Content
</closing-tag>
```

Example:

```html
<h1>My Heading</h1>
```

### Anatomy

```text
<h1>My Heading</h1>
│   │            │
│   │            └── Closing tag
│   └─────────────── Content
└─────────────────── Opening tag
```

---

# 🧩 HTML Elements

An HTML element generally consists of:

```text
Opening Tag
     ↓
  Content
     ↓
Closing Tag
```

Example:

```html
<p>Hello World</p>
```

Here:

```text
<p>          → Opening tag
Hello World  → Content
</p>         → Closing tag
```

---

# 📄 Basic HTML5 Document Structure

```html
<!DOCTYPE html>

<html>
    <head>
        <title>First Page</title>
    </head>

    <body>
        <h1>Durga Prasad Mishra</h1>
        <p>BCA Student</p>
    </body>
</html>
```

---

# 🔍 Understanding the Structure

```text
<html>
│
├── <head>
│   └── <title>
│
└── <body>
    ├── <h1>
    └── <p>
```

### `<!DOCTYPE html>`

Declares that the document uses **HTML5**.

```html
<!DOCTYPE html>
```

---

### `<html>`

The **root element** of the HTML document.

Everything in the HTML document is placed inside it.

```html
<html>
    ...
</html>
```

---

### `<head>`

Contains information about the webpage that is generally **not displayed as the main page content**.

```html
<head>
    ...
</head>
```

Examples of things commonly placed inside `<head>`:

```text
Page title
Metadata
CSS references
Fonts
Favicon
```

---

### `<title>`

Defines the title shown in the **browser tab**.

```html
<title>First Page</title>
```

---

### `<body>`

Contains the content displayed on the webpage.

```html
<body>
    ...
</body>
```

---

### `<h1>`

Represents the main/largest heading level.

```html
<h1>Durga Prasad Mishra</h1>
```

HTML provides heading levels:

```text
<h1> → Heading level 1
<h2> → Heading level 2
<h3> → Heading level 3
<h4> → Heading level 4
<h5> → Heading level 5
<h6> → Heading level 6
```

---

### `<p>`

Represents a paragraph.

```html
<p>BCA Student</p>
```

---

# 🧠 Important Concept — Nesting

HTML elements can exist inside other elements.

Example:

```html
<html>

    <head>
        <title>My Page</title>
    </head>

    <body>
        <h1>Hello</h1>
    </body>

</html>
```

Think of it like a tree:

```text
html
│
├── head
│   └── title
│
└── body
    └── h1
```

This parent-child relationship is extremely important for HTML.

---

# 🧪 My First HTML Page

My first HTML practice:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>First Page</title>
    </head>

    <body>
        <h1>Durga Prasad Mishra</h1>
        <p>BCA Student</p>
    </body>
</html>
```

---

# 🎯 Level 1 Knowledge Check

<details>
<summary>💡 What does HTML stand for?</summary>

**HyperText Markup Language**

</details>

<details>
<summary>💡 Is HTML a programming language?</summary>

No. HTML is a **markup language** used to structure webpage content.

</details>

<details>
<summary>💡 What does DOCTYPE do?</summary>

It tells the browser that the document uses **HTML5**.

</details>

<details>
<summary>💡 What is the root element?</summary>

`<html>` is the root element of an HTML document.

</details>

<details>
<summary>💡 What is the difference between HEAD and BODY?</summary>

`<head>` contains document information and resources.

`<body>` contains the visible webpage content.

</details>

<details>
<summary>💡 Where does TITLE appear?</summary>

The `<title>` normally appears in the **browser tab**, not as the main visible page content.

</details>

<details>
<summary>💡 What is an HTML element?</summary>

An element generally consists of an opening tag, content, and closing tag.

Example:

```html
<p>Hello</p>
```

</details>

---

⭐ **Repository Status: HTML Mastery — In Progress**
