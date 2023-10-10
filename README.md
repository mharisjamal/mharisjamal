<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Profile</title>
  <style>
    /* Global styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f0f0;
      overflow-x: hidden;
    }

    /* Header styles */
    header {
      text-align: center;
      background-color: #0366d6;
      color: #fff;
      padding: 2rem 0;
    }

    header h1 {
      font-size: 2rem;
    }

    /* Profile picture styles */
    .profile-picture {
      display: block;
      margin: 2rem auto;
      border-radius: 50%;
      animation: rotate 10s linear infinite;
    }

    /* Animated GitHub stats styles */
    .stats {
      display: flex;
      justify-content: center;
      margin-top: 1rem;
    }

    /* Skill icons styles */
    .skills {
      display: flex;
      justify-content: center;
      margin-top: 1rem;
    }

    .skills img {
      width: 50px;
      height: 50px;
      margin: 0 10px;
      animation: bounce 2s infinite;
    }

    /* Project thumbnails styles */
    .projects {
      display: flex;
      justify-content: center;
      margin-top: 1rem;
    }

    .projects img {
      width: 200px;
      margin: 0 10px;
      transition: transform 0.3s ease-in-out;
    }

    .projects img:hover {
      transform: scale(1.1);
    }

    /* Footer styles */
    footer {
      text-align: center;
      padding: 2rem 0;
      background-color: #0366d6;
      color: #fff;
    }

    /* Keyframes for profile picture animation */
    @keyframes rotate {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    /* Keyframes for skill icons animation */
    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
      }
      40% {
        transform: translateY(-10px);
      }
      60% {
        transform: translateY(-5px);
      }
    }
  </style>
</head>
<body>
  <!-- Header section -->
  <header>
    <h1>Hi 👋, I'm M.Haris Jamal</h1>
  </header>

  <!-- Animated background -->
  <img src="animated-background.gif" alt="Animated Background" style="width: 100%; height: auto;">

  <!-- Animated profile picture -->
  <img src="animated-profile-picture.gif" alt="Profile Picture" class="profile-picture" width="150">

  <!-- Animated GitHub stats -->
  <div class="stats">
    <img src="github-stats.gif" alt="GitHub Stats">
  </div>

  <!-- Skill icons -->
  <div class="skills">
    <img src="python-logo.gif" alt="Python">
    <img src="javascript-logo.gif" alt="JavaScript">
    <img src="react-logo.gif" alt="React">
  </div>

  <!-- Project thumbnails -->
  <div class="projects">
    <a href="link-to-project">
      <img src="project-thumbnail.gif" alt="Project 1">
    </a>
    <a href="link-to-project">
      <img src="project-thumbnail.gif" alt="Project 2">
    </a>
  </div>

  <!-- Footer with social media links -->
  <footer>
    <a href="mailto:harisjamal01@icloud.com">
      <img src="email-icon.gif" alt="Email" style="width: 30px; height: 30px; margin-right: 10px;">
    </a>
    <a href="https://www.linkedin.com/in/heheboi">
      <img src="linkedin-icon.gif" alt="LinkedIn" style="width: 30px; height: 30px; margin-right: 10px;">
    </a>
    <a href="https://www.instagram.com/hehebrooo">
      <img src="instagram-icon.gif" alt="Instagram" style="width: 30px; height: 30px;">
    </a>
  </footer>
</body>
</html>
