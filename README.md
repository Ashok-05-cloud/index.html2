<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>B. Ashok | Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f7fa;
      color: #222;
      line-height: 1.6;
    }

    header {
      background: #111827;
      color: white;
      padding: 20px 8%;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav h2 {
      color: #38bdf8;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 25px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #38bdf8;
    }

    .hero {
      min-height: 90vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 40px 20px;
      background: linear-gradient(135deg, #e0f2fe, #f8fafc);
    }

    .hero h1 {
      font-size: 50px;
      margin-bottom: 10px;
    }

    .hero h1 span {
      color: #0284c7;
    }

    .hero h3 {
      font-size: 24px;
      color: #555;
      margin-bottom: 20px;
    }

    .hero p {
      max-width: 650px;
      margin: auto;
      color: #555;
    }

    .buttons {
      margin-top: 25px;
    }

    .btn {
      display: inline-block;
      padding: 12px 25px;
      margin: 5px;
      background: #0284c7;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
    }

    .btn:hover {
      background: #0369a1;
    }

    section {
      padding: 70px 8%;
    }

    section h2 {
      text-align: center;
      font-size: 32px;
      margin-bottom: 40px;
      color: #0284c7;
    }

    .about {
      max-width: 800px;
      margin: auto;
      text-align: center;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }

    .skill {
      background: white;
      padding: 15px 25px;
      border-radius: 8px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
      font-weight: bold;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .project {
      background: white;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 3px 12px rgba(0,0,0,0.1);
    }

    .project h3 {
      color: #0284c7;
      margin-bottom: 10px;
    }

    .project a {
      display: inline-block;
      margin-top: 15px;
      color: #0284c7;
      font-weight: bold;
      text-decoration: none;
    }

    .education {
      max-width: 700px;
      margin: auto;
      background: white;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 3px 12px rgba(0,0,0,0.1);
      text-align: center;
    }

    .contact {
      text-align: center;
      background: #e0f2fe;
    }

    .contact a {
      color: #0284c7;
      font-weight: bold;
      text-decoration: none;
    }

    footer {
      background: #111827;
      color: white;
      text-align: center;
      padding: 20px;
    }

    @media (max-width: 700px) {
      nav {
        flex-direction: column;
        gap: 15px;
      }

      nav ul {
        gap: 12px;
        flex-wrap: wrap;
        justify-content: center;
      }

      .hero h1 {
        font-size: 36px;
      }
    }
  </style>
</head>

<body>

  <!-- Navigation -->
  <header>
    <nav>
      <h2>B. Ashok</h2>

      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>


  <!-- Home -->
  <section class="hero" id="home">
    <div>
      <h1>Hi, I'm <span>B. Ashok</span></h1>

      <h3>Computer Science Student | Full Stack Developer</h3>

      <p>
        I am a passionate technology enthusiast interested in
        Full Stack Development, MERN Stack, Web Development,
        and problem solving. I am continuously improving my
        technical skills by building projects and learning new technologies.
      </p>

     <div class="buttons">

  <a class="btn" href="#projects">
    View My Projects
  </a>

  <a class="btn"
     href="https://github.com/Ashok-05-cloud"
     target="_blank">
    GitHub
  </a>

  <a class="btn"
     href="https://www.linkedin.com/in/ashok-kumar-5799a9294"
     target="_blank">
    LinkedIn
  </a>

  <a class="btn"
     href="resume.pdf"
     target="_blank">
    View My Resume
  </a>

  <a class="btn"
     href="resume.pdf"
     download>
    Download Resume
  </a>

</div>
    </div>
  </section>


  <!-- About -->
  <section id="about">
    <h2>About Me</h2>

    <div class="about">
      <p>
        Hello! I am B. Ashok, a Computer Science student with
        a strong interest in software development and modern
        web technologies.
      </p>

      <br>

      <p>
        My current focus is on developing my skills in
        HTML, CSS, JavaScript, React, Node.js, Express.js,
        MongoDB and other Full Stack technologies.
      </p>

      <br>

      <p>
        I am also preparing for GATE 2027 and continuously
        working on improving my programming and computer science
        fundamentals.
      </p>
    </div>
  </section>


  <!-- Skills -->
  <section id="skills">
    <h2>My Skills</h2>

    <div class="skills">

      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">React.js</div>
      <div class="skill">Node.js</div>
      <div class="skill">Express.js</div>
      <div class="skill">MongoDB</div>
      <div class="skill">MERN Stack</div>
      <div class="skill">Git</div>
      <div class="skill">GitHub</div>
      <div class="skill">REST APIs</div>
      <div class="skill">Java</div>

    </div>
  </section>


  <!-- Projects -->
  <section id="projects">
    <h2>My Projects</h2>

    <div class="projects">

      <div class="project">
        <h3>Personal Portfolio</h3>

        <p>
          A responsive personal portfolio website created
          using HTML and CSS and hosted using GitHub Pages.
        </p>

        <a href="https://github.com/Ashok-05-cloud"
           target="_blank">
          View on GitHub →
        </a>
      </div>


      <div class="project">
        <h3>To-Do List</h3>

        <p>
          An interactive To-Do List application built with
          HTML, CSS and JavaScript. Users can add tasks and
          mark them as completed.
        </p>

        <a href="https://github.com/Ashok-05-cloud"
           target="_blank">
          View Project →
        </a>
      </div>


      <div class="project">
        <h3>MERN Social Media Application</h3>

        <p>
          A Full Stack Social Media project focused on learning
          React, Node.js, Express.js, MongoDB and authentication.
        </p>

        <a href="https://github.com/Ashok-05-cloud"
           target="_blank">
          View Project →
        </a>
      </div>


      <div class="project">
        <h3>Budget Tracker</h3>

        <p>
          A web application concept for tracking income,
          expenses and managing personal budgets.
        </p>

        <a href="https://github.com/Ashok-05-cloud"
           target="_blank">
          View Project →
        </a>
      </div>

    </div>
  </section>


  <!-- Education -->
  <section id="education">
    <h2>Education & Goals</h2>

    <div class="education">

      <h3>Computer Science / Information Technology</h3>

      <p>
        Currently pursuing my academic studies and developing
        practical skills in software and web development.
      </p>

      <br>

      <h3>GATE 2027 Aspirant</h3>

      <p>
        Preparing for GATE 2027 with focus on Computer Science
        and Engineering subjects.
      </p>

    </div>
  </section>


  <!-- Contact -->
  <section class="contact" id="contact">

    <h2>Let's Connect</h2>

    <p>
      I am interested in learning, building projects,
      internships and opportunities in software development.
    </p>

    <br>

    <p>
      GitHub:
      <a href="https://github.com/Ashok-05-cloud"
         target="_blank">
        github.com/Ashok-05-cloud
      </a>
    </p>

    <br>

    <p>
      LinkedIn:
      <a href="https://www.linkedin.com/"
         target="_blank">
        Connect with me on LinkedIn
      </a>
    </p>

  </section>


  <!-- Footer -->
  <footer>
    <p>© 2026 B. Ashok. All Rights Reserved.</p>
    <p>Built with HTML & CSS | Hosted on GitHub Pages</p>
  </footer>

</body>
</html>
