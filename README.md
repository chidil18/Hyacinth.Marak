
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Creative Portfolio</title>

    <!-- Connect CSS file -->
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="logo">MY<span>PORTFOLIO.</span></div>

        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>


    <!-- Home Section -->
    <section class="hero" id="home">

        <div class="hero-text">
            <p class="welcome">HELLO, WELCOME TO MY PORTFOLIO</p>

            <h1>
                I'm <span>Your Name</span>
            </h1>

            <h2>Creative Designer & Student</h2>

            <p class="description">
                I am a creative and passionate individual
                who loves designing, learning new technologies
                and creating meaningful digital experiences.
            </p>

            <a href="#contact" class="btn">Contact Me</a>
            <a href="#about" class="btn secondary">Explore More</a>
        </div>

        <div class="hero-image">
            <img src="https://placehold.co/400x450/20243A/FFFFFF?text=Your+Photo"
                 alt="My Profile Photo">
        </div>

    </section>


    <!-- About Section -->
    <section class="section" id="about">

        <h2 class="section-title">About <span>Me</span></h2>

        <div class="about-content">

            <p>
                Hello! My name is Your Name. I am an enthusiastic
                student with an interest in creativity, technology
                and design.

                I enjoy exploring new ideas, improving my skills
                and working on projects that allow me to express
                my creativity.

                My goal is to develop my knowledge and build
                a successful career in my chosen field.
            </p>

        </div>

    </section>


    <!-- Skills Section -->
    <section class="section" id="skills">

        <h2 class="section-title">My <span>Skills</span></h2>

        <div class="skills-container">

            <div class="skill-card">
                <h3>HTML</h3>
                <p>Webpage Structure</p>
            </div>

            <div class="skill-card">
                <h3>CSS</h3>
                <p>Web Design & Styling</p>
            </div>

            <div class="skill-card">
                <h3>Creativity</h3>
                <p>Creative Thinking</p>
            </div>

            <div class="skill-card">
                <h3>Communication</h3>
                <p>Team Collaboration</p>
            </div>

        </div>

    </section>


    <!-- Projects Section -->
    <section class="section" id="projects">

        <h2 class="section-title">My <span>Projects</span></h2>

        <div class="projects-container">

            <div class="project-card">
                <div class="project-image">01</div>
                <h3>Personal Website</h3>
                <p>
                    A personal website created using
                    HTML and CSS.
                </p>
            </div>

            <div class="project-card">
                <div class="project-image">02</div>
                <h3>Creative Poster</h3>
                <p>
                    A creative poster design made
                    using digital design tools.
                </p>
            </div>

            <div class="project-card">
                <div class="project-image">03</div>
                <h3>Portfolio Design</h3>
                <p>
                    A responsive portfolio website
                    showcasing my skills and work.
                </p>
            </div>

        </div>

    </section>


    <!-- Education Section -->
    <section class="section" id="education">

        <h2 class="section-title">My <span>Education</span></h2>

        <div class="education-card">
            <h3>Your Degree / Course</h3>
            <p>Your College or University Name</p>
            <p>2023 - 2026</p>
        </div>

    </section>


    <!-- Contact Section -->
    <section class="section" id="contact">

        <h2 class="section-title">Contact <span>Me</span></h2>

        <div class="contact-content">

            <p>Email: yourname@email.com</p>
            <p>Phone: +91 9876543210</p>
            <p>Location: Your City, India</p>

            <a href="mailto:yourname@email.com" class="btn">
                Send Me an Email
            </a>

        </div>

    </section>


    <!-- Footer -->
    <footer>
        <p>© 2026 Your Name. All Rights Reserved.</p>
        <p>Designed with HTML & CSS.</p>
    </footer>

</body>
</html>

