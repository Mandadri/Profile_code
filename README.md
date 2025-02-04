<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Rohith - GitHub Profile</title>
    <style>
        /* General Body and Page Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            min-height: 100vh;
        }

        /* Header Section */
        header {
            background-color: #222;
            color: white;
            padding: 40px;
            text-align: center;
            margin-bottom: 20px;
        }

        header h1 {
            margin: 0;
            font-size: 48px;
            text-transform: uppercase;
            letter-spacing: 3px;
        }

        header p {
            font-size: 20px;
            margin-top: 10px;
        }

        /* Name Grid Styling */
        .name-grid {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            grid-template-rows: auto;
            gap: 10px;
            justify-items: center;
            align-items: center;
            padding: 50px 10%;
            text-align: center;
            background-color: #fff;
            border-bottom: 2px solid #ddd;
        }

        .name-grid h2 {
            font-size: 36px;
            margin: 0;
            color: #222;
            font-weight: bold;
            text-transform: uppercase;
        }

        .name-grid .line {
            width: 100%;
            height: 2px;
            background-color: #1e90ff;
            margin: 10px 0;
        }

        /* Welcome Section */
        .welcome-section {
            background-color: #222;
            color: white;
            padding: 20px 0;
            text-align: center;
            margin-bottom: 30px;
        }

        .welcome-section h3 {
            font-size: 24px;
            margin: 0;
        }

        /* Profile Content Section */
        section {
            padding: 30px;
            background-color: #fff;
        }

        h2 {
            font-size: 28px;
            color: #222;
            margin-bottom: 20px;
        }

        .section-content {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .section-item {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            width: 48%;
        }

        .section-item h3 {
            margin: 0 0 10px;
        }

        .section-item p {
            margin: 10px 0;
        }

        .skills-list, .projects-list {
            list-style: none;
            padding-left: 0;
        }

        .skills-list li, .projects-list li {
            margin: 8px 0;
            font-size: 16px;
        }

        /* Contact Information */
        .contact-info {
            margin-top: 30px;
            text-align: center;
            background-color: #222;
            color: white;
            padding: 20px;
        }

        .contact-info a {
            color: #1e90ff;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #222;
            color: white;
            position: absolute;
            width: 100%;
            bottom: 0;
        }

        footer p {
            margin: 0;
        }

        /* 3D Animation Styling */
        .animation-embed {
            width: 100%;
            height: 500px;
            border: none;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .name-grid {
                grid-template-columns: 1fr;
                padding: 50px 5%;
            }

            .section-content {
                flex-direction: column;
                gap: 10px;
            }

            .section-item {
                width: 100%;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>Rohith</h1>
    <p>Welcome to my GitHub Profile! I'm passionate about coding, data science, and 3D animation.</p>
</header>

<div class="name-grid">
    <div class="line"></div>
    <h2>Rohith</h2>
    <div class="line"></div>
</div>

<div class="welcome-section">
    <h3>Welcome to my GitHub Profile! Feel free to explore my work and projects.</h3>
</div>

<section>
    <h2>About Me</h2>
    <div class="section-content">
        <div class="section-item">
            <h3>Introduction</h3>
            <p>
                I am a passionate software engineer with a deep interest in AI, web development, and 3D animation. I love working on innovative projects and collaborating with others to bring ideas to life. My skills include working with various technologies such as Python, JavaScript, AI frameworks, and 3D design tools.
            </p>
        </div>
        <div class="section-item">
            <h3>Skills & Technologies</h3>
            <ul class="skills-list">
                <li>Python</li>
                <li>JavaScript</li>
                <li>AI & Machine Learning</li>
                <li>3D Animation</li>
                <li>React</li>
                <li>Node.js</li>
                <li>TensorFlow</li>
                <li>Web Development</li>
            </ul>
        </div>
    </div>
</section>

<section>
    <h2>Current Projects</h2>
    <div class="section-content">
        <div class="section-item">
            <h3>Project 1: [Project Name]</h3>
            <p>[Project Description]</p>
            <p>Technologies used: [Technologies]</p>
            <p><a href="[GitHub URL]" target="_blank">View on GitHub</a></p>
        </div>
        <div class="section-item">
            <h3>Project 2: [Project Name]</h3>
            <p>[Project Description]</p>
            <p>Technologies used: [Technologies]</p>
            <p><a href="[GitHub URL]" target="_blank">View on GitHub</a></p>
        </div>
    </div>
</section>

<section>
    <h2>3D Animation Showcase</h2>
    <div class="section-item">
        <h3>Here’s a 3D animation I’ve worked on:</h3>
        <iframe class="animation-embed" src="https://sketchfab.com/models/[Model-ID]/embed" title="3D Model - [Your Model Name]"></iframe>
        <p>You can also view more of my animations on [Portfolio/Website].</p>
    </div>
</section>

<section>
    <h2>Education & Certifications</h2>
    <div class="section-content">
        <div class="section-item">
            <h3>Degree in [Field of Study]</h3>
            <p>[University Name], [Year]</p>
            <p>Certifications: [Certification 1], [Certification 2], [Certification 3]</p>
        </div>
    </div>
</section>

<section>
    <h2>Open to Collaborations</h2>
    <div class="section-item">
        <p>I am always looking for opportunities to collaborate on exciting projects in the fields of AI, web development, and 3D animation.</p>
        <p>If you have an interesting project or need help, feel free to reach out to me via the contact section below.</p>
    </div>
</section>

<section class="contact-info">
    <h2>Contact Information</h2>
    <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/[your-linkedin-profile]" target="_blank">[Your LinkedIn]</a></p>
    <p>GitHub: <a href="https://github.com/[your-github-username]" target="_blank">[Your GitHub]</a></p>
</section>

<footer>
    <p>&copy; 2025 Rohith. All rights reserved.</p>
</footer>

</body>
</html>
