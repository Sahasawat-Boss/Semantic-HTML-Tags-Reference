# 🌐 Semantic HTML Tags Reference

Semantic HTML gives meaning to the structure of a web page. It improves accessibility, SEO, and maintainability.

---

## 📌 Document Structure

| Tag        | Purpose                                                   |
|------------|-----------------------------------------------------------|
| `<html>`   | Root element of an HTML document                          |
| `<head>`   | Contains meta information, links to CSS, etc.             |
| `<body>`   | Contains the visible content of the webpage               |

---

## 📑 Page Layout Tags

| Tag        | Purpose                                                   |
|------------|-----------------------------------------------------------|
| `<header>` | Represents introductory content (site or section header)  |
| `<nav>`    | Contains navigation links                                 |
| `<main>`   | The main content area of the document                     |
| `<section>`| Groups related content into sections                      |
| `<article>`| Represents self-contained content (e.g. blog post)        |
| `<aside>`  | Content tangentially related to the main content          |
| `<footer>` | Footer for a section or the whole document                |

---

## 🖼️ Media & Content Tags

| Tag           | Purpose                                                  |
|---------------|----------------------------------------------------------|
| `<figure>`     | A self-contained piece of media/content (image, code)   |
| `<figcaption>` | Caption for the `<figure>` element                      |
| `<img>`        | Embeds images                                            |
| `<video>`      | Embeds video content                                     |
| `<audio>`      | Embeds audio content                                     |
| `<iframe>`     | Embeds other HTML pages or media                         |

---

## 📝 Text Content & Formatting

| Tag        | Purpose                                                   |
|------------|-----------------------------------------------------------|
| `<h1>`–`<h6>` | Headings from most to least important                   |
| `<p>`      | Paragraph                                                  |
| `<strong>` | Important text (bold)                                     |
| `<em>`     | Emphasized text (italic)                                  |
| `<blockquote>`| Quoted text                                             |
| `<cite>`   | Citing a source                                            |
| `<mark>`   | Highlighted/marked text                                   |
| `<code>`   | Inline code snippet                                       |
| `<pre>`    | Preformatted text block (e.g. code block)                 |
| `<abbr>`   | Abbreviation or acronym                                   |
| `<br>`     | Line break                                                |
| `<hr>`     | Thematic break (horizontal rule)                          |

---

## 📋 Interactive Elements

| Tag         | Purpose                                                  |
|-------------|----------------------------------------------------------|
| `<a>`       | Anchor (hyperlink)                                       |
| `<button>`  | Clickable button                                         |
| `<details>` | Collapsible content container                            |
| `<summary>` | Visible summary for `<details>`                          |
| `<form>`    | User input form                                          |
| `<input>`   | User input field                                         |
| `<label>`   | Label for input fields                                   |
| `<select>`  | Drop-down list                                           |
| `<option>`  | Option in a drop-down list                               |
| `<textarea>`| Multi-line input field                                   |

---

## 📆 Metadata & Time

| Tag       | Purpose                                                     |
|-----------|-------------------------------------------------------------|
| `<time>`  | Represents a date/time value                                |
| `<meta>`  | Meta information (charset, description, etc.)               |
| `<title>` | The title of the document (in browser tab)                  |
| `<link>`  | External resource (e.g., CSS file)                          |
| `<script>`| JavaScript embedding                                        |
| `<style>` | Embeds CSS directly in HTML                                 |

---

## 🧠 Tips

- Use **`<main>`** only once per page
- Avoid `<div>` and `<span>` unless no semantic tag fits
- Use **ARIA roles** if needed to enhance semantics

---

## ✅ Example Layout

```html
<body>
  <header>
    <nav>
      <!-- navigation links -->
    </nav>
  </header>

  <main>
    <section>
      <article>
        <h2>Blog Post Title</h2>
        <p>Post content...</p>
      </article>
    </section>

    <aside>
      <p>Sidebar info, ads, or related links</p>
    </aside>
  </main>

  <footer>
    <p>© 2025 My Website</p>
  </footer>
</body>
