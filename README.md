<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
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
            flex-wrap: wrap; /* Allow items to wrap on smaller screens */
            justify-content: space-around; /* Space out items */
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 15px;
        }

        .project {
            background-color: white;
            border-radius: 8px;
            padding: 15px;
            margin: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            width: 30%; /* Set width for each project */
            box-sizing: border-box; /* Include padding in width calculation */
        }

        .project h3 {
            margin-top: 0;
            font-size: 1.5em;
        }

        .project p {
            margin-bottom: 10px;
            font-size: 1em;
        }

        .project a {
            display: block;
            text-align: center;
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
        }

        .project a:hover {
            background-color: #45a049;
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
            .container {
                flex-direction: column; /* Stack projects vertically on mobile */
            }

            .project {
                width: 100%; /* Full width on small screens */
                margin: 10px 0; /* Adjust margins for small screens */
            }

            .project h3 {
                font-size: 1.3em; /* Smaller headings on small screens */
            }

            .project p {
                font-size: 0.9em; /* Smaller description text */
            }

            .project a {
                font-size: 0.9em; /* Adjust button size */
                padding: 8px;
            }

            .footer {
                font-size: 0.9em; /* Adjust footer text size */
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>My Portfolio</h1>
        <p>Welcome to my portfolio! Here are some of my projects.</p>
    </header>
    <nav class="nav">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
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
            <a href="#" target="_blank">View Project</a>
        </section>
        <section class="project">
            <h3>Project Title 3</h3>
            <p>Description of your project goes here. You can include technologies used, challenges faced, and what you learned.</p>
            <a href="#" target="_blank">View Project</a>
        </section>
    </div>
    <footer class="footer">
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>
