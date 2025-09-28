<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mario Magdy | Portfolio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: "Segoe UI", sans-serif; background: #f8fafc; color: #333; }

    /* Navbar */
    nav {
      background: #0077b6;
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav h2 { color: #fff; }
    nav ul { display: flex; gap: 1.5rem; list-style: none; }
    nav ul li a { color: #fff; text-decoration: none; font-weight: 500; transition: color .3s; }
    nav ul li a:hover { color: #ffd60a; }

    /* Hero */
    .hero {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      padding: 3rem 2rem;
      background: linear-gradient(135deg, #0077b6, #00b4d8);
      color: #fff;
      text-align: center;
    }
    .hero img {
      width: 300px;
      height: 300px;
      border-radius: 50%;
      object-fit: cover;
      margin: 1rem;
      border: 5px solid #fff;
      box-shadow: 0 6px 15px rgba(0,0,0,0.2);
    }
    .hero-text { max-width: 600px; margin: 1rem; }
    .hero-text h1 { font-size: 2.5rem; margin-bottom: .5rem; }
    .hero-text p { font-size: 1.2rem; }

    /* Sections */
    .container { width: 90%; max-width: 1000px; margin: 2rem auto; }
    section { margin-bottom: 2rem; padding: 2rem; background: #fff;; box-shadow: 0 4px 8px rgba(0,0,0,0.05); }
    section h2 { margin-bottom: 1rem; color: #0077b6; }

    ul { list-style: none; }
    ul li { margin-bottom: .5rem; }

    /* Skills */
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem;
    }
    .skill {
      background: #e9f5ff;
      padding: 1rem;
      text-align: center;
      border-radius: 8px;
      transition: transform 0.2s, background .3s;
    }
    .skill:hover { transform: translateY(-5px); background: #d9f0ff; }

    /* Projects */
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }
    .project-card {
      background: #f1f9ff;
      border-radius: 12px;
      padding: 1.5rem;
      transition: transform .3s, box-shadow .3s;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }
    .project-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }
    .project-card h3 { color: #0077b6; margin-bottom: .5rem; }
    .project-card p { font-size: 0.95rem; margin-bottom: 1rem; }
    .project-card a {
      display: inline-block;
      padding: 0.5rem 1rem;
      background: #0077b6;
      color: #fff;
      border-radius: 6px;
      text-decoration: none;
      font-size: 0.9rem;
      transition: background .3s;
    }
    .project-card a:hover { background: #005f8a; }

         .fade-in ul li a {
      display: inline-block;
      padding: 0.5rem 1rem;
      background: #0077b6;
      color: #fff;
      border-radius: 6px;
      text-decoration: none;
      font-size: 0.9rem;
      transition: background .3s;
    }
      .fade-in ul li a :hover { background: #005f8a; }
    /* Contact */
    .contact { text-align: center; background: #0077b6; color: #fff; padding: 2rem; border-radius: 12px; }
    .contact a { color: #ffd60a; font-weight: bold; }
    .contact h2 { color: white; font-weight: bold; }

    /* Fade Animation */
    .fade-in { opacity: 0; transform: translateY(20px); transition: all .6s ease; }
    .fade-in.show { opacity: 1; transform: translateY(0); }

    @media (max-width: 768px) {
      nav ul { display: none; }
      .hero { flex-direction: column; text-align: center; }
      .hero-text h1 { font-size: 2rem; }
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <h2>Mario Magdy</h2>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#contact">Contact</a></li>
     <li><a href="CV_Mario Magdy.pdf">CV</a></li>
    </ul>
  </nav>

  <!-- Hero -->
  <section class="hero">
    <img src="photo_5847992123109002581_y.jpg" alt="Mario Magdy">
    <div class="hero-text">
      <h1>Mario Magdy</h1>
      <p>Junior Full-Stack Developer | Communication Engineer</p>
    </div>
  </section>

  <!-- About -->
  <div class="container">
    <section id="about" class="fade-in">
      <h2>About Me</h2>
      <p>
   I am a junior full-stack developer currently in the DEPI 6-month program. With a
background in communication engineering, I bring both technical and problem-solving skills. I
am also professional in creating impactful presentations with PowerPoint and Word.
I inspire clients by combining development expertise with clear communication, delivering
solutions that are both functional and easy to understand.
      </p>
    </section>

    <!-- Education -->
    <section id="education" class="fade-in">
      <h2>Education</h2>
      <ul>
        <li>Electronics & Communication, Alexandria University (GPA: 3.8)</li>
        <li>Projects using MATLAB, VSCODE, MULTISIM, STK, DIALUX, AUTOCAD, ORCAD</li>
      </ul>
    </section>

    <!-- Experience -->
    <section id="experience" class="fade-in">
      <h2>Experience & Courses</h2>
      <ul>
        <li>Digital Egypt Pioneers Program (6/2025 - 12/2025)</li>
        <li>Oil Company Training (7/2024)</li>
        <li>Copper Company Training (8/2024)</li>
        <li>Maths & Algorithms Course for AI Competition (2/2024)  <a href="aiu.jfif"> certificate</a></li>
        <li>I judged a competition of robot challenge in coding (2025,2024)    <a href="1758565757428.jfif"> certificate</a></li>
    
        <li>Third place in a competition of international robot Challenge in sumo mega as a coach (2024)  <a href="sumo.jfif"> certificate</a></li>
        <li>Participated in Global Robotics Challenge in coding and won best performance award (2024) <a href="grc.jfif">certificate </a></li></li>
        <li>First place in a competition of robot challenge in web development in the republic as a coach (2023) <a href="web1.jfif"> certificate</a></li></li>
      </ul>
    </section>

    <!-- Projects -->
    <section id="projects" class="fade-in">
      <h2>Projects</h2>
      <div class="projects-grid">
        <div class="project-card">
          <h3>Website</h3>
          <p>this is a website using html and css</p>
          <a href="web.html">View Details</a>
        </div>
        <div class="project-card">
          <h3>lollipop</h3>
          <p>this is a drawing using html and css</p>
          <a href="lollipop.html">View Details</a>
        </div>
        <div class="project-card">
          <h3>Watch</h3>
          <p>this is a drawing using html and css</p>
          <a href="watch.html">View Details</a>
        </div>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="fade-in">
      <h2>Skills</h2>
      <div class="skills-grid">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Python</div>
        <div class="skill">SQL</div>
        <div class="skill">C / C#</div>
        <div class="skill">Matlab</div>
        <div class="skill">AutoCAD</div>
        <div class="skill">Problem Solving</div>
        <div class="skill">Soft Skills</div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="contact fade-in">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:mariomagdy887@gmail.com">mariomagdy887@gmail.com</a></p>
      <p>Phone: <a href="#">01228469938</a></p>
      <p>linkedin: <a href="https://www.linkedin.com/in/mario-magdy-6063082b8?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Mario Magdy</a></p>
    </section>
  </div>

  <!-- JS -->
  <script>
    const sections = document.querySelectorAll('.fade-in');
    const revealOnScroll = () => {
      sections.forEach(sec => {
        const rect = sec.getBoundingClientRect();
        if (rect.top < window.innerHeight - 100) {
          sec.classList.add('show');
        }
      });
    };
    window.addEventListener('scroll', revealOnScroll);
    revealOnScroll();
  </script>
</body>
</html>
