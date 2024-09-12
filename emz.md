<!DOCTYPE html>
<html lang="en">
<head>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #408cff; 
    }
    .container {
      display: flex;
    }
    .nav {
      width: 185px;
      background: rgba(255, 255, 255, 0.2); 
      backdrop-filter: blur(10px); 
      border-radius: 20px;
      padding: 20px;
      height: 100vh;
      position: fixed;
      z-index: 1000;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
      transition: all 0.3s ease-in-out;
    }
    .nav:hover {
      box-shadow: 0 12px 40px rgba(0, 0, 0, 0.2);
      transform: translateY(-5px);
    }
    .nav h2 {
      color: #ffffff;
      font-size: 22px;
      text-align: center;
      margin-bottom: 30px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 2px;
    } 
    .nav a {
      text-decoration: none;
      color: #dbe4ff;
      display: flex;
      align-items: center;
      font-size: 18px;
      padding: 12px 10px;
      border-radius: 12px;
      margin: 10px 0;
      transition: background-color 0.3s ease, transform 0.3s ease;
    }  
    .nav a:hover {
      background-color: rgba(255, 255, 255, 0.3);
      transform: scale(1.05);
    }
    .nav a i {
      margin-right: 10px;
      font-size: 18px;
    }    
    .content {
      flex-grow: 1;
      padding: 40px;
      margin-left: 200px;
      background-color: #cfdeff;
      position: relative;
      min-height: 100vh;
      transition: background-color 0.3s ease;
      padding-top: 20px;
    }  
    h1 {
      color: #222;
      font-size: 28px;
    } 
    p {
      line-height: 1.8;
      font-size: 16px;
      color: #666;
      margin-left: 20px; /* Adjust as needed */
    }
    ul li {
      margin-bottom: 8px;
      font-size: 16px;
      color: #444;
    }
     .profile-image {
      width: 150px; 
      height: auto;
      border-radius: 50%; 
      display: block;
      margin: 0 auto 10px; 
    }
    @media (max-width: 768px) {
      .nav {
        width: 100%;
        height: auto;
        position: relative;
      }
      .content {
        margin-left: 0;
        padding: 20px;
      }
    }
  </style>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personal Profile</title>
</head>
<body>
<div class="container">
  <div class="nav">
    <h2>EMMAN PROFILE</h2>
    <a href="#about">About Me</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>
  <div class="content">
    <section id="about">
      <h1>About Me</h1>
      <img src="https://i.pinimg.com/564x/0d/69/1c/0d691cff3e30a57df2a3855d5bfe2d67.jpg" alt="Bruno Mars" class="profile-image">
      <p>Hello! I am Emmanuel C. Cabañas, a web developer passionate about creating clean and user-friendly websites. I love coding and learning new technologies to improve my skills.</p>
    </section>
    <section id="skills">
      <h1>Skills</h1>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>React</li>
        <h5>Soft Skills</h5>
        <li>Communication (verbal and written)</li>
        <li>Teamwork and conflict resolution</li>
        <li>Problem solving</li>
        <li>Empathy</li>
        <li>Patience</li>
        <li>Curiosity</li>
        <li>Adaptability</li>
        <li>Accountability</li>
        <li>Time management</li>
        <h5>Hard Skills</h5>
        <li>Data structures and algorithms</li>
        <li>Database and SQL</li>
        <li>Object-oriented programming (OOP) languages</li>
        <li>Integrated development environments (IDEs)</li>
        <li>Cloud computing</li>
        <li>Web development</li>
        <li>Containers</li>
        <li>Text editors</li>
        <li>Git version control</li>
      </ul>
    </section>
    <section id="projects">
      <h1>Projects</h1>
      <p>Check out some of my recent projects below: </p>
      <ul>
        <li><strong>Project 1:</strong> Personal Portfolio</li>
        <li><strong>Project 2:</strong> E-commerce Website</li>
        <li><strong>Project 3:</strong> Student Result Management System</li>
        <li><strong>Project 4:</strong> Online Code Editor (React)</li>
        <li><strong>Project 5:</strong> Amazon clone using React</li>
        <li><strong>Project 6:</strong> Customer Relationship Manager</li>
        <li><strong>Project 7:</strong> Sorting Visualizer</li>
        <li><strong>Project 8:</strong> Multiplayer Game – Connect4</li>
        <li><strong>Project 9:</strong> YouTube Transcript Summarizer</li>
        <li><strong>Project 10:</strong> OurApp – a social media web app in NodeJS</li>
        <li><strong>Project 11:</strong> Codechef Notifier</li>
        <li><strong>Project 12:</strong> Visualizing and forecasting stocks using Dash</li>
        <li><strong>Project 13:</strong> Online Code Editor (JQuery)</li>
        <li><strong>Project 14:</strong> FuzzyURLs</li>
        <li><strong>Project 15:</strong> Slack clone using React</li>
        <li><strong>Project 16:</strong> Authentication in Node.js for a web app</li>
        <li><strong>Project 17:</strong> TinyMCE Synonyms Plugin</li>
        <li><strong>Project 18:</strong> Rat in a Maze</li>
        <li><strong>Project 19:</strong> Resume Builder Web Application</li>
        <li><strong>Project 20:</strong> Markdown Editor</li>
        <li><strong>Project 21:</strong> 450 DSA Tracker</li>
        <li><strong>Project 22:</strong> To-do Web App</li>
        <li><strong>Project 23:</strong> Two truths and a lie game slack bot</li>
        <li><strong>Project 24:</strong> Real-Time Video Processing using Chromakey (Greenscreen) Effect</li>
        <li><strong>Project 25:</strong> WhatsApp Web Clone</li>
        <li><strong>Project 26:</strong> Email Alerts on WhatsApp</li>
        <li><strong>Project 27:</strong> Weather Forecasting App</li>
      </ul>
</section>
<section id="contact">
    <br>
<h1>Contact</h1>
<p>&nbsp;&nbsp;&nbsp;&nbsp;You can reach me at: <a href="emmancabanas9@gmail.com">emmancabanas9@gmail.com</a></p>
</section>
</div>
</div>
</body>
</html>
