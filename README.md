<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A FAKRUDEEN | Portfolio</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f2f6ff;
            color: #333;
        }

        header {
            background-color: #1e3a8a;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }

        header h1 {
            font-size: 40px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 18px;
        }

        nav {
            background-color: #111827;
            text-align: center;
            padding: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #60a5fa;
        }

        section {
            background-color: white;
            margin: 25px auto;
            padding: 30px;
            width: 80%;
            max-width: 900px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #1e3a8a;
            border-bottom: 2px solid #1e3a8a;
            padding-bottom: 10px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .skill {
            background-color: #1e3a8a;
            color: white;
            padding: 12px 20px;
            border-radius: 20px;
        }

        .project {
            background-color: #eef4ff;
            padding: 15px;
            margin-top: 15px;
            border-left: 5px solid #1e3a8a;
        }

        .contact p {
            font-size: 18px;
        }

        footer {
            background-color: #111827;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>
        <h1>A FAKRUDEEN</h1>
        <p>BE CSE Student | 1st Year</p>
        <p>Welcome to My Portfolio</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>

        <p>
            Hello! My name is <strong>A FAKRUDEEN</strong>.
            I am a first-year Bachelor of Engineering student
            specializing in Computer Science and Engineering.
        </p>

        <p>
            I am interested in programming, web development,
            and learning new technologies. I am currently
            developing my technical skills and working towards
            becoming a successful software professional.
        </p>
    </section>

    <!-- Education Section -->
    <section id="education">
        <h2>Education</h2>

        <p><strong>College:</strong>
            MOUNTZION COLLEGE OF ENGINEERING AND TECHNOLOGY
        </p>

        <p><strong>Degree:</strong> BE CSE</p>

        <p><strong>Year:</strong> 1st Year</p>

        <p><strong>City:</strong> KARAIKUDI</p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>

        <div class="skills">
            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">C Programming</div>
            <div class="skill">Python</div>
            <div class="skill">Problem Solving</div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>

        <div class="project">
            <h3>Personal Portfolio Website</h3>
            <p>
                A personal portfolio website created using
                HTML and CSS to showcase my profile,
                education, skills, and contact information.
            </p>
        </div>

        <div class="project">
            <h3>Future Project</h3>
            <p>
                I will add my upcoming programming and
                web development projects here.
            </p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Me</h2>

        <p><strong>Name:</strong> A FAKRUDEEN</p>

        <p><strong>Phone:</strong> 7358720578</p>

        <p><strong>City:</strong> KARAIKUDI</p>

        <p><strong>College:</strong>
            MOUNTZION COLLEGE OF ENGINEERING AND TECHNOLOGY
        </p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 A FAKRUDEEN. All Rights Reserved.</p>
        <p>BE CSE | 1st Year</p>
    </footer>

</body>
</html>
