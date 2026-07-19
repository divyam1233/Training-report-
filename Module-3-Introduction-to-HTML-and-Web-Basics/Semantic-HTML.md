# 🏗️ Semantic HTML (Detailed)

## 📘 Introduction
**Semantic HTML** uses elements that clearly describe their meaning and role in a webpage.  
It improves **readability, accessibility, and SEO** by helping browsers and search engines understand the structure of content.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Why Semantic HTML?
- Provides **meaningful structure** to web pages.  
- Improves **SEO** (search engine optimization).  
- Enhances **accessibility** for screen readers.  
- Makes code easier to read and maintain.  

---

# 🔹 2. Common Semantic Tags

| Tag | Purpose | Example |
|-----|----------|---------|
| `<header>` | Defines page or section header | `<header><h1>Site Title</h1></header>` |
| `<nav>` | Navigation links | `<nav><a href="#">Home</a></nav>` |
| `<section>` | Thematic grouping of content | `<section><h2>About Us</h2></section>` |
| `<article>` | Independent, self-contained content | `<article><h2>Blog Post</h2></article>` |
| `<aside>` | Sidebar or related info | `<aside>Related Links</aside>` |
| `<footer>` | Page or section footer | `<footer>© 2026 MySite</footer>` |
| `<main>` | Main content of page | `<main><h2>Welcome</h2></main>` |
| `<figure>` | Image with caption | `<figure><img src="pic.jpg"><figcaption>Caption</figcaption></figure>` |
| `<mark>` | Highlighted text | `<p>Use <mark>important</mark> keywords.</p>` |

---

# 🔹 3. Example Semantic Layout

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Semantic HTML Example</title>
</head>
<body>
  <header>
    <h1>My Website</h1>
    <nav>
      <a href="#">Home</a> | <a href="#">About</a> | <a href="#">Contact</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>About Us</h2>
      <p>We build modern web applications using semantic HTML.</p>
    </section>

    <article>
      <h2>Latest Blog Post</h2>
      <p>Semantic HTML improves accessibility and SEO.</p>
    </article>

    <aside>
      <h3>Quick Links</h3>
      <ul>
        <li><a href="#">FAQ</a></li>
        <li><a href="#">Support</a></li>
      </ul>
    </aside>
  </main>

  <footer>
    <p>© 2026 My Website</p>
  </footer>
</body>
</html>
