<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        #about img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 10px 0;
        }
        #skills ul {
            list-style: none;
            padding: 0;
        }
        #skills ul li {
            display: inline;
            margin: 0 15px;
            padding: 5px 10px;
            background: #e7e7e7;
            border-radius: 5px;
        }
        .project {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            background: #f9f9f9;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>My Portfolio</h1>
    <nav>
        <a href="#about">About Me</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="container">
    <section id="about">
        <h2>About Me</h2>
        <img src="C:\Users\pc\Downloads\WhatsApp Image 2024-07-15 at 11.40.43_18a74882.jpg" alt="Profile Image">
        <p>Hi, I'm Raghav Khandelwal, a passionate Data Scientist and Developer with a strong focus on machine learning and computer vision. With extensive experience in Python, I specialize in leveraging libraries like TensorFlow, OpenCV, NumPy, and Pandas to develop innovative solutions that make sense of complex data.</p>
        <p>I am dedicated to exploring the intersection of data science and artificial intelligence, constantly seeking to learn new techniques and apply them to real-world challenges. My goal is to create intelligent systems that not only automate processes but also provide insightful predictions and analyses.</p>
        <p>Through my projects, I aim to contribute to the growing field of data science by developing applications that can understand and interpret visual and auditory data, paving the way for smarter technology.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Machine Learning</li>
            <li>Data Science</li>
            <li>NumPy</li>
            <li>Pandas</li>
            <li>TensorFlow</li>
            <li>OpenCV</li>
            <li>Data Visualization</li>
            <li>Model Deployment</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Image and Speech Recognition</h3>
            <p>This project identifies objects in images and categorizes them, providing detailed information about each object.</p>
            <a href="https://github.com/raghavkhandelwal12">View on GitHub</a>
        </div>
        <div class="project">
            <h3>Data Analysis with Pandas</h3>
            <p>Utilized Pandas for data manipulation and analysis to derive insights from datasets, helping businesses make data-driven decisions.</p>
            <a href="https://github.com/raghavkhandelwal12">View on GitHub</a>
        </div>
        <div class="project">
            <h3>Machine Learning Models</h3>
            <p>Developed machine learning models using TensorFlow to solve various classification problems, achieving high accuracy on multiple datasets.</p>
            <a href="https://github.com/raghavkhandelwal12">View on GitHub</a>
        </div>
        <div class="project">
            <h3>Data Visualization Dashboard</h3>
            <p>Created interactive dashboards using Python libraries to visualize data trends and insights effectively for stakeholders.</p>
            <a href="https://github.com/raghavkhandelwal12">View on GitHub</a>
        </div>
        <div class="project">
            <h3>Model Deployment</h3>
            <p>Successfully deployed machine learning models into production environments, ensuring reliable performance and scalability.</p>
            <a href="https://github.com/raghavkhandelwal12">View on GitHub</a>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:raghavkhandelwal761@gmail.com">raghavkhandelwal761@gmail.com</a></p>
        <p>Phone: 7877578237</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/raghav-khandelwal-031452229/">My LinkedIn Profile</a></p>
        <p>GitHub: <a href="https://github.com/raghavkhandelwal12">My GitHub Profile</a></p>
    </section>
</div>

<footer>
    <p>My Portfolio &copy; 2024</p>
</footer>

</body>
</html>

