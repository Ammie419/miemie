# miemie
Portfolio 
<!DOCTYPE html>
<html>
<html lan="eng">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Mimi's Portfolio</title>
</head>
<body>
<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  color: white;
  background: dimgrey;
  justify-content: center;
}

.container {
  max-width: 1000px;
  margin: auto;
  padding: 40px 20px;
}

header {
  background: linear-gradient(to right, #ff6a00, #ee0979);
  color: white;
  text-align: center;
  padding: 60px 20px;
}

header h1 {
  font-size: 3rem;
  margin-bottom: 10px;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
  transition: opacity 0.3s;
}

nav a:hover {
  opacity: 0.7;
}

.section {
  background: #fff;
  padding: 60px 0;
}

.section.alt {
  background: #f0f0f0;
}

h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  text-align: center;
}

p {
  margin-bottom: 15px;
  text-align: center;
}

.projects {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.project-card {
  background: dimgrey;
  border: 2px solid #eee;
  border-radius: 8px;
  padding: 20px;
  width: 300px;
  transition: transform 0.3s, box-shadow 0.3s;
  color: white;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
}

.skills-list {
  list-style: none;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 15px;
}

.skills-list li {
  background: #333;
  color: white;
  padding: 10px 20px;
  border-radius: 20px;
  font-size: 0.95rem;
  }
  footer {
    padding: 20px;
    background: #333;
    text-align: center;
    color:white;
  }
  h2 {
    color: black;
  }
  h3 {
    text-align: center;
  }
 
    .circle-image {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      border: 5px solid #6C6D6E;
      object-fit: cover;        
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
      margin: auto;
      display: block;
    }
  </style>
    <div class="container">
      <h1>Mimi</h1>
      <p>Aspiring Software Developer</p>
      <nav>
        <a href="#about">About</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section id="about" class="section">
    <div class="container">
      <img src="powerranger.jpg" alt="My profile" class="circle-image">
      <h2>About Me</h2>
      <p style="color:black">Hi, I'm Mimi — an aspiring software developer. I'm passionate about creating efficient user-friendly applications and i'm excited to grow into a professional developmental role.</p>
    </div>
  </section>

  <section id="portfolio" class="section alt">
    <div class="container">
      <h2>Experience</h2>
      <div class="projects">
        <div class="project-card">
          <h3>PAST</h3>
          <p> I attended a local computer training center where i learnt basic computer operations and applications like MS word, excel, corel draw and powerpoint.</p>
        </div>
        <div class="project-card">
          <h3>PRESENT</h3>
          <p>Currently, i'm undergoing self training on how to use programming languages like HTML, CSS, python and JavaScript to create websites using websites like <strong><a style="color:white" href="http://www.w3schools.com/">w3schools</a></strong> as an aid. As a way of practice i've managed to create a personal profile and designed an AI chatbox.</p> 
        </div>
        <div class="project-card">
          <h3>FUTURE</h3>
          <p>After growing my skills in programming languages, frameworks, design principles, deployment and reaching a reasonable amount of expertise in them, i intend to build an educational app for skill acquisition.</p>
      </div>
    </div>
  </section>

  <section id="skills" class="section">
    <div class="container">
      <h2>Skills</h2>
      <ul class="skills-list">
        <li>HTML</li>
        <li>CSS</li>
        <li>Python</li>
        <li>JavaScript</li>
        <li>Graphic design</li>
      </ul>
    </div>
  </section>

  <section id="contact" class="section alt">
    <div class="container">
      <h2 style="color:black">Contact</h2>
      <p style="color:black">Email: <a href="mailto:your@email.com">olominamiracle@gmail..com</a></p>
      <p style="color: black">Phone: 09014231355, 07040750718</p>
    </div>
  </section>

  <footer>
    <p>© 2025 Mimi. Made with 🤍</p>
  </footer>
</body>
</html>
