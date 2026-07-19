# 🧾 Student Form (HTML Code)

## 📘 Introduction
This HTML program creates a **student information form** using various input types such as text, email, password, radio buttons, checkboxes, dropdowns, and text areas.  
The form uses the **POST** method to send data to `submit.html`.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 HTML Code

```html
<!DOCTYPE html>
<html>
<head>
    <title>Form Demo</title>
</head>
<body>
    <form action="submit.html" method="post">
        <fieldset>
            <legend>Student Form</legend>

            <label for="n">Name:</label>
            <input type="text" id="n" required><br>

            <label for="e">Email:</label>
            <input type="email" id="e"><br>

            <label for="p">Password:</label>
            <input type="password" id="p"><br>

            <label>Gender:</label>
            <input type="radio" id="m" name="g">
            <label for="m">Male</label>
            <input type="radio" id="f" name="g">
            <label for="f">Female</label><br>

            <label><input type="checkbox"> Reading</label><br>

            <label for="s">State:</label>
            <select id="s">
                <option>Punjab</option>
            </select><br>

            <label for="b">Bio:</label>
            <textarea id="b" rows="2"></textarea><br>

            <input type="submit" value="Submit">
            <input type="reset" value="Reset">
        </fieldset>
    </form>
</body>
</html>
![alt text](<student form.jpeg>)