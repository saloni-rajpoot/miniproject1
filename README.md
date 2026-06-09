# miniproject1
first webpage using html and css
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- CSS LInk -->
    <link rel="stylesheet" href="project1.css" />
    <!--  Google Font, Poppins -->
    <!-- CDN -->
    <!-- FontAweosme CDN -->
    <title>Project 1</title>
  </head>
  <body>
    <!-- Started -->
    <!-- Header -->
    <header>
      <nav>
        <!-- Logo -->
        <div class="logo">LOGO</div>
        <!-- Menus -->
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
        <!-- Search Area -->
        <div class="search-field">
          <input type="text" placeholder="Search" />
          <button>Search</button>
        </div>
      </nav>
    </header>
    <!-- Hero Section -->
    <section class="hero-section">
      <!-- Left Section of HERO -->
      <div class="hero-left-section">
        <h1>Hello, I am a <span> Web Developer</span></h1>
        <p>
          I am an aspiring <span>Full Stack JavaScript Developer</span> , who is
          currently working as <span>a Freelancer</span> for
          <span> National and International Client.</span>
        </p>
      </div>
      <!-- Right  Hero Section -->
      <div class="hero-right-section">
        <img src="data:image/png;base64,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" alt="Avatar" />
        <div>
          <button class="hero-right-section-btn">Chat With me</button>
        </div>
      </div>
    </section>
    <footer>
      <p>Copyright © 2022 LOGO. All rights reserved.</p>
      <ul>
        <li><a href="#">Github</a></li>
        <li><a href="#">LinkedIn</a></li>
        <li><a href="#">Instagram</a></li>
      </ul>
    </footer>
  </body>
</html>
