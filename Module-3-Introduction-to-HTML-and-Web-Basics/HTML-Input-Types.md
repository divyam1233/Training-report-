# ⌨️ HTML Input Types (Detailed)

## 📘 Introduction
The `<input>` tag in HTML is one of the most versatile elements.  
It allows users to enter different kinds of data in forms.  
The `type` attribute defines the behavior and appearance of the input field.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Common Input Types

| Type | Purpose | Example |
|------|----------|---------|
| `text` | Single-line text | `<input type="text" name="username">` |
| `password` | Hidden characters | `<input type="password" name="pwd">` |
| `email` | Email validation | `<input type="email" name="email">` |
| `number` | Numeric input | `<input type="number" min="1" max="10">` |
| `date` | Date picker | `<input type="date">` |
| `time` | Time picker | `<input type="time">` |
| `url` | Website address | `<input type="url">` |
| `tel` | Telephone number | `<input type="tel">` |

---

# 🔹 2. Choice Inputs

| Type | Purpose | Example |
|------|----------|---------|
| `radio` | Single choice | `<input type="radio" name="gender" value="male"> Male` |
| `checkbox` | Multiple choices | `<input type="checkbox" name="hobby" value="sports"> Sports` |
| `select` (dropdown) | Choose from list | `<select><option>Option1</option></select>` |

---

# 🔹 3. File and Media Inputs

| Type | Purpose | Example |
|------|----------|---------|
| `file` | Upload files | `<input type="file">` |
| `image` | Submit with image button | `<input type="image" src="submit.png">` |
| `color` | Color picker | `<input type="color">` |

---

# 🔹 4. Buttons

| Type | Purpose | Example |
|------|----------|---------|
| `submit` | Submit form | `<input type="submit" value="Send">` |
| `reset` | Reset form | `<input type="reset" value="Clear">` |
| `button` | Custom button | `<input type="button" value="Click Me">` |

---

# 🔹 5. Example Form Using Multiple Input Types

```html
<!DOCTYPE html>
<html>
<head>
  <title>Input Types Demo</title>
</head>
<body>
  <form action="submit.html" method="post">
    <label>Name:</label>
    <input type="text" name="name" required><br>

    <label>Password:</label>
    <input type="password" name="pwd"><br>

    <label>Email:</label>
    <input type="email" name="email"><br>

    <label>Age:</label>
    <input type="number" name="age" min="1" max="100"><br>

    <label>Gender:</label>
    <input type="radio" name="gender" value="male"> Male
    <input type="radio" name="gender" value="female"> Female<br>

    <label>Hobbies:</label>
    <input type="checkbox" name="hobby" value="reading"> Reading
    <input type="checkbox" name="hobby" value="sports"> Sports<br>

    <label>Favorite Color:</label>
    <input type="color" name="favcolor"><br>

    <label>Upload File:</label>
    <input type="file" name="resume"><br>

    <input type="submit" value="Submit">
    <input type="reset" value="Reset">
  </form>
</body>
</html>
