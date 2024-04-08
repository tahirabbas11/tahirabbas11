<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>README</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f8f9fa;
    margin: 0;
    padding: 20px;
  }
  h2 {
    text-align: left;
  }
  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .stats-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 20px;
  }
  .social-links {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 20px;
  }
  .social-link {
    display: inline-block;
  }
  .technologies {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 20px;
  }
  .technology-icon {
    width: 30px;
    height: 30px;
    margin-right: 12px;
  }
  @media (min-width: 768px) {
    .container {
      flex-direction: row;
    }
    .stats-container {
      flex-direction: column;
    }
    .technologies {
      justify-content: flex-start;
    }
  }
</style>
</head>
<body>

<div class="container">
  <div>
    <h2>Hi 👋! My name is Tahir Abbas and I'm a Backend Developer.</h2>
    
    <div class="stats-container">
      <img src="https://github-readme-stats.vercel.app/api?username=tahirabbas11&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="150" alt="stats graph" />
      <img src="https://github-readme-stats.vercel.app/api/top-langs?username=tahirabbas11&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph" />
    </div>
    
    <div class="social-links">
      <a class="social-link" href="mailto:tahir.12868@iqra.edu.pk">
        <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo" />
      </a>
      <a class="social-link" href="https://www.linkedin.com/in/thetahirabbas/">
        <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo" />
      </a>
      <!-- Add other social links similarly -->
    </div>
  </div>

  <div class="technologies">
    <img class="technology-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="javascript logo" />
    <img class="technology-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="typescript logo" />
    <img class="technology-icon" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="html5 logo" />
    <!-- Add other technology icons similarly -->
  </div>
</div>

</body>
</html>
