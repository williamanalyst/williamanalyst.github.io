<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Personal Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 1rem;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            overflow: hidden;
            padding: 0 2rem;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Personal Page</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I'm [Your Name], a data scientist specializing in [your specialization]. Currently, I'm applying for a data scientist position at Microsoft Clipchamp.</p>
            <img src="[image_url]" alt="A photo of [Your Name]">
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li>
                    <a href="[project_link]">Project 1</a>: Description of project 1.
                    <br>
                    <img src="[image_url]" alt="Screenshot of Project 1">
                </li>
                <li>
                    <a href="[project_link]">Project 2</a>: Description of project 2.
                    <br>
                    <img src="[image_url]" alt="Screenshot of Project 2">
                </li>
                <li>
                    <a href="[project_link]">Project 3</a>: Description of project 3.
                    <br>
                    <img src="[image_url]" alt="Screenshot of Project 3">
                </li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>You can reach me at <a href="mailto:your.email@example.com">your.email@example.com</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 [Your Name]. All Rights Reserved.</p>
    </footer>
</body>
</html>
