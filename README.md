
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>S. Meenakshi - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #d00031;
        }
        .header {
            background-color: #c4ff4d;
            text-align: center;
            padding: 20px;
        }
        .header h1 {
            margin: 0;
            color: #5a2d0c;
        }
        .header p {
            margin: 5px 0;
            font-size: 18px;
        }
        .navbar {
            display: flex;
            justify-content: center;
            background-color: #900028;
            padding: 10px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
        }
        h2 {
            color: #900028;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            margin: 5px 0;
        }
        .resume-btn {
            display: block;
            text-align: center;
            background: black;
            color: white;
            padding: 10px;
            border-radius: 5px;
            text-decoration: none;
            width: 150px;
            margin: 20px auto;
        }
        .footer {
            background: black;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>S. Meenakshi</h1>
        <p>BCA Student at Madras University</p>
    </div>

    <div class="navbar">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>

    <div class="container">
        <h2 id="about">About Me</h2>
        <p>Currently, I am pursuing my BSc degree. Passionate about coding and technology.</p>

        <h2 id="education">Education</h2>
        <p><strong>Madras University</strong> - Bachelor of Computer Applications (BCA)</p>

        <h2 id="skills">Skills</h2>
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>Computer Architecture</li>
        </ul>

        <h2 id="projects">Projects</h2>
        <ul>
            <li>Hangman Game using Java</li>
        </ul>

        <h2 id="resume">Resume</h2>
        <a href="#" class="resume-btn">Download CV</a>
    </div>

    <div class="footer">
        © 2025 S. Meenakshi
    </div>

</body>
</html>
