<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1.5em 0;
        }

        .nav {
            background-color: #333;
        }

        .nav ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        .nav li {
            margin: 0 10px;
        }

        .nav a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
        }

        .container {
            display: flex;
            flex-direction: column;
            margin: 20px;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }

        .project {
            background-color: white;
            border-radius: 8px;
            padding: 15px;
            margin: 10px 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .project h3 {
            margin-top: 0;
            font-size: 1.5em;
        }

        .footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: relative;
            clear: both;
        }

        /* Mobile Styles */
        @media (max-width: 600px) {
            .nav ul {
                flex-direction: column; /* Stack nav items vertically on small screens */
            }

            .nav li {
                margin: 10px 0;
            }

            .container {
                margin: 0 5px; /* Reduce margin on smaller screens */
                padding: 0 10px; /* Add padding to ensure content doesn't touch the screen edge */
            }

            .project {
                padding: 10px;
                margin: 15px 0;
            }

            .project h3 {
                font-size: 1.3em; /* Smaller headings on small screens */
            }

            .footer {
                font-size: 0.9em; /* Adjust footer text size */
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Praveen C Devarajan</h1>
        <p>Welcome to my portfolio! Here are some of my projects.</p>
    </header>
    <nav class="nav">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Resume</a></li>
            <li><a href="#">Projects</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <div class="container">
        <section class="project">
            <h3>Project Title 1</h3>
            <p>Description of your project goes here. You can include technologies used, challenges faced, and what you learned.</p>
            <a href="#" target="_blank">View Project</a>
        </section>
        <section class="project">
            <h3>Project Title 2</h3>
            <p>Description of your project goes here. You can include technologies used, challenges faced, and what you learned.</p>
            <a href="https://github.com/pravchand/energy_project" target="_blank">View Project</a>
        </section>
        <section class="project">
            <h3>Project Title 3</h3>
            <p>Description of your project goes here. You can include technologies used, challenges faced, and what you learned.</p>
            <a href="#" target="_blank">View Project</a>
        </section>
        <!-- Add more projects as needed -->
    </div>
    <footer class="footer">
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>
