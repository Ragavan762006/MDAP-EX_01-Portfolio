# MDAP-EX_01-Portfolio
## Date:10-08-2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">My Portfolio</div>
        <nav>
            <a href="index.html">Home</a>
            <a href="skills.html">Skills</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <section>
        <h2>I am Ragavan</h2>
        <p class="intro">
            I am an aspiring frontend developer who enjoys making websites that look good and are easy to use. 
            I work with HTML, CSS, and JavaScript to create responsive and user-friendly pages. 
            I like designing layouts that work well on all devices. 
            I enjoy learning new skills and keeping up with modern web trends. 
            My goal is to keep improving and building better websites.
        </p>

         <a  class="skill" href="skills.html">skill</a>
        <a class="Contact" href="contact.html">Contact</a>
        
        <div class="profile-links">
            <a href="https://github.com/Ragavan762006" target="_blank">
                <img src="https://cdn-icons-png.flaticon.com/512/733/733553.png" alt="GitHub">
            </a>
            <a href="https://www.linkedin.com/in/ragavan-e-3793652b7/" target="_blank">
                <img src="https://cdn-icons-png.flaticon.com/512/733/733561.png" alt="LinkedIn">
            </a>
        </div>

        <img src="wave (2).svg" alt="wave background" class="wave">
    </section>

</body>
</html>

```
## skills.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio - Skills</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">My Portfolio</div>
        <nav>
            <a href="index.html">Home</a>
            <a href="skills.html">Skills</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <section>
        <h2>My Skills</h2>
        <div class="skills-container">
            <div class="skill-box">HTML</div>
            <div class="skill-box">Css</div>
            <div class="skill-box">JavaScript</div>
            <div class="skill-box">Java Programming</div>
            <div class="skill-box">Python</div>
            <div class="skill-box">Communication</div>
            
        </div>
        <h2>Certifications</h2>
        <div class="cert">
            <div class="cert-box">INTRODUCTION TO IOT- Certified by NPTEL</div>
            <div class="cert-box">DATABASE MANAGEMENT SYSTEM - certified by coursera</div>
            <div class="cert-box">DATA ANALYTICS WITH PYTHON-Certified by NPTEL</div>
            <div class="cert-box">OCI AI FOUNDATIONS - Oracle certificate</div>
        </div>
    </section>

</body>
</html>

```
## Style.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #0a1f44; 
    color: white;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(92, 127, 188, 0.45); 
    padding: 15px 30px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.3);
}

.logo {
    font-weight: bold;
    font-size: 20px;
    color: white;
}
.intro
{
    font-style:oblique;
    font-size:25px;
    font-family:'Times New Roman', Times, serif;
}

nav a {
    text-decoration: none;
    color: #d4e3ff; 
    margin-left: 20px;
    font-weight: 500;
    transition: 0.3s;
}

nav a:hover {
    color: #4da3ff; 
}

section {
    padding: 50px 20px;
    max-width: 800px;
    margin: auto;
}

 .profile-links {
    margin-top: 15px;
    display: flex;
    gap: 20px;
}

.profile-links img {
    width: 40px;
    height: 40px;
    transition: transform 0.3s;
}

.profile-links img:hover {
    transform: scale(1.1);
}

.wave {
    margin-top: 40px;
    width: 100%;
}

h1, h2 {
    color: #ffffff;
}
.home-section {
    position: relative; 
    padding-bottom: 100px; 
}

.wave {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;

}

.wave
{
    padding: 0px;
    padding-right: 0%;
}
h1, h2 {
    color: #ffffff;
}

button, .btn {
    background: #4da3ff;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 6px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover, .btn:hover {
    background: #2e7bd8;
}
.skills-container {

    display:flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 20px;
    padding: 10px;
    font-size: larger;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.skill-box {
    background: rgba(255, 255, 255, 0.1);
    padding: 20px;
    border-radius: 8px;
    flex: 1 1 150px;
    text-align: center;
    border: 1px solid rgba(255,255,255,0.2);
    color: white;
    font-weight: bold;
    transition: 0.3s;
}

.skill-box:hover {
    background: rgba(77, 163, 255, 0.2);
    transform: scale(1.05);
    border-color: #4da3ff;
}
.cert
{
    display:grid;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 20px;
    padding: 10px;
    font-size: larger;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.cert-box{
    background: rgba(255, 255, 255, 0.1);
    padding: 20px;
    border-radius: 8px;
    flex: 1 1 150px;
    text-align: center;
    border: 1px solid rgba(255,255,255,0.2);
    color: white;
    font-weight: bold;
    transition: 0.3s;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.cert-box:hover
 {
    background: rgba(94, 153, 216, 0.2);
    transform: scale(1.05);
    border-color: #4da3ff;
}
p
{
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 25px;

}
.Contact {
    display: inline-block;
    background: rgba(196, 181, 181, 0.1);
    padding: 10px 20px;
    border-radius: 8px;
    text-align: center;
    border: 1px solid rgba(255,255,255,0.2);
    color: white !important;
    font-weight: bold;
    transition: 0.3s;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    text-decoration: none !important;
    cursor: pointer;
    margin-top: 20px;
}

.Contact:hover {
    background: #ffffff;
    color: #0a1f44 !important;
    transform: scale(1.05);
    border-color: #4da3ff;
}

.skill {
    display: inline-block;
    background: rgba(196, 181, 181, 0.1);
    padding: 10px 25px;
    padding-right: 25px;
    border-radius: 8px;
    text-align: center;
    border: 1px solid rgba(255,255,255,0.2);
    color: white !important;
    font-weight: bold;
    transition: 0.3s;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    text-decoration: none !important;
    cursor: pointer;
    margin-top: 20px;
}

.skill:hover {
    background: #ffffff;
    color: #0a1f44 !important;
    transform: scale(1.05);
    border-color: #4da3ff;
}
```
## OUTPUT
![WhatsApp Image 2025-08-10 at 21 07 09_cc0f2fe0](https://github.com/user-attachments/assets/0fb11892-d3c0-4255-86c2-5059228de7bd)
![WhatsApp Image 2025-08-10 at 21 07 30_897a5182](https://github.com/user-attachments/assets/61a3f00f-dd87-4682-8767-ca8e62df3db9)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
