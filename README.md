# 🌐 Semantic HTML Tags Reference

Semantic HTML Tags Reference is a simple guide showcasing semantic HTML tags with examples to help developers build accessible and well-structured web pages.

---
## Semantic HTML 
gives meaning to the structure of a web page. It improves accessibility, SEO, and maintainability.



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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BossBrand - Digital Solutions</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <!-- Header and Navigation -->
  <header>
    <nav>
      <div class="container nav-wrapper">
        <h1>BossBrand</h1>
        <ul class="nav-links">
          <li><a href="#">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- Main Hero Section -->
  <main>
    <section class="hero">
      <div class="container hero-content">
        <div>
          <h2>Crafting Digital Experiences</h2>
          <p>From concept to code, we transform your vision into responsive, engaging web solutions.</p>
          <a href="#services" class="btn">Learn More →</a>
        </div>
        <figure>
          <img src="images/hero-image.webp" alt="Team working on digital design" />
          <figcaption>BossBrand Digital Team</figcaption>
        </figure>
      </div>
    </section>

    <!-- Services Section -->
    <section id="services">
      <div class="container">
        <h3>What We Do</h3>
        <div class="services">
          <article>
            <h4>Web Development</h4>
            <p>Fast and modern websites built with Next.js, React, or Vue.</p>
          </article>
          <article>
            <h4>UI/UX Design</h4>
            <p>Clean, user-centered design that’s both functional and beautiful.</p>
          </article>
          <article>
            <h4>API Integration</h4>
            <p>Secure and scalable backends with Node.js, Express, and PostgreSQL.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about">
      <div class="container">
        <h3>About Us</h3>
        <p>We are passionate developers and designers based in Chiang Mai, delivering creative solutions worldwide.</p>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <div class="container text-center">
      <p>© 2025 BossBrand. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>
