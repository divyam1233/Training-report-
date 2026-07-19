# 📝 HTML Forms (Detailed)

## 📘 Introduction
**HTML forms** are used to collect user input on web pages.  
They allow users to enter data such as text, passwords, selections, and submit it to a server for processing.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Basic Form Structure

👉 Example:
```html
<form action="submit.html" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br>

  <input type="submit" value="Submit">
</form>
