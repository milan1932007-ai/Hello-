# new project 
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
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            background: #555;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        .card {
            background: white;
            padding: 15px;
            margin: 10px 0;
            border-radius: 8px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>My Portfolio</h1>
    <p>Welcome to my personal website</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <div class="card">
        <h2>About Me</h2>
        <p>Hello! I am a student learning web development.</p>
    </div>
</section>

<section id="projects">
    <div class="card">
        <h2>Projects</h2>
        <ul>
            <li>To-Do List App</li>
            <li>Calculator</li>
            <li>Event Registration Form</li>
        </ul>
    </div>
</section>

<section id="contact">
    <div class="card">
        <h2>Contact</h2>
        <p>Email: example@gmail.com</p>
    </div>
</section>

<footer>
    <p>© 2026 My Portfolio</p>
</footer>

</body>
</html>
