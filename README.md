
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Omkar Chavan - Resume</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet" />

  <style>
    :root {
      --bg-color: #f9f9f9;
      --text-color: #333;
      --primary-color: #2980b9;
      --secondary-color: #ecf0f1;
      --heading-color: #2c3e50;
    }

    body.dark-mode {
      --bg-color: #1e1e1e;
      --text-color: #ddd;
      --primary-color: #3498db;
      --secondary-color: #2c3e50;
      --heading-color: #fff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    .navbar {
      background-color: var(--primary-color);
      color: white;
      padding: 15px 30px;
      position: sticky;
      top: 0;
      z-index: 999;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .navbar h1 {
      font-size: 1.2rem;
    }

    .toggle-btn {
      background: none;
      color: white;
      border: 2px solid white;
      padding: 5px 10px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 0.9rem;
    }

    .container {
      max-width: 900px;
      margin: auto;
      background: var(--bg-color);
      padding: 30px;
    }

    header {
      text-align: center;
      margin-bottom: 30px;
    }

    .profile-header {
      display: flex;
      align-items: center;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .profile-header h1 {
      font-size: 2.5rem;
      color: var(--heading-color);
    }

    section {
      margin-bottom: 30px;
    }

    section h2 {
      color: var(--primary-color);
      margin-bottom: 10px;
      border-bottom: 2px solid #ccc;
      padding-bottom: 5px;
    }

    .skills ul,
    .languages ul,
    .hobbies ul {
      list-style: none;
      padding-left: 0;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skills li,
    .languages li,
    .hobbies li {
      background: var(--secondary-color);
      padding: 8px 12px;
      border-radius: 4px;
    }

    .project {
      margin-bottom: 15px;
    }

    .project h3 {
      margin-bottom: 5px;
      color: var(--heading-color);
    }

    .project a {
      color: var(--primary-color);
      text-decoration: none;
    }

    .contact a {
      color: var(--primary-color);
      text-decoration: none;
    }

    .semesters {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .semester {
      background-color: var(--secondary-color);
      padding: 15px;
      border-radius: 8px;
      text-align: center;
    }

    @media (max-width: 600px) {
      .skills ul,
      .languages ul,
      .hobbies ul {
        flex-direction: column;
      }

      .profile-header {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <div class="navbar">
    <h1>Omkar Chavan</h1>
    <button class="toggle-btn" onclick="toggleDarkMode()">Toggle Dark Mode</button>
  </div>

  <div class="container">

    <!-- Header -->
    <header>
      <div class="profile-header">
        <div>
          <h1>Omkar Chavan</h1>
        </div>
      </div>
    </header>

    <!-- About Me -->
    <section class="about">
      <h2>About Me</h2>
      <p>
        I am a motivated and enthusiastic Bachelor of Computer Science (BCS) student with a strong passion for software development, problem-solving, and innovative technology.
        I enjoy learning new programming languages and frameworks, building web applications, and contributing to open-source projects. Currently, I am focused on deepening my knowledge in algorithms, data structures, and full-stack web development.
        I am eager to apply my skills in real-world projects and internships to grow as a software engineer and make meaningful contributions to the tech community.
      </p>
    </section>

    <!-- Personal Info -->
    <section class="personal-info">
      <h2>Personal Information</h2>
      <p><strong>Age:</strong> 22</p>
      <p><strong>Date of Birth:</strong> Jun 27, 2003</p>
      <p><strong>Nationality:</strong> Indian</p>
      <p><strong>Address:</strong> AT post old loha Dist:Nanded, Maharashtra, India</p>
    </section>

    <!-- Education -->
    <section class="education">
      <h2>Education</h2>
      <p><strong>Bachelor of Computer Science (BCS)</strong><br />
        <b>University Name:</b> Swami Ramanand Teerth Marathwada University<br />
        2023 – 2026
      </p>
      <p><strong>Overall CGPA:</strong> 8.6 / 10</p>
      <p><strong>Relevant Coursework:</strong> Data Structures, Web Development, Operating Systems</p>

      <div class="semesters">
        <div class="semester">
          <h3>Semester 1</h3>
          <p><strong>CGPA:</strong> 8.15</p>
        </div>
        <div class="semester">
          <h3>Semester 2</h3>
          <p><strong>CGPA:</strong> 7.83</p>
        </div>
        <div class="semester">
          <h3>Semester 3</h3>
          <p><strong>CGPA:</strong> 8.33</p>
        </div>
        <div class="semester">
          <h3>Semester 4</h3>
          <p><strong>CGPA:</strong> 7.08</p>
        </div>
      </div>
    </section>

    <!-- Skills -->
    <section class="skills">
      <h2>Skills</h2>
      <ul>
        <li>C++</li>
        <li>Python</li>
        <li>HTML</li>
        <li>CSS</li>
        <li>Java</li>
      </ul>
    </section>

    <!-- Languages -->
    <section class="languages">
      <h2>Languages Known</h2>
      <ul>
        <li>English – Fluent</li>
        <li>Hindi – Fluent</li>
        <li>Marathi – Native</li>
      </ul>
    </section>

    <!-- Hobbies -->
    <section class="hobbies">
      <h2>Hobbies & Interests</h2>
      <ul>
        <li>Coding Challenges</li>
        <li>Create web pages</li>
        <li>Reading Tech Blogs</li>
        <li>Gaming</li>
      </ul>
    </section>

    <!-- Projects -->
    <section class="projects">
      <h2>Projects</h2>

      <div class="project">
        <h3>Portfolio Website</h3>
        <p>A personal portfolio to showcase my projects and skills.</p>
        <p><strong>Tech used:</strong> HTML, CSS, JS, bootstrap</p>
        <p><a href="https://omkarpatilchavan0712.github.io/responsiveportfolio1/">Click Here</a></p>
      </div>

      <div class="project">
        <h3>Event Managnent</h3>
        <p>A  simple project created in class.</p>
        <p><strong>Tech used:</strong> JavaScript, HTML, CSS</p>
        <p><a href=" https://omkarpatilchavan0712.github.io/eventmanagment1/">Click Here</a></p>
      </div>
    </section>

    <!-- Contact -->
    <section class="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:chavanomiipatil@gmail.com">chavanomiipatil@gmail.com</a></p>
      <p>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/yourusername" target="_blank">linkedin.com/in/yourusername</a></p>
    </section>

  </div>

  <!-- Dark Mode Toggle Script -->
  <script>
    function toggleDarkMode() {
      document.body.classList.toggle("dark-mode");
    }
  </script>

</body>
</html>
