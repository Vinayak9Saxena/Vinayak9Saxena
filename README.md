<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    /* Reset some default styles */
    body, h1, h2, h3, p {
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Times New Roman', sans-serif;
      line-height: 1.6;
      background-color: #000000;
    }
    img {
        position: absolute;
    }
    header {
      background-color: #333333;
      color: #ffffff;
      text-align: center;
      padding: 100px 0;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
    }
    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
    }
    nav ul li {
      display: inline;
      margin-right: 20px;
    }
    nav ul :hover {
        color: rgb(255, 145, 0);
        text-decoration: underline;
        cursor: pointer;
    }
    nav ul li a {
      color: #a9a8a8;
      text-decoration: none;
    }
    nav ul li a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px;
      margin: 20px;
      background-color: #fff;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    section h2 {
      margin-bottom: 20px;
      font-size: 1.8em;
    }
    .about-me p,
    .project p,
    .contact-info p {
      font-size: 1.1em;
      line-height: 1.8;
    }
    footer {
      text-align: center;
      padding: 20px 0;
      background-color: #333;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi!
        This is VINAYAK SAXENA</h1>
    <nav>
      <ul>
        <li><a href="https://github.com/Vinayak9Saxena">GitHub Profile</a></li>
        <li><a href="https://www.linkedin.com/in/vinayak-saxena-90b2a42a6/">Linked In</a></li>
       <!-- <li><a href="vinayak2002saxena@gmail.com">Gmail</a></li> -->
      </ul>
    </nav>
    <img src="" alt="">
  </header>

  <section id="about" class="about-me">
    <h2>About Me</h2>
    <p>"Passionate and results-driven professional with a diverse background in <b>computer and its application.</b> Equipped with a blend of creative thinking and analytical prowess, I thrive in dynamic environments where innovation and strategic problem-solving are valued.</p>
    <p>I am driven by a commitment to <b>excellence, a thirst for new challenges, and a belief in the power of collaboration.</b> I am eager to contribute my expertise and enthusiasm to a team that values innovation, fosters growth, and embraces diversity.</p>  
</section>

  <section id="projects" class="project">
    <h2>Projects</h2>
    <div>
      <h3><li>Movie Streaming Website</li></h3>
      <p>This Website is made specially for those customers who loves to binge watch their favourite movies, Popular TV shows, Anime for free.</p>
      <p>The technology Used in making this website is: </p>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>Java Script</li>
        <li>Bootstrap</li>
      </ul>
    </div>

    <div>
      <h3><li>Image Ennhancer</li></h3>
      <p>This website is used to make distorted and unclear images into understandable and clear image, The purpose to make this is to make images more clear and understandable.</p>
      <p>The Technology used in making this is:</p>
      <ul>
        <li>Matlab</li>
        <li>machine Learning based Algorithms</li>
      </ul>
    </div>
    <!-- Add more projects as needed -->
  </section>

  <section id="contact" class="contact-info">
    <h2>Contact Me</h2>
    <p>Email: vinayak2002saxena@gmail.com</p>
    <!--<p>Phone: 123-456-7890</p>
    You can add a contact form here if you'd like -->
  </section>

  <footer>
    <p>&copy; 2023 My Portfolio</p>
  </footer>
</body>
</html>
