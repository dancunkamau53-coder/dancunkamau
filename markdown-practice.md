<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dancun Kamau Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }

        header {
            background-color: #4a90e2;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 3em;
        }

        header p {
            font-size: 1.2em;
        }

        nav {
            text-align: center;
            margin: 20px 0;
        }

        nav a {
            text-decoration: none;
            color: #4a90e2;
            margin: 0 15px;
            font-weight: bold;
        }

        section {
            max-width: 1000px;
            margin: 40px auto;
            padding: 0 20px;
        }

        h2 {
            color: #4a90e2;
            margin-bottom: 20px;
        }

        .projects, .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .card {
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            flex: 1 1 250px;
            padding: 20px;
        }

        .card img {
            max-width: 100%;
            border-radius: 8px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #4a90e2;
            color: white;
        }

        footer a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }

    </style>
</head>
<body>

    <header>
        <h1>Dancun Kamau</h1>
        <p>Aspiring Web Developer | Tech Enthusiast | Portfolio Showcase</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am Dancun Kamau, a passionate developer learning web technologies and building projects to showcase my skills. I love creating clean, modern, and interactive web experiences.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="card">
                <img src="https://via.placeholder.com/300x200" alt="Project 1">
                <h3>Project 1</h3>
                <p>Short description of your first project. What it does and why it’s cool.</p>
                <a href="#">View Project</a>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/300x200" alt="Project 2">
                <h3>Project 2</h3>
                <p>Short description of your second project. Include links or demo info.</p>
                <a href="#">View Project</a>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/300x200" alt="Project 3">
                <h3>Project 3</h3>
                <p>Short description of your third project. Highlight key features.</p>
                <a href="#">View Project</a>
            </div>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <div class="card"><h3>HTML</h3></div>
            <div class="card"><h3>CSS</h3></div>
            <div class="card"><h3>JavaScript</h3></div>
            <div class="card"><h3>Git & GitHub</h3></div>
            <div class="card"><h3>Responsive Design</h3></div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>You can reach me via email or follow me on social media:</p>
        <p>Email: <a href="mailto:dancun.kamau@example.com">dancun.kamau@example.com</a></p>
        <p>
            <a href="https://github.com/yourusername">GitHub</a> | 
            <a href="https://linkedin.com/in/yourusername">LinkedIn</a> | 
            <a href="https://twitter.com/yourusername">Twitter</a>
        </p>
    </section>

    <footer>
        &copy; 2026 Dancun Kamau | Made with ❤️
    </footer>

</body>
</html>
