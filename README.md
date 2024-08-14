<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sruthi's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-size: 1.2em;
            margin: 10px 0;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            background: #fff;
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        .project {
            margin-bottom: 20px;
        }
        .project img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }
        form {
            display: grid;
            gap: 10px;
        }
        form input, form textarea {
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1em;
        }
        form input[type="submit"] {
            background: #333;
            color: #fff;
            border: none;
            cursor: pointer;
            font-size: 1.1em;
        }
        form input[type="submit"]:hover {
            background: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sruthi</h1>
        <p>Passionate Software Developer</p>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am Sruthi, a software developer with a B.Tech in Computer Science and Engineering from Vignan University.</p>
        <h3>Education</h3>
        <ul>
            <li>B.Tech in Computer Science and Engineering, Vignan University</li>
        </ul>
        <h3>Professional Interests</h3>
        <p>I am deeply interested in software development and enjoy working on innovative projects and technologies.“I am looking for an entry-level position to kickstart my career in the software field. I wish to work in a dynamic organisation that will contribute to my professional and personal growth while I contribute to the growth of the company as well as engage in opportunities to further the company's goals.”</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <article class="project">
            <h3>Project One</h3>
            <p>Brief description of Project One.</p>
            <a href="https://projectone.com" target="_blank">View Project</a>
            <img src="projectone-screenshot.jpg" alt="Screenshot of Project One">
        </article>
        <article class="project">
            <h3>Project Two</h3>
            <p>Brief description of Project Two.</p>
            <a href="https://projecttwo.com" target="_blank">View Project</a>
            <img src="projecttwo-screenshot.jpg" alt="Screenshot of Project Two">
        </article>
        <article class="project">
            <h3>Project Three</h3>
            <p>Brief description of Project Three.</p>
            <a href="https://projectthree.com" target="_blank">View Project</a>
            <img src="projectthree-screenshot.jpg" alt="Screenshot of Project Three">
        </article>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <input type="submit" value="Send Message">
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Sruthi. All rights reserved.</p>
    </footer>
</body>
</html>

