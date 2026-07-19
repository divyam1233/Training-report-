# 🌐 HTML Tags (Detailed)

## 📘 Introduction
**HTML tags** are the building blocks of web pages.  
They define the structure, content, and meaning of elements in a document.  
Tags are enclosed in angle brackets `< >` and usually come in pairs: an **opening tag** and a **closing tag**.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Basic Structure Tags

| Tag | Purpose | Example |
|-----|----------|---------|
| `<!DOCTYPE html>` | Declares HTML5 document type | `<!DOCTYPE html>` |
| `<html>` | Root element | `<html> ... </html>` |
| `<head>` | Metadata, title, styles | `<head> ... </head>` |
| `<title>` | Page title | `<title>My Page</title>` |
| `<body>` | Visible content | `<body> ... </body>` |

---

# 🔹 2. Text Formatting Tags

| Tag | Purpose | Example |
|-----|----------|---------|
| `<h1>` – `<h6>` | Headings | `<h1>Main Title</h1>` |
| `<p>` | Paragraph | `<p>This is text.</p>` |
| `<b>` | Bold text | `<b>Bold</b>` |
| `<i>` | Italic text | `<i>Italic</i>` |
| `<u>` | Underline | `<u>Underline</u>` |
| `<br>` | Line break | `Line1<br>Line2` |
| `<hr>` | Horizontal line | `<hr>` |

---

# 🔹 3. Links and Media Tags

| Tag | Purpose | Example |
|-----|----------|---------|
| `<a>` | Hyperlink | `<a href="https://github.com">GitHub</a>` |
| `<img>` | Image | `<img src="logo.png" alt="Logo">` |
| `<video>` | Video | `<video controls><source src="movie.mp4"></video>` |
| `<audio>` | Audio | `<audio controls><source src="song.mp3"></audio>` |

---

# 🔹 4. List Tags

| Tag | Purpose | Example |
|-----|----------|---------|
| `<ul>` | Unordered list | `<ul><li>Item</li></ul>` |
| `<ol>` | Ordered list | `<ol><li>Item</li></ol>` |
| `<li>` | List item | `<li>Item</li>` |

---

# 🔹 5. Table Tags

| Tag | Purpose | Example |
|-----|----------|---------|
| `<table>` | Table container | `<table> ... </table>` |
| `<tr>` | Table row | `<tr> ... </tr>` |
| `<td>` | Table data cell | `<td>Data</td>` |
| `<th>` | Table header cell | `<th>Heading</th>` |

👉 Example:
```html
<table border="1">
  <tr>
    <th>Name</th><th>URN</th>
  </tr>
  <tr>
    <td>Divyam Garg</td><td>2513993</td>
  </tr>
</table>
