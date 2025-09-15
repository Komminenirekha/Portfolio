# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kommineni Rekha Chowdary - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      color: #222;
      background-color: #fff;
      line-height: 1.6;
    }

    header {
      background: #1e3a8a;
      color: #fff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      margin: 0;
      font-size: 1.6rem;
    }

    nav a {
      margin-left: 20px;
      color: #fff;
      font-weight: bold;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }

    section {
      max-width: 1000px;
      margin: 50px auto;
      padding: 0 20px;
      text-align: center;
    }

    h2 {
      color: #1e40af;
      font-size: 2rem;
    }

    h3 {
      color: #333;
      margin-top: 15px;
    }

    .section-divider {
      height: 2px;
      width: 80px;
      background: #1e40af;
      margin: 10px auto 20px auto;
    }

    .profile-img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      border: 3px solid #1e40af;
      object-fit: cover;
      margin-bottom: 15px;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      background: #f8f9fa;
      border-radius: 10px;
      padding: 20px;
      margin: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      flex: 1 1 280px;
      text-align: left;
    }

    ul {
      text-align: left;
      padding-left: 20px;
    }

    button {
      background: #1e40af;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 25px;
      margin: 10px 5px;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background: #2563eb;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1e3a8a;
      color: #fff;
      margin-top: 40px;
    }

    @media(max-width:768px) {
      header {
        flex-direction: column;
        text-align: center;
      }
      nav {
        margin-top: 10px;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Kommineni Rekha Chowdary</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#education">Education</a>
      <a href="#skills">Skills</a>
      <a href="#experience">Experience</a>
      <a href="#certifications">Certifications</a>
      <a href="#services">Services</a>
      <a href="#projects">Projects</a>
      <a href="#resume">Resume</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Home -->
  <section id="home">
    <img src="https://i.ibb.co/Q7T3dndL/IMG-20250514-103030.jpg" alt="Rekha" class="profile-img">
    <h2>Hello, I'm Rekha</h2>
    <p>Salesforce Developer & Administrator | Java, Python, SQL | CRM & Business Process Improvement</p>
    <a href="#contact"><button>Get In Touch</button></a>
    <a href="https://drive.google.com/file/d/1RXs2nhh9wJCX_vbnm56g5hHIKDuL-m6F/view?usp=drive_link" target="_blank">
      <button>Download Resume</button>
    </a>
  </section>

  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <div class="section-divider"></div>
    <p>I am a Salesforce Developer and Administrator with expertise in Java, Python, and SQL, specializing in CRM solutions, data analysis, and business process improvement. Passionate about continuous learning and innovation, I aim to solve complex problems and drive efficiency.</p>
    <div class="cards">
      <div class="card">Problem Solver</div>
      <div class="card">Innovation Focused</div>
      <div class="card">Continuous Learner</div>
      <div class="card">Development Expertise: Salesforce, Java, Python, SQL</div>
      <div class="card">CRM Solutions: Data Analysis & Management</div>
      <div class="card">Process Improvement & Optimization</div>
      <div class="card">Collaboration: Team Leadership & Communication</div>
    </div>
  </section>

  <!-- Education -->
  <section id="education">
    <h2>Education</h2>
    <div class="section-divider"></div>
    <div class="cards">
      <div class="card"><h3>MBA – HR & IT</h3><p>Dr. AER MBA College, SVU (2023–2025)<br>CGPA: 7.18</p></div>
      <div class="card"><h3>B.Com – Computer Applications</h3><p>Dr. AER Degree/PG College, SVU (2020–2023)<br>CGPA: 8.6</p></div>
      <div class="card"><h3>Intermediate (Class 12)</h3><p>Sri Chaitanya Junior College (2018–2020)<br>CGPA: 8.25</p></div>
      <div class="card"><h3>10th Standard (SSC)</h3><p>Sri Chaitanya School (2017–2018)<br>CGPA: 9.8</p></div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="section-divider"></div>
    <h3>Technical Skills</h3>
    <div class="cards">
      <div class="card">Salesforce (Developer & Administrator)</div>
      <div class="card">Java</div>
      <div class="card">Python</div>
      <div class="card">SQL</div>
      <div class="card">Cybersecurity Fundamentals</div>
      <div class="card">MS Excel & PowerPoint</div>
      <div class="card">Accounting Software</div>
    </div>
    <h3>Professional Skills</h3>
    <div class="cards">
      <div class="card">Data Analysis</div>
      <div class="card">Business Process Improvement</div>
      <div class="card">CRM Management</div>
      <div class="card">Financial Reporting</div>
      <div class="card">Communication</div>
      <div class="card">Team Collaboration</div>
      <div class="card">Research & Documentation</div>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience">
    <h2>Experience</h2>
    <div class="section-divider"></div>
    <div class="cards">
      <div class="card">
        <h3>Finance & Accounts Intern – Amara Raja Energy & Mobility Ltd</h3>
        <p>Aug 2024 – Apr 2025 | India</p>
        <ul>
          <li>Assisted in financial reporting, budgeting, and account reconciliations.</li>
          <li>Gained hands-on experience in accounting software and financial analysis.</li>
          <li>Supported the finance team in optimizing accounting processes.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Sales & Accounts Intern – Aqua Group: Texmo</h3>
        <p>Dec 2022 – May 2023 | India</p>
        <ul>
          <li>Managed physical sales operations, billing, invoicing, and payment tracking.</li>
          <li>Handled accounts and prepared sales reports.</li>
          <li>Streamlined sales and accounting processes.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Salesforce Developer Intern – Salesforce, SmartInternz</h3>
        <p>Aug 2022 – Oct 2022 | Remote</p>
        <ul>
          <li>Salesforce development and customization.</li>
          <li>Created workflows, reports, and dashboards.</li>
          <li>Enhanced CRM processes and automation.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Cybersecurity Virtual Intern – Palo Alto Networks</h3>
        <p>Sep 2022 – Nov 2022 | Remote</p>
        <ul>
          <li>Learned cybersecurity fundamentals and protocols.</li>
          <li>Assisted in vulnerability assessment and threat analysis.</li>
          <li>Gained exposure to real-world cybersecurity tools.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Salesforce Administrator Intern – Salesforce, SmartInternz</h3>
        <p>Apr 2023 – May 2023 | Remote</p>
        <ul>
          <li>Salesforce administration tasks including user management.</li>
          <li>Configured objects, fields, and reports.</li>
          <li>Optimized CRM workflows.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Certifications -->
  <section id="certifications">
    <h2>Certifications</h2>
    <div class="section-divider"></div>
    <div class="cards">
      <div class="card">Cybersecurity Essentials – Cisco</div>
      <div class="card">Master Class on Java Programming – Pantech E-Learning</div>
      <div class="card">Master Class on Python Programming – Skill AP</div>
      <div class="card">Essential Program in Python – LetsUpgrade</div>
      <div class="card">AWS Security Fundamentals – AWS</div>
    </div>
  </section>

  <!-- Services -->
  <section id="services">
    <h2>Services</h2>
    <div class="section-divider"></div>
    <div class="cards">
      <div class="card"><h3>Salesforce Solutions</h3><p>Customization, administration, and development of Salesforce solutions.</p></div>
      <div class="card"><h3>Software Development</h3><p>Building applications using Java, Python, or SQL.</p></div>
      <div class="card"><h3>Finance & Accounts Support</h3><p>Data management, process improvement, and reporting support.</p></div>
      <div class="card"><h3>Business Process Improvement</h3><p>Analyzing workflows and suggesting better solutions.</p></div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="section-divider"></div>
    <div class="cards">
      <div class="card">
        <h3>Community Service Project – Dairy Awareness</h3>
        <p>Dec 2022 – Jan 2023</p>
        <ul>
          <li>Educating local communities about dairy business practices.</li>
          <li>Conducted awareness campaigns and created materials.</li>
          <li>Engaged in research and communication skills.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Research Project – Job Enrichment in APSPDCL</h3>
        <p>Sep 2024 – Nov 2024</p>
        <ul>
          <li>Analyzed employee motivation and efficiency.</li>
          <li>Collected and interpreted survey data.</li>
          <li>Developed insights to improve satisfaction.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Resume -->
  <section id="resume">
    <h2>Resume</h2>
    <div class="section-divider"></div>
    <p style="max-width:700px;margin:auto;">
      I am a dedicated Salesforce Developer & Administrator with expertise in Java, Python, and SQL. With hands-on experience in CRM solutions, finance, and cybersecurity, I bring both technical and analytical skills to deliver efficient business process improvements. Passionate about learning and innovation, I aim to create impactful solutions that drive growth and efficiency.
    </p>
    <a href="https://drive.google.com/file/d/1RXs2nhh9wJCX_vbnm56g5hHIKDuL-m6F/view?usp=drive_link" target="_blank">
      <button>Download Resume</button>
    </a>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact</h2>
    <div class="section-divider"></div>
    <p>📞 +91 79012 66761</p>
    <p>✉️ <a href="mailto:rekhachowdarykommineni@gmail.com">rekhachowdarykommineni@gmail.com</a></p>
    <p>🔗 <a href="https://www.linkedin.com/in/kommineni-rekha-chowdary" target="_blank">LinkedIn</a></p>
    <p>💻 <a href="https://github.com/Komminenirekha" target="_blank">GitHub</a></p>
    <a href="mailto:rekhachowdarykommineni@gmail.com"><button>Send Email</button></a>
    <a href="https://www.linkedin.com/in/kommineni-rekha-chowdary" target="_blank"><button>Connect on LinkedIn</button></a>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Kommineni Rekha Chowdary. Made with love and lots of coffee ☕ | Made in Bolt</p>
  </footer>

  <!-- Smooth Scroll -->
  <script>
    document.querySelectorAll('a[href^="#"]').forEach(link => {
      link.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href'))
          .scrollIntoView({behavior:'smooth'});
      });
    });
  </script>

</body>
</html>
