<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Resume - Md Nazmus Sajid</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      text-decoration: none;
    }

    body {
      font-family: Calibri, sans-serif;
      line-height: 1.6;
    }

    /* Navigation bar */
    .navbar {
      background-color: crimson;
      padding: 8px 15px;
    }

    .navdiv {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .navdiv h2 {
      color: white;
    }

    .navdiv ul {
      list-style: none;
    }

    .navdiv ul li {
      display: inline-block;
      margin-left: 20px;
    }

    .navdiv ul li a {
      color: white;
      font-size: 22px;
      font-weight: bold;
    }

    /* Main content */
    .container {
      padding: 40px 60px;
    }

    section {
      margin-bottom: 40px;
    }

    h1, h2 {
      color: #333;
    }

    /* Skills header + resume button */
    .skills-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top: -40px; 
      margin-bottom: 15px;
    }

    .download-btn {
      background-color: white;
      color: crimson;
      font-weight: bold;
      padding: 10px 15px;
      border: 2px solid crimson;
      border-radius: 5px;
      transition: all 0.3s ease;
    }

    .download-btn:hover {
      background-color: crimson;
      color: white;
    }

    ul.skills-list, ul.experience-list {
      padding-left: 20px;
    }

    ul.skills-list li,
    ul.experience-list li {
      margin-bottom: 10px;
    }
    .education-section {
    margin-top: -50px; /* Adjust this value as needed */
    }
    .experience-section {
    margin-top: -50px; /* Adjust this value as needed */
    }
    
    .tech-skills {
    font-size: 18px; /* or any size you prefer */
    }
    
    li {
    font-size: 18px; /* You can change to 20px, 22px, etc. */
    }


  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar">
    <div class="navdiv">
      <ul>
        <li><a href="Projects.html">Projects</a></li>
        <li><a href="Cerifications.html">Certifications</a></li>
        <li><a href="Contact.html">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Main Content -->
  <div class="container">
    
    <section>
      <h1>Microsoft Certified Power BI Business Analyst with 2 Years of Experience</h1>
      <p class="tech-skills"><strong>Technical Skills:</strong> Python, R, SQL, Power BI, MySQL, Azure, AWS</p>
    </section>

    <section>
      <div class="skills-header">
        <h2>Skills Highlights Include</h2>
        <a href="assets/Md_Nazmus_ Sajid_Resume.pdf" download class="download-btn">Download Resume</a>
      </div>
      <ul class="skills-list">
        <li>Skilled in applying data-driven problem-solving methodologies, achieving a 25% increase in database management efficiency.</li>
        <li>Demonstrated a proactive approach by transitioning from Azure to GCP and mastering SAS.</li>
        <li>Created interactive reports on product performance and customer interactions that transformed decision-making processes.</li>
        <li>Exceptional interpersonal communication skills, contributing to a 10% increase in overall sales revenue.</li>
      </ul>
    </section>

    <section class="education-section">
      <h2>Education</h2>
      <p class="tech-skills"><strong>Master of Data Science and Analytics</strong> | University of Calgary (Sep 2021 - Sep 2023)</p>
      <p class="tech-skills"><strong>Bachelor of Computer Science</strong> | IIUM Malaysia (Sep 2015 - Mar 2020)</p>
    </section>

    <section class="experience-section">
      <h2>Experience</h2>
      <h3>Data Analyst | Flexiroam (June 2019 - August 2020)</h3>
      <ul class="experience-list">
        <li>Engineered 50+ database schemas with MySQL Workbench, improving efficiency by 25%.</li>
        <li>Built reporting infrastructure in Power BI & SQL to deliver real-time product and marketing insights.</li>
        <li>Ingested CRM/BI data into Azure Data Lake for monthly reports on clients and resources.</li>
        <li>Partnered with marketing/product teams to centralize reporting, reducing report time by 40%.</li>
        <li>Performed root cause analyses that improved conversion rates by 32%.</li>
        <li>Used analytics to optimize sales strategy, increasing revenue by 10% in 3 months.</li>
      </ul>
    </section>

  </div>

</body>
</html>






