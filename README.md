# vedantnila.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f0f0f5;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #1a1a2e;
            color: #fff;
            padding: 2rem;
            text-align: center;
        }
        header h1 {
            margin-bottom: 1rem;
            font-size: 2.5rem;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: 600;
            transition: color 0.3s ease;
        }
        nav ul li a:hover {
            color: #e94560;
        }
        section {
            padding: 3rem 2rem;
            text-align: center;
        }
        .about {
            background-color: #fff;
            border-radius: 10px;
            padding: 2rem;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 2rem;
        }
        .about img {
            max-width: 150px;
            border-radius: 50%;
            margin-bottom: 1.5rem;
        }
        .skills {
            background-color: #fff;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 2rem;
        }
        .skills h2 {
            margin-bottom: 1rem;
        }
        .skills ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 1rem;
        }
        .skills ul li {
            background-color: #1a1a2e;
            color: #fff;
            padding: 0.5rem 1rem;
            border-radius: 5px;
        }
        .projects {
            background-color: #1a1a2e;
            color: #fff;
            padding: 2rem;
            border-radius: 10px;
        }
        .projects h2 {
            color: #e94560;
            margin-bottom: 2rem;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .project {
            background-color: #fff;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }
        .project img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .project h3 {
            margin: 1rem;
            color: #1a1a2e;
        }
        .project p {
            margin: 1rem;
            font-size: 0.95rem;
            color: #555;
        }
        .blog {
            background-color: #fff;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 2rem;
        }
        .blog h2 {
            margin-bottom: 1rem;
        }
        .blog-post {
            margin-bottom: 1.5rem;
        }
        .blog-post h3 {
            color: #1a1a2e;
            margin-bottom: 0.5rem;
        }
        .blog-post p {
            color: #555;
        }
        .contact {
            background-color: #fff;
            border-radius: 10px;
            padding: 2rem;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .contact h2 {
            margin-bottom: 1rem;
        }
        .contact p a {
            color: #e94560;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s ease;
        }
        .contact p a:hover {
            color: #1a1a2e;
        }
        footer {
            background-color: #1a1a2e;
            color: #fff;
            padding: 1rem;
            text-align: center;
            margin-top: 3rem;
        }
        footer p {
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

   <section id="about" class="about">
        <img src="https://via.placeholder.com/150" alt="Profile Picture">
        <h2>About Me</h2>
        <p>Hi! I'm a web developer passionate about building beautiful and functional websites.</p>
    </section>

  <section id="skills" class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>React</li>
            <li>Node.js</li>
        </ul>
    </section>

  <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project">
            <img src="https://via.placeholder.com/300" alt="Project 1">
            <h3>Project 1</h3>
            <p>A brief description of project 1. <strong>Technologies:</strong> HTML, CSS, JavaScript</p>
        </div>
        <div class="project">
            <img src="https://via.placeholder.com/300" alt="Project 2">
            <h3>Project 2</h3>
            <p>A brief description of project 2. <strong>Technologies:</strong> React, Node.js</p>
        </div>
        <div class="project">
            <img src="https://via.placeholder.com/300" alt="Project 3">
            <h3>Project 3</h3>
            <p>A brief description of project 3</p>
        </div>
    </section>

   <section id="blog" class="blog">
        <h2>Blog</h2>
        <div class="blog-post">
            <h3>Post Title 1</h3>
            <p>A brief description or excerpt of the first blog post.</p>
        </div>
        <div class="blog-post">
            <h3>Post Title 2
