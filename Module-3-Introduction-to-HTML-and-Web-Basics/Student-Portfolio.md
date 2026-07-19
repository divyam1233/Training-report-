# 💼 My Professional Portfolio

## 📘 Introduction
This project is a **personal portfolio webpage** built using **HTML and CSS**.  
It highlights your profile, projects, academic progress, and coding interests — all styled with a **modern gradient background** and **glass‑effect cards**.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 Complete HTML + CSS Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Professional Portfolio</title>
    <style>
        :root {
            --primary: #4f46e5;
            --secondary: #0ea5e9;
            --dark: #0f172a;
            --light-bg: #f8fafc;
            --gradient: linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Inter', system-ui, sans-serif;
            background: var(--gradient);
            background-attachment: fixed;
            color: var(--dark);
            line-height: 1.6;
            padding: 2rem;
        }

        .max-w { max-width: 900px; margin: 0 auto; }

        header { padding: 4rem 0; text-align: center; }
        h1 {
            font-size: 3rem;
            background: linear-gradient(90deg, #1e293b, #4f46e5);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 0.5rem;
        }

        .project-card, .card {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.5);
            border-radius: 16px;
            padding: 1rem;
        }

        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }

        table {
            background: white;
            border-radius: 16px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            width: 100%;
            border-collapse: collapse;
        }

        th {
            background: var(--primary);
            color: white;
        }

        .site-footer {
            margin-top: 6rem;
            padding: 3rem;
            background: var(--dark);
            color: white;
            border-radius: 16px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="max-w">
        <header>
            <h1>I am Divyam Garg.</h1>
            <p class="tagline">Second Year Engineering Student & UI/UX & Web Dev</p>
            <p class="age">I am 19 years old</p>
            <aside class="focus">
                <p><em>I focus on curiosity, adaptability, and learning new technologies quickly.</em></p>
            </aside>
        </header>

        <section>
            <h2>Projects</h2>
            <div class="project-grid">
                <article class="project-card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTbVROOWJZCLDYFYtKAWRRDbTl2sFfsn_rRY1W3Z5lZEw&s=10" alt="code project">
                    <h3>DSA Visualizer</h3>
                    <p>A tool to visualize sorting algorithms with JavaScript.</p>
                </article>

                <article class="project-card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSGa7ZsiyuyNERlbU1oTtRngEXObh_mQubZhEIyT9Iawg&s=10" alt="AI">
                    <h3>AI & Machine Learning</h3>
                    <p>Machine Learning (ML) uses algorithms to automatically learn patterns from data.</p>
                </article>
            </div>
        </section>

        <section style="margin-top: 5rem;">
            <h2>Academic Progress</h2>
            <table cellpadding="10">
                <thead>
                    <tr>
                        <th>Educational Qualifications</th>
                        <th>Passing Percentage</th>
                    </tr>
                </thead>
                <tbody>
                    <tr><td>CSE - Semester 1</td><td>92.6%</td></tr>
                    <tr><td>Senior Secondary (Class XII)</td><td>96%</td></tr>
                    <tr><td>Secondary (Class X)</td><td>98.6%</td></tr>
                </tbody>
            </table>
        </section>

        <section class="interests-container">
            <h2>My Coding Areas of Interest</h2>
            <div class="project-grid">
                <div class="card">
                    <h3>Web Development</h3>
                    <p>Building responsive, user-centric interfaces using React and modern CSS.</p>
                </div>
                <div class="card">
                    <h3>Data Science</h3>
                    <p>Analyzing datasets and building predictive models with Python and Pandas.</p>
                </div>
                <div class="card">
                    <h3>Cloud Computing</h3>
                    <p>Deploying scalable architecture using AWS and Docker Containers.</p>
                </div>
            </div>
        </section>

        <footer class="site-footer">
            <h3>Let's Connect</h3>
            <p>Feel free to reach out for collaboration or project inquiries.</p>
            <div class="social-links">
                <a href="mailto:gargdivyam@gmail.com">Email</a> |
                <a href="https://github.com/gargd22" target="_blank">GitHub</a> |
                <a href="https://linkedin.com/in/gargd22" target="_blank">LinkedIn</a>
            </div>
            <p>@ 2026 Divyam Garg. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>


[Go to my Portfolio](PORTFOLIO.html)

