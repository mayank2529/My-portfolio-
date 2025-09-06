# My-portfolio-
Hi, I'm Mayank Zende, a graphic designer, photographer, and 3D artist.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mayank Zende Portfolio</title>
  <style>
    /* Basic Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; background-color: #121212; color: #f5f5f5; }

    /* Header */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background-color: #1f1f1f;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #f5f5f5;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover { color: #ffcc00; }

    /* Hero Section */
    .hero {
      text-align: center;
      padding: 100px 20px 50px 20px;
    }
    .hero h1 { font-size: 3em; margin-bottom: 20px; }
    .hero p { font-size: 1.2em; color: #ccc; }

    /* Portfolio Section */
    section { padding: 60px 20px; }
    section h2 { text-align: center; font-size: 2.5em; margin-bottom: 40px; }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .project {
      background-color: #1f1f1f;
      padding: 10px;
      border-radius: 10px;
      overflow: hidden;
      transition: transform 0.3s;
    }
    .project img { width: 100%; height: auto; border-radius: 10px; }
    .project p { text-align: center; margin-top: 10px; font-weight: bold; }
    .project:hover { transform: scale(1.05); }

    /* Skills Section */
    .skills ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .skills li {
      background-color: #1f1f1f;
      padding: 15px 25px;
      border-radius: 20px;
      font-weight: bold;
      transition: 0.3s;
    }
    .skills li:hover { background-color: #ffcc00; color: #121212; }

    /* Contact Section */
    .contact { text-align: center; }
    .contact p { margin-bottom: 10px; }
    .contact a {
      color: #ffcc00;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .contact a:hover { color: #fff; }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background-color: #1f1f1f;
      color: #ccc;
    }

    /* Responsive Adjustments */
    @media(max-width: 600px){
      .hero h1 { font-size: 2em; }
      section h2 { font-size: 2em; }
    }
  </style>
</head>
<body>

  <header>
    <h3>Mayank Zende</h3>
    <nav>
      <a href="#portfolio">Portfolio</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Hi, I'm Mayank</h1>
    <p>Graphic Designer | Photographer | 3D Artist | Freelancer</p>
  </div>

  <section id="portfolio">
    <h2>My Work</h2>
    <div class="projects">
      <div class="project">
        <img src="project1.jpg" alt="Project 1">
        <p>Graphic Design</p>
      </div>
      <div class="project">
        <img src="project2.jpg" alt="Project 2">
        <p>Photography</p>
      </div>
      <div class="project">
        <img src="project3.jpg" alt="Project 3">
        <p>3D Blender</p>
      </div>
      <!-- Add more projects as needed -->
    </div>
  </section>

  <section id="skills" class="skills">
    <h2>Skills</h2>
    <ul>
      <li>Graphic Design</li>
      <li>Photography</li>
      <li>3D Modeling (Blender)</li>
      <li>Coding</li>
      <li>Freelancing</li>
    </ul>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:mayank@example.com">mayank@example.com</a></p>
    <p>Instagram: <a href="https://instagram.com/PixelPalette" target="_blank">@PixelPalette</a></p>
  </section>

  <footer>
    &copy; 2025 Mayank Zende. All rights reserved.
  </footer>

</body>
</html>
