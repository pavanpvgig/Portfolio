<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            padding: 10px;
            background-color: #0056b3;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }
        .project {
            background: white;
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0px 0px 5px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <h1>John Doe</h1>
        <p>Beginner Software Developer | Web Enthusiast</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I’m John, a beginner software developer passionate about building simple and effective web applications. I enjoy learning new technologies and improving my coding skills every day.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>To-Do List App</h3>
            <p>A simple app to manage your daily tasks using HTML, CSS, and JavaScript.</p>
        </div>
        <div class="project">
            <h3>Weather App</h3>
            <p>An app that fetches real-time weather data from an API and displays it to the user.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: johndoe@example.com</p>
        <p>LinkedIn: <a href="#" target="_blank">My LinkedIn</a></p>
        <p>GitHub: <a href="#" target="_blank">My GitHub</a></p>
    </section>

    <footer>
        <p>&copy; 2025 John Doe. All rights reserved.</p>
    </footer>

</body>
</html>
