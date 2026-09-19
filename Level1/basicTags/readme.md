# 🌐 HTML Basics — Quick Notes

## 1. Basic HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Page Title</title>
</head>
<body>

    <!-- Visible webpage content -->

</body>
</html>
```

### Important Tags

| Tag               | Usage                                  |
| ----------------- | -------------------------------------- |
| `<!DOCTYPE html>` | Declares HTML5 document                |
| `<html>`          | Root element of the page               |
| `<head>`          | Contains page information/metadata     |
| `<title>`         | Sets browser tab title                 |
| `<body>`          | Contains visible webpage content       |
| `<h1>`            | Main heading                           |
| `<h2>`            | Second-level heading                   |
| `<p>`             | Paragraph                              |
| `<div>`           | Generic container for grouping content |

---

## 2. Headings

HTML provides six heading levels:

```html
<h1>Main Heading</h1>
<h2>Second Heading</h2>
<h3>Third Heading</h3>
<h4>Fourth Heading</h4>
<h5>Fifth Heading</h5>
<h6>Sixth Heading</h6>
```

```text
<h1> → Highest-level heading
<h2>
<h3>
<h4>
<h5>
<h6> → Lowest-level heading
```

---

## 3. Paragraph

Used for normal blocks of text.

```html
<p>This is a paragraph.</p>
```

---

## 4. `<div>`

`<div>` is a **generic block-level container** used to group related HTML elements.

Example:

```html
<div>
    <h2>My Skills</h2>
    <p>HTML</p>
    <p>CSS</p>
</div>
```

Structure:

```text
div
├── h2
├── p
└── p
```

### Why use `<div>`?

It helps group elements so they can later be:

* Styled with CSS
* Manipulated with JavaScript
* Organized into sections of a page

---

## 5. Nesting

HTML elements can be placed inside other elements.

```html
<div>
    <h1>My Name</h1>
    <p>I am a BCA student.</p>
</div>
```

Here:

```text
div → Parent
h1  → Child
p   → Child
```

`h1` and `p` are **siblings** because they have the same parent.

---

## 6. Attributes

Attributes provide additional information about an element.

```html
<html lang="en">
```

Here:

```text
lang → Attribute
en   → Attribute value
```

General syntax:

```html
<tag attribute="value">
```

---

## 7. Comments

Comments are ignored by the browser and used to explain code.

```html
<!-- This is a comment -->
```

---

## 🧠 Quick Memory

```text
<html>  → Whole document
<head>  → Page information
<title> → Browser tab
<body>  → Visible content
<h1>    → Main heading
<h2>    → Sub-heading
<p>     → Paragraph
<div>   → Group/container
```
