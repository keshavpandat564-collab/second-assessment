# second-assessment
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background-color: #f4f4f4;
      color: #222;
      text-align: center;
    }

    /* Header */
    header {
      background-color: #0b4da2;
      color: white;
      padding: 15px 0;
    }

    header h1 {
      font-size: 24px;
      margin-bottom: 8px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-size: 13px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* Sections */
    section {
      padding: 30px 20px;
      border-bottom: 1px solid #ccc;
    }

    section h2 {
      font-size: 18px;
      margin-bottom: 20px;
    }

    /* About Me */
    .profile-img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      background-color: #cfe0fc;
      margin-bottom: 15px;
    }

    .about-text {
      font-size: 13px;
      color: #333;
    }

    /* Skills Table */
    table {
      margin: 0 auto;
      border-collapse: collapse;
      width: 60%;
      max-width: 500px;
      background-color: #f9f9f9;
      font-size: 13px;
    }

    th, td {
      border: 1px solid #0b4da2;
      padding: 10px;
    }

    th {
      background-color: #0b4da2;
      color: white;
    }

    /* Projects */
    .project-card {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 6px;
      width: 60%;
      max-width: 500px;
      margin: 12px auto;
      padding: 18px;
    }

    .project-card h3 {
      font-size: 15px;
      margin-bottom: 8px;
    }

    .project-card p {
      font-size: 13px;
      color: #444;
    }

    /* Contact Form */
    .contact-table input,
    .contact-table textarea {
      width: 95%;
      padding: 6px;
      border: 1px solid #888;
      font-size: 12px;
    }

    .contact-table textarea {
      height: 55px;
      resize: none;
    }

    .btn {
      background-color: #0b4da2;
      color: white;
      border: none;
      padding: 8px 35px;
      border-radius: 3px;
      cursor: pointer;
      font-size: 12px;
    }

    .btn:hover {
      background-color: #083a7a;
    }

    /* Back to Top */
    .top-btn-container {
      text-align: right;
      padding: 10px 20px;
    }

    .top-btn {
      background-color: #0b4da2;
      color: white;
      text-decoration: none;
      padding: 6px 12px;
      border-radius: 3px;
      font-size: 12px;
    }

    /* Bottom Footer Bar */
    footer {
      background-color: #0b4da2;
      height: 10px;
    }
  </style>
</head>
<body id="top">

  <!-- Header -->
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- About Me Section -->
  <section id="about">
    <h2>About Me</h2>
    <!-- Apni image lagane ke liye src mein apni photo ka path daal dena -->
    <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" alt="Profile Picture" class="profile-img">
    <p class="about-text">
      Hello! My name is John Doe. I am learning web development and this is my first portfolio website.
    </p>
  </section>

  <!-- My Skills Section -->
  <section id="skills">
    <h2>My Skills</h2>
    <table>
      <tr>
        <th>Skill</th>
        <th>Level</th>
      </tr>
      <tr>
        <td>HTML</td>
        <td>Beginner</td>
      </tr>
      <tr>
        <td>CSS</td>
        <td>Beginner</td>
      </tr>
      <tr>
        <td>JavaScript</td>
        <td>Learning</td>
      </tr>
    </table>
  </section>

  <!-- My Projects Section -->
  <section id="projects">
    <h2>My Projects</h2>
    <div class="project-card">
      <h3>Project 1</h3>
      <p>A simple HTML & CSS webpage.</p>
    </div>
    <div class="project-card">
      <h3>Project 2</h3>
      <p>Another awesome mini project.</p>
    </div>
  </section>

  <!-- Contact Me Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <table class="contact-table">
        <tr>
          <td><label for="name">Name:</label></td>
          <td><input type="text" id="name" placeholder="Enter your name" required></td>
        </tr>
        <tr>
          <td><label for="email">Email:</label></td>
          <td><input type="email" id="email" placeholder="Enter your email" required></td>
        </tr>
        <tr>
          <td><label for="message">Message:</label></td>
          <td><textarea id="message" placeholder="Write your message" required></textarea></td>
        </tr>
        <tr>
          <td colspan="2">
            <button type="submit" class="btn">Send</button>
          </td>
        </tr>
      </table>
    </form>

    <div class="top-btn-container">
      <a href="#top" class="top-btn">&uarr; Back to Top</a>
    </div>
  </section>

  <footer></footer>

</body>
</html>
