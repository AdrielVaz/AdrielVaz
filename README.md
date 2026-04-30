<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Adriel Vaz Lima | Fullstack Developer</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <style>
    body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #0f172a;
  color: #e2e8f0;
}

.container {
  width: 80%;
  margin: auto;
  padding: 20px;
}

header {
  text-align: center;
  border-bottom: 1px solid #334155;
  padding-bottom: 20px;
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
  color: #38bdf8;
}

.contact {
  margin-top: 10px;
}

.contact span, .contact a {
  display: block;
  margin: 5px 0;
  color: #94a3b8;
  text-decoration: none;
}

section {
  margin-top: 30px;
}

h2 {
  color: #38bdf8;
  border-bottom: 1px solid #334155;
  padding-bottom: 5px;
}

.skills {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 15px;
}

.project {
  background: #1e293b;
  padding: 15px;
  margin-top: 15px;
  border-radius: 10px;
}

.project a {
  color: #38bdf8;
  text-decoration: none;
}

footer {
  text-align: center;
  margin-top: 40px;
  color: #64748b;
}
  </style>
  <div class="container">

    <header>
      <h1>Adriel Vaz Lima</h1>
      <p>Fullstack Developer | Software Engineering Student</p>
      <div class="contact">
        <span>📍 Salvador, Brazil</span>
        <span>📧 adriel20005@gmail.com</span>
        <span>📱 +55 71 99260-4539</span>
        <a href="https://www.linkedin.com/in/adriel-vaz-lima-898981287/" target="_blank">LinkedIn</a>
      </div>
    </header>

    <section>
      <h2>🎯 Objective</h2>
      <p>Gain professional experience and grow as a developer.</p>
    </section>

    <section>
      <h2>🎓 Education</h2>
      <ul>
        <li>Software Engineering (In Progress) – Estácio</li>
        <li>Technical Degree in Systems Development – SENAI CIMATEC</li>
        <li>Ford Enter Program – SENAI CIMATEC</li>
        <li>High School – SESI</li>
      </ul>
    </section>

    <section>
      <h2>🛠 Skills</h2>

      <div class="skills">
        <div>
          <h3>Backend</h3>
          <p>Python, Java, C#, PHP, Node.js, TypeScript</p>
        </div>

        <div>
          <h3>Frontend</h3>
          <p>HTML, CSS, JavaScript</p>
        </div>

        <div>
          <h3>Frameworks</h3>
          <p>Spring Boot, Angular</p>
        </div>

        <div>
          <h3>DevOps</h3>
          <p>Docker, Google Cloud, Vercel</p>
        </div>

        <div>
          <h3>Databases</h3>
          <p>PostgreSQL, MySQL</p>
        </div>
      </div>
    </section>

    <section>
      <h2>📌 Projects</h2>

      <div class="project">
        <h3>MySQL Database Generator</h3>
        <p>Backend project using Spring Boot to simulate database creation.</p>
        <a href="https://github.com/AdrielVaz/Projeto-Msql-cria--o-e-consulta-dinamica--Plano-.git">View Project</a>
      </div>

      <div class="project">
        <h3>Course Platform Backend</h3>
        <p>Node.js backend with Google OAuth2, email verification and PDF generation.</p>
        <a href="https://github.com/AdrielVaz/Back-end-SiteCurso">View Project</a>
      </div>

      <div class="project">
        <h3>Ford Dashboard</h3>
        <p>Angular dashboard developed in Ford Enter program.</p>
        <a href="https://ford-dashboard-master-ryhx.vercel.app/inicio">Live Demo</a>
      </div>

    </section>

    <footer>
      <p>© 2026 Adriel Vaz Lima</p>
    </footer>

  </div>

</body>
</html>
