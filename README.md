# DALURA_ELAIZA_RANARA_PORTFOLIO

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elaiza | Creative Portfolio</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background: #faf9f6;
            color: #333;
            line-height: 1.7;
        }

        header {
            padding: 25px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: white;
        }

        nav a {
            color: #333;
            text-decoration: none;
            margin-left: 18px;
        }

        section {
            padding: 65px 10%;
        }

        .hero {
            background: #f2eadb;
            padding: 100px 10%;
        }

        h1 {
            font-size: 42px;
            margin-bottom: 12px;
        }

        h2 {
            margin-bottom: 20px;
        }

        .projects {
            display: grid;
            grid-template-columns:
                repeat(auto-fit, minmax(230px, 1fr));
            gap: 20px;
        }

        .project {
            background: white;
            padding: 22px;
            border-radius: 12px;
        }

        .project img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 12px;
        }

        footer {
            padding: 25px;
            text-align: center;
            background: #eee9df;
        }

        @media (max-width: 600px) {
            header {
                flex-direction: column;
                gap: 12px;
            }

            nav a {
                margin: 5px;
            }

            h1 {
                font-size: 32px;
            }
        }
    </style>
</head>

<body>

<header>
    <strong>ELAIZA.</strong>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#creative">Creative Works</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h1>Hello, I'm Elaiza!</h1>
    <p>BSIT Student | Aspiring UI/UX & Website Designer</p>
    <p>I enjoy creating digital experiences,
       designing interfaces, and exploring creativity.</p>
</section>

<section id="about">
    <h2>About Me</h2>
    <p>
        I am a third-year Information Technology student
        at PHINMA-COC with an interest in website design,
        UI/UX, digital illustration, and animation.
        I enjoy combining technology and creativity
        through my academic projects.
    </p>
</section>

<section id="projects">
    <h2>Completed Projects</h2>
    <div class="projects">

        <div class="project">
            <h3>Dish Diaries</h3>
            <p>Food recipe website designed with a focus
               on visual presentation and user experience.</p>
        </div>

        <div class="project">
            <h3>Gas Station Management System</h3>
            <p>Web-based system for managing transactions,
               inventory, and user accounts.</p>
        </div>

        <div class="project">
            <h3>Car Rental System</h3>
            <p>Java Swing application for managing vehicles,
               reservations, and customer records.</p>
        </div>

    </div>
</section>

<section id="creative">
    <h2>Creative Works</h2>
    <div class="project">
        <h3>Jungle Hunt</h3>
        <p>Ongoing academic 2D game development project
           featuring original characters, illustrations,
           and Blender animations.</p>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Email: YOUR-PROFESSIONAL-EMAIL</p>
    <p>LinkedIn: YOUR-LINKEDIN-LINK</p>
</section>

<footer>
    <p>© 2026 Elaiza | Creative Portfolio</p>
</footer>

</body>
</html>
