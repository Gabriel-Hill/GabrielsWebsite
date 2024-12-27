<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gabe Hill - Career Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background-color: #f8fafc;
        }

        header {
            background-color: #1e2a38;
            color: #fff;
            padding: 40px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 2.8rem;
            margin: 0;
        }

        header p {
            font-size: 1.2rem;
            margin-top: 10px;
        }

        nav {
            background-color: #ffffff;
            border-bottom: 1px solid #e5e7eb;
            padding: 10px 20px;
            display: flex;
            justify-content: center;
            gap: 15px;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav a {
            color: #1e2a38;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 15px;
            border-radius: 5px;
        }

        nav a:hover {
            background-color: #e5e7eb;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        section:nth-child(even) {
            background-color: #f1f5f9;
        }

        h2 {
            font-size: 2.2rem;
            color: #1e2a38;
            margin-bottom: 20px;
        }

        .card {
            background-color: #ffffff;
            border: 1px solid #e5e7eb;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            text-align: left;
        }

        .card h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: #1e2a38;
        }

        ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        ul li {
            background-color: #e5e7eb;
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
        }

        ul li:hover {
            background-color: #d1d5db;
        }

        footer {
            background-color: #1e2a38;
            color: #ffffff;
            text-align: center;
            padding: 20px 0;
        }

        footer a {
            color: #66b2ff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            header p {
                font-size: 1rem;
            }

            nav {
                flex-wrap: wrap;
            }

            .card {
                margin: 20px 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Gabe Hill</h1>
        <p>Compensation Analyst | HR Professional | Texas A&M Graduate</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>

   <section id="about">
    <div class="container">
        <h2>About Me</h2>
        <p>I am a dedicated and hardworking professional who thrives on achieving both personal and professional goals. As a devoted father. I find immense motivation in setting an example of perseverance, commitment, and balance. My son inspires me every day to be the best version of myself, both at work and in life.</p>

        <p>Outside of my professional endeavors, I am deeply passionate about fitness. I am an avid weightlifter and marathon runner, constantly challenging myself to push boundaries and improve. Whether I’m training for a new personal best in the gym or crossing the finish line of a race, I bring the same level of discipline, resilience, and focus that I apply to my career.</p>

        <p>I believe in giving my all to everything I do and value hard work, consistency, and a positive outlook. With a strong sense of purpose and drive, I strive to balance my personal aspirations with professional excellence, always keeping my family and goals at the heart of everything I pursue.
    <section id="experience">
        <div class="container">
            <h2>Experience</h2>

            <div class="card">
                <h3>Compensation Analyst - indiGO Auto Group</h3>
                <p><strong>Location:</strong> Houston, TX</p>
                <p>Collaborated with the Corporate Board to analyze data, ensuring decision-making aligned with organization goals. Evaluated pay practices to identify discrepancies, ensuring compliance with state and federal regulations. Led the implementation of a company-wide compensation plan with new state-specific labor laws, including sick time policies and minimum wage increases.</p>
            </div>

            <div class="card">
                <h3>Compensation Analyst - Lockton</h3>
                <p><strong>Location:</strong> Remote</p>
                <p>Collaborated with consultants to support various projects by gathering, organizing, and analyzing data. Administered various client compensation merit and bonus programs in congruence with client agreements. Assisted with impact analysis assessments of current compensation levels and pay mix.</p>
            </div>

            <div class="card">
                <h3>Benefits Representative - Lockton</h3>
                <p><strong>Location:</strong> Remote</p>
                <p>Resolved benefits-related queries during open enrollment for 80+ clients, consistently receiving positive feedback. Collaborated with other departments to resolve complex issues effectively.</p>
            </div>

            <div class="card">
                <h3>HR Assistant - Texas A&M Engineering Experiment Station</h3>
                <p><strong>Location:</strong> College Station, TX</p>
                <p>Onboarded 500+ employees during bi-monthly hiring events, conducting seminars to inform new staff about policies. Created 11 position titles by forecasting labor demand and pricing roles based on market trends.</p>
            </div>
        </div>
    </section>

    <section id="education">
        <div class="container">
            <h2>Education</h2>

            <div class="card">
                <h3>Texas A&M University</h3>
                <p>Bachelor of Science in Human Resource Development</p>
                <p>Graduated: December 2023 | GPA: 3.7</p>
            </div>
        </div>
    </section>

    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>Compensation Analysis</li>
                <li>Data Analytics</li>
                <li>Employee Relations</li>
                <li>HR Compliance</li>
                <li>Communication and Mediation</li>
                <li>Proficiency in Excel, PowerPoint, and HRIS systems</li>
            </ul>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact</h2>
            <p><strong>Email:</strong> <a href="mailto:ghilltx12@gmail.com">ghilltx12@gmail.com</a></p>
            <p><strong>Phone:</strong> (469) 667-3021</p>
            <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/gabehill" target="_blank">linkedin.com/in/gabehill</a></p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Gabe Hill. All rights reserved. | <a href="#">Back to top</a></p>
    </footer>
</body>
</html>
