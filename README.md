<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Raghav Khandelwal's Profile</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f9;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 900px;
      margin: auto;
      overflow: hidden;
      padding: 0 20px;
    }
    .header {
      background: #333;
      color: #fff;
      padding: 10px 0;
      text-align: center;
    }
    .header img {
      width: 150px;
      border-radius: 50%;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      animation: float 4s ease-in-out infinite;
    }
    .about, .skills, .projects, .contact {
      background: #fff;
      margin: 20px 0;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .section-title {
      margin-bottom: 10px;
      color: #333;
      font-size: 24px;
      text-align: center;
    }
    .skills .skill {
      display: inline-block;
      margin: 10px;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 8px;
      background: #f4f4f9;
    }
    .projects a {
      color: #333;
      text-decoration: none;
      display: block;
      margin: 10px 0;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 8px;
      background: #f4f4f9;
    }
    .projects a:hover {
      background: #e2e2e9;
    }
    .contact a {
      margin: 0 10px;
      color: #333;
      text-decoration: none;
    }
    .contact a:hover {
      color: #007BFF;
    }
    @keyframes float {
      0% {
        transform: translateY(0px);
      }
      50% {
        transform: translateY(-10px);
      }
      100% {
        transform: translateY(0px);
      }
    }
    @media (max-width: 768px) {
      .skills .skill {
        display: block;
        width: 100%;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

  <div class="header">
    <img src="https://github.com/raghavkhandelwal12/your-repository/blob/main/test_image_house.jpg" alt="Raghav Khandelwal">
    <h1>Raghav Khandelwal</h1>
  </div>

  <div class="container">

    <div class="about">
      <h2 class="section-title">About Me</h2>
      <p>Hello! I'm Raghav Khandelwal, a Data Scientist specializing in machine learning and computer vision. I love creating innovative solutions and learning new technologies.</p>
    </div>

    <div class="skills">
      <h2 class="section-title">Skills</h2>
      <div class="skill">Python</div>
      <div class="skill">C</div>
      <div class="skill">Machine Learning</div>
      <div class="skill">TensorFlow</div>
      <div class="skill">Keras</div>
      <div class="skill">OpenCV</div>
      <div class="skill">NumPy</div>
      <div class="skill">Pandas</div>
      <div class="skill">Matplotlib</div>
      <div class="skill">Git</div>
      <div class="skill">VSCode</div>
    </div>

    <div class="projects">
      <h2 class="section-title">Projects</h2>
      <a href="https://github.com/raghavkhandelwal12/project1">Project Name 1: A brief description of what this project does.</a>
      <a href="https://github.com/raghavkhandelwal12/project2">Project Name 2: A brief description of what this project does.</a>
    </div>

    <div class="contact">
      <h2 class="section-title">Contact Me</h2>
      <a href="https://www.linkedin.com/in/raghav-khandelwal-031452229/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
      <a href="mailto:raghavkhandelwal761@gmail.com"><i class="fas fa-envelope"></i> Email</a>
      <p><i class="fas fa-phone"></i> Contact Number: 7877578237</p>
    </div>

  </div>

</body>
</html>

