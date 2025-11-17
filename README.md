<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Mohamed Atlam CV</title>
    <link rel="icon" href="Images/icon-cv.png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:ital,opsz,wght@0,18..144,300..900;1,18..144,300..900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: "Merriweather", serif;
            background-color: #f6f6f6;
            margin: 0;
            padding: 20px;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 5px 5px 20px rgba(0,0,0,0.2);
            padding: 30px;
        }
        h1, h2, h3 {
            color: #222;
        }
        h1 {
            text-align: center;
            margin-bottom: 5px;
        }
        h2 {
            margin-top: 30px;
            border-bottom: 2px solid #ecdccf;
            padding-bottom: 5px;
        }
        p, li {
            line-height: 1.5;
            font-size: 1rem;
        }
        ul {
            margin-left: 20px;
        }
        a {
            color: #d97706;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .screenshot {
            display: block;
            margin: 20px auto;
            max-width: 250px;
            border-radius: 10px;
            box-shadow: 3px 3px 10px rgba(0,0,0,0.2);
        }
        .technologies, .project-structure, .features, .usage {
            margin-top: 20px;
        }
        pre {
            background: #f0f0f0;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9rem;
            color: grey;
        }
        .live-demo {
            display: block;
            margin: 10px 0;
            font-weight: bold;
            font-size: 1.1rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Mohamed Atlam - Simple CV</h1>
        <img src="Images/icon-cv.png" alt="CV Icon" class="screenshot">

        <p>A <strong>simple and responsive CV</strong> built with HTML, CSS, and Font Awesome. This project showcases personal information, skills, education, and experience in a clean layout.</p>

        <h2>🌐 Live Demo</h2>
        <a href="https://cv-mohamed-atlam.netlify.app/" class="live-demo" target="_blank"><i class="fa-solid fa-arrow-up-right-from-square"></i> View Live Demo</a>

        <h2>🖼 Project Screenshot</h2>
        <img src="Images/my-img.jpg" alt="My Image" class="screenshot">

        <h2>🛠 Technologies Used</h2>
        <ul class="technologies">
            <li>HTML5 - Semantic structure of the CV</li>
            <li>CSS3 - Styling, responsive design, and layout</li>
            <li>Font Awesome - Icons for contact info and social links</li>
            <li>Google Fonts - Merriweather font for typography</li>
        </ul>

        <h2>📂 Project Structure</h2>
        <pre class="project-structure">
CV-Simple/
│
├── index.html           # Main HTML file
├── CSS/
│   └── style.css        # CSS styling file
├── Images/
│   ├── icon-cv.png      # Favicon
│   └── my-img.jpg       # Profile picture
        </pre>

        <h2>✨ Features</h2>
        <ul class="features">
            <li>Responsive Design: Works perfectly on mobile, tablet, and desktop.</li>
            <li>Skills & Languages: Visual representation using progress bars.</li>
            <li>Experience & Education: Organized sections with clear formatting.</li>
            <li>Contact Info: Phone, email, and address with icons.</li>
        </ul>

        <h2>📌 Usage</h2>
        <pre class="usage">
1. Clone the repository:
git clone https://github.com/your-username/cv-simple.git

2. Open index.html in any web browser.
3. Customize content, images, and styling as needed.
        </pre>

        <h2>📚 About Me</h2>
        <p>I am a <strong>Front-End Developer</strong> with experience in HTML, CSS, JavaScript, React.js, and Bootstrap. I build responsive and user-friendly interfaces with clean and maintainable code.</p>

        <div class="footer">
            <p>Mohamed Atlam | Front-End Developer</p>
        </div>
    </div>
</body>
</html>
