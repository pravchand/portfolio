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
    flex-wrap: wrap;
}

.nav li {
    margin: 0 10px;
}

.nav a {
    color: white;
    text-decoration: none;
    padding: 10px 15px;
    display: block;
}

.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
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
    width: calc(33.33% - 20px);
    box-sizing: border-box;
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

/* Tablet Styles */
@media (max-width: 900px) {
    .project {
        width: calc(50% - 20px);
    }
}

/* Mobile Styles */
@media (max-width: 600px) {
    body {
        font-size: 14px; /* Reduce base font size for mobile */
    }

    .container {
        flex-direction: column;
        padding: 0 10px; /* Add minimal padding to container */
    }

    .project {
        width: 100%;
        margin: 10px 0;
        padding: 10px;
        border-radius: 4px; /* Smaller border-radius */
        max-width: 100%; /* Ensure project doesn't exceed screen width */
    }

    .project h3 {
        font-size: 1.2em; /* Smaller heading for mobile */
        margin-bottom: 0.5em;
    }

    .project p {
        font-size: 0.9em; /* Smaller paragraph text */
        line-height: 1.4; /* Adjust line height for readability */
        margin-bottom: 0.8em;
    }

    .project a {
        font-size: 0.9em;
        padding: 8px;
        margin-top: 5px;
    }

    .nav ul {
        flex-direction: column;
        align-items: center;
    }

    .nav li {
        margin: 5px 0;
        width: 100%;
        text-align: center;
    }

    .nav a {
        padding: 8px 0;
    }

    .header {
        padding: 1em 0;
    }

    .header h1 {
        font-size: 1.5em;
    }

    .footer {
        font-size: 0.8em;
        padding: 0.8em 0;
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
