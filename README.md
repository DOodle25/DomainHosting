<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dipen's Projects & Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f9fc;
      color: #333;
    }

    header {
      text-align: center;
      padding: 50px 20px;
      background-color: #ffffff;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      margin-bottom: 40px;
    }

    h1 {
      font-size: 3rem;
      color: #2c3e50;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.2rem;
      color: #7f8c8d;
      margin-bottom: 20px;
    }

    hr {
      border: 1px solid #ecf0f1;
      margin: 20px 0;
      width: 60%;
      margin-left: auto;
      margin-right: auto;
    }

    .social-links {
      margin: 20px 0;
    }

    .social-links a {
      font-size: 1.5rem;
      color: #ffffff;
      text-decoration: none;
      margin: 0 15px;
      padding: 12px 20px;
      background-color: #3498db;
      border-radius: 30px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      display: inline-flex;
      align-items: center;
    }
    .social-links a:first-child {
      background-color: #000000;
    }

    .social-links a i {
      margin-right: 8px;
    }

    .social-links a:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
    }

    .projects, .domain-projects {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 30px;
    }

    .project-box, .domain-box {
      background-color: #ffffff;
      color: #333;
      padding: 20px;
      margin: 15px;
      border-radius: 10px;
      width: 250px;
      text-align: center;
      font-size: 1.2rem;
      text-decoration: none;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .project-box:hover, .domain-box:hover {
      transform: translateY(-10px);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
    }

    .project-box img, .domain-box img {
      width: 100%;
      height: auto;
      border-radius: 10px;
      margin-bottom: 15px;
    }

    .tech-badges img {
      margin: 15px;
      height: 25px;
      transition: transform 0.3s ease;
    }

    .tech-badges img:hover {
      transform: scale(1.1);
    }

    @media (max-width: 768px) {
      .project-box, .domain-box {
        width: 200px;
      }
    }

    @media (max-width: 480px) {
      .project-box, .domain-box {
        width: 100%;
      }

      .social-links a {
        font-size: 1.2rem;
        padding: 10px 15px;
      }

      .tech-badges img {
        width: 120px;
      }
    }

  </style>
</head>
<body>

<header>
  <h1>💼 Dipen's Projects & Portfolio</h1>
  <p>A collection of my work, projects, and experiments in web development</p>
  <hr>
  
  <div class="social-links">
    <a href="https://github.com/DOodle25" target="_blank">
      <i class="fab fa-github"></i> GitHub
    </a>
    <a href="https://www.linkedin.com/in/dipen-patel-792296260/" target="_blank">
      <i class="fab fa-linkedin"></i> LinkedIn
    </a>
    <a href="Dipen.html" target="_blank">
      <i class="fas fa-file-alt"></i> Resume
    </a>
  </div>
  
  <hr>

  <h2>🌟 Featured Projects</h2>
  <div class="projects">
    <a href="https://azure-portfolio.alynor.wiki/" class="project-box" target="_blank">
      <!-- <img src="path/to/image2.jpg" alt="Portfolio"> -->
      Portfolio
    </a>
    <a href="https://ambitious-bush-0645df200.5.azurestaticapps.net/" class="project-box" target="_blank">
      <!-- <img src="path/to/image3.jpg" alt="District Integrated Dashboard"> -->
      District Integrated Dashboard-Frontend
    </a>
    <a href="https://district-integrated-dashboard-backend-cudqcnbehzgye3c9.centralindia-01.azurewebsites.net/admin/login/?next=/admin/" class="project-box" target="_blank">
      <!-- <img src="path/to/image3.jpg" alt="District Integrated Dashboard"> -->
      District Integrated Dashboard-Backend Admin
    </a>
    <a href="https://github.com/DOodle25/SyncUP" class="project-box" target="_blank">
      <!-- <img src="path/to/image4.jpg" alt="SyncUP"> -->
      SyncUP
    </a>
    <a href="Project-CodeCanvas-Login-Signup/Code-Canvas-Landing-Page.html" class="project-box" target="_blank">
      <!-- <img src="path/to/image5.jpg" alt="Code-Canvas"> -->
      Code-Canvas (Prototype)
    </a>
    <a href="https://github.com/DOodle25/DOodle25" class="project-box" target="_blank">
      <!-- <img src="path/to/image12.jpg" alt="Profile Readme"> -->
      Profile Readme
    </a>
    <a href="https://github.com/DOodle25/DID-React-Native" class="project-box" target="_blank">
      <!-- <img src="path/to/image13.jpg" alt="DID React Native"> -->
      DID React Native
    </a>
    <a href="https://github.com/DOodle25/React-Native" class="project-box" target="_blank">
      <!-- <img src="path/to/image14.jpg" alt="React Native"> -->
      React Native
    </a>
    <a href="https://github.com/DOodle25/GradialD" class="project-box" target="_blank">
      <!-- <img src="path/to/image15.jpg" alt="GradialD"> -->
      GradialD
    </a>
    <a href="https://github.com/DOodle25/AIChatBot" class="project-box" target="_blank">
      <!-- <img src="path/to/image16.jpg" alt="AIChatBot"> -->
      AIChatBot
    </a>
    <a href="https://github.com/DOodle25/Python-public-" class="project-box" target="_blank">
      <!-- <img src="path/to/image17.jpg" alt="Python Public"> -->
      Python Public
    </a>
    <a href="https://github.com/DOodle25/DSA" class="project-box" target="_blank">
      <!-- <img src="path/to/image18.jpg" alt="DSA"> -->
      DSA
    </a>
    <a href="https://github.com/DOodle25/MATH" class="project-box" target="_blank">
      <!-- <img src="path/to/image19.jpg" alt="MATH"> -->
      MATH
    </a>
    <a href="https://github.com/DOodle25/DBMS-public-" class="project-box" target="_blank">
      <!-- <img src="path/to/image20.jpg" alt="DBMS Public"> -->
      DBMS Public
    </a>
    <a href="https://github.com/DOodle25/Product-listing" class="project-box" target="_blank">
      <!-- <img src="path/to/image21.jpg" alt="Product Listing"> -->
      Product Listing
    </a>
    <a href="https://github.com/DOodle25/SystemDesign" class="project-box" target="_blank">
      <!-- <img src="path/to/image22.jpg" alt="System Design"> -->
      System Design
    </a>
    <a href="https://github.com/DOodle25/Web-Development-Notes-Public" class="project-box" target="_blank">
      <!-- <img src="path/to/image23.jpg" alt="Web Development Notes"> -->
      Web Development Notes
    </a>
    <a href="https://github.com/DOodle25/Code-Canvas-Server" class="project-box" target="_blank">
      <!-- <img src="path/to/image24.jpg" alt="Code Canvas Server"> -->
      Code Canvas Server
    </a>
  </div>

  <hr>

  <h2>🖥️ Project Sharing Ports</h2>
  <div class="domain-projects">
    <a href="https://www.alynor.wiki" class="domain-box" target="_blank">
      <!-- <img src="path/to/image6.jpg" alt="My Domain"> -->
      My Domain
    </a>
    <a href="https://1.alynor.wiki" class="domain-box" target="_blank">
      <!-- <img src="path/to/image7.jpg" alt="Hosting Port 1"> -->
      Hosting Port 1: nginx + ngrok
    </a>
    <a href="https://2.alynor.wiki" class="domain-box" target="_blank">
      <!-- <img src="path/to/image8.jpg" alt="Hosting Port 2"> -->
      Hosting Port 2: nginx + ngrok
    </a>
    <a href="https://3.alynor.wiki" class="domain-box" target="_blank">
      <!-- <img src="path/to/image9.jpg" alt="Hosting Port 3"> -->
      Hosting Port 3: Render
    </a>
    <a href="https://4.alynor.wiki" class="domain-box" target="_blank">
      <!-- <img src="path/to/image10.jpg" alt="Hosting Port 4"> -->
      Hosting Port 4: Azure
    </a>
    <a href="https://5.alynor.wiki" class="domain-box" target="_blank">
      <!-- <img src="path/to/image11.jpg" alt="Hosting Port 5"> -->
      Hosting Port 5: Azure
    </a>
  </div>

  <hr>
  
  <h3>🎨 Styling and design improvements coming soon!</h3>
  <p>Stay tuned for more updates and exciting projects 🚀</p>
  
  <div class="tech-badges">
    <img src="https://img.shields.io/badge/MERN-stack-green" alt="MERN" />
    <img src="https://img.shields.io/badge/React-blue" alt="React" />
    <img src="https://img.shields.io/badge/Node.js-brightgreen" alt="Node.js" />
    <img src="https://img.shields.io/badge/Django-darkgreen" alt="Django" />
  </div>
</header>
<section></section>
  <h2 style="text-align: center;">🎥 Video Gallery</h2>
  <div class="video-gallery">
    <iframe src="https://github.com/DOodle25/DomainHosting/blob/main/Videos/DBI.mp4" frameborder="0" allowfullscreen></iframe>
    <iframe src="../Videos/bytexlproductlisting.mp4" frameborder="0" allowfullscreen></iframe>
    <iframe src="../Videos/internship.mp4" frameborder="0" allowfullscreen></iframe>
    <iframe src="../Videos/portfolio.mp4" frameborder="0" allowfullscreen></iframe>
    <iframe src="../Videos/SyncUP2.mp4" frameborder="0" allowfullscreen></iframe>
  </div>

  <style>
    .video-gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }

    .video-gallery iframe {
      width: 100%;
      max-width: 560px;
      height: 315px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .video-gallery iframe:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
    }

    @media (max-width: 768px) {
      .video-gallery iframe {
        max-width: 100%;
        height: auto;
      }
    }
  </style>
</section>

</body>
</html>
