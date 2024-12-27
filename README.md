<!DOCTYPE html>
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
            background-color: #f0f4f8;
        }

        header {
            background: linear-gradient(90deg, #4a90e2, #2a3e52);
            color: #fff;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            margin: 5px 0 0;
            font-size: 1.2rem;
        }

        nav {
            display: flex;
            justify-content: center;
            background: #2a3e52;
            padding: 10px 0;
        }

        nav a {
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
            font-size: 0.9rem;
        }

        nav a:hover {
            background: #4a90e2;
            border-radius: 4px;
        }

        section {
            padding: 20px;
        }

        .container {
            max-width: 1100px;
            margin: auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #4a90e2;
            border-bottom: 2px solid #2a3e52;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }

        .card {
            background: #eef2f5;
            padding: 15px;
            margin: 15px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .card h3 {
            margin-top: 0;
            color: #2a3e52;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            background: #d9e4ea;
            margin: 5px 0;
            padding: 10px;
            border-radius: 4px;
        }

        ul li:hover {
            background: #c4d4df;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #2a3e52;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer a {
            color: #4a90e2;
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

            nav a {
                font-size: 0.8rem;
                padding: 8px 12px;
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
            <p>Hello! I'm Gabe Hill, a dedicated Compensation Analyst with a Bachelor of Science in Human Resource Development from Texas A&M University. I have a passion for optimizing employee compensation strategies and fostering organizational growth. Let me help your company thrive!</p>
        </div>
    </section>

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
