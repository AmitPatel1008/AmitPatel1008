<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amit Patel's Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Amit Patel</h1>
    <p>Front-End Developer | Pursuing Graduation in ECE, Expected Completion 2027</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate front-end developer with a strong foundation in HTML, CSS, and JavaScript. I enjoy creating visually appealing and user-friendly websites.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML & CSS</li>
      <li>JavaScript</li>
      <li>Responsive Web Design</li>
      <li>Version Control (Git)</li>
      <li>React.js</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>A personal portfolio website to showcase my projects and skills.</p>
      <a href="#">View Project</a>
    </div>
    <div class="project">
      <h3>Responsive E-commerce Site</h3>
      <p>An e-commerce website built with responsive design principles.</p>
      <a href="#">View Project</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:suraj21amit@gmail.com">suraj21amit@gmail.com</a></p>
    <p>Mobile: <a href="tel:+916387544116">6387544116</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/amit-patel-084a972b4?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">linkedin.com/in/amit-patel</a></p>
  </section>

  <footer>
    <p>&copy; 2024 Amit Patel</p>
  </footer>
</body>
</html>





/* Reset and Basic Styling */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f4f4f4;
}

header {
  text-align: center;
  background-color: #333;
  color: #fff;
  padding: 1.5rem;
}

header h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

/* Section Styling */
section {
  max-width: 800px;
  margin: 2rem auto;
  padding: 1rem;
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
  font-size: 1.8rem;
  color: #333;
  border-bottom: 2px solid #333;
  padding-bottom: 0.5rem;
  margin-bottom: 1rem;
}

#skills ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

#skills li {
  background-color: #e0e0e0;
  padding: 0.5rem 1rem;
  border-radius: 3px;
}

.project {
  margin-top: 1.5rem;
}

.project h3 {
  font-size: 1.5rem;
  color: #555;
}

.project p {
  margin: 0.5rem 0;
}

.project a {
  color: #0066cc;
  text-decoration: none;
}

.project a:hover {
  text-decoration: underline;
}

/* Contact Section */
#contact a {
  color: #0066cc;
  text-decoration: none;
}

#contact a:hover {
  text-decoration: underline;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #333;
  color: #fff;
  margin-top: 2rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  header h1 {
    font-size: 2rem;
  }

  h2 {
    font-size: 1.5rem;
  }
}

