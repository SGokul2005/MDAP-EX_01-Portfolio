# MDAP-EX_01-Portfolio
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TECH APPLY</title>
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      color: #333;
      background: #f9f9f9;
    }

    header {
      background: #e70808;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 30px;
    }

    .logo {
      font-size: 1.5em;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    .nav-links li a {
      color: rgba(255, 255, 255, 0.375);
      text-decoration: none;
      transition: color 0.3s ease;
    }

    .nav-links li a:hover {
      color: #00bcd4;
    }

    .header-content {
      margin-top: 20px;
    }

    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }

    .project {
      background: white;
      padding: 20px;
      margin: 15px 0;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }

    .project:hover {
      transform: scale(1.02);
    }

    footer {
      background: #352d2d;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <h1 class="logo">My Information</h1>
      <ul class="nav-links">
        <li><a href="#intro">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#my projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="header-content">
      <h2>Hello, I'm GOKUL S webdeveloper</h2>
      <p>I build clean, user-friendly websites.</p>
    </div>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Iam interested in coding and creating beautiful, functional websites with HTML, CSS, and JavaScript.</p>
  </section>

  <section id="my projects">
    <h2>My Projects</h2>
    <div class="project">
      <h3>Project One</h3>
      <p>A responsive landing page made using Flexbox.</p>
    </div>
    <div class="my project">
      <h3>Project Two</h3>
      <p>A personal blog styled with modern CSS.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: gokulgoku9655@gmail.com</p>
  </section>

 
</body>
</html>


## OUTPUT
image 1
![Screenshot 2025-04-30 084017](https://github.com/user-attachments/assets/834e9a87-2e67-49c4-9635-f15ab4eb6183) 
image 2
![Screenshot 2025-04-30 084108](https://github.com/user-attachments/assets/c15e7f3b-2aa9-4e14-bf81-edb1daf19229)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
