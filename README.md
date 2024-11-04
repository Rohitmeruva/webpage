# webpage
Welcome to our fashion page, where expert knowledge and sophistication come together to showcase the latest in fashion trends. Our fashion experts scoured the globe to bring you the most up-to-date styles, from haute couture to ready-to-wear collections. This project is based on a fashion campany called TONES.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fashion Made Simple</title>
  <style>
    
 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
  }
  
  /* Navigation Bar */
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
  }
  
  .logo {
    font-size: 1.5em;
    font-weight: bold;
  }
  
  nav ul {
    list-style: none;
    display: flex;
    gap: 30px;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    letter-spacing: 1px;
  }
  
  .icons a {
    color: #fff;
    margin-left: 20px;
    text-decoration: none;
    font-size: 1.2em;
  }
  
  /* Social Media Sidebar */
  .social-media {
    position: fixed;
    top: 50%;
    left: 10px;
    transform: translateY(-50%);
    display: flex;
    flex-direction: column;
    gap: 15px;
  }
  
  .social-media a {
    color: #fff;
    font-size: 1.2em;
    text-decoration: none;
  }
  
  /* Hero Section */
  .hero {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    text-align: center;
    position: relative;
  }
  
  .hero-content {
    position: relative;
    z-index: 1;
  }
  
  .hero h1 {
    font-size: 3em;
    line-height: 1.2;
    font-weight: bold;
  }
  
  .hero h1 .highlight {
    color: #e91e63;
  }
  
  .hero button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 1em;
    font-weight: bold;
    color: #fff;
    background: transparent;
    border: 2px solid #fff;
    cursor: pointer;
    transition: background 0.3s ease;
  }
  
  .hero button:hover {
    background: #e91e63;
    color: #fff;
  }
  
  .hero-image {
    position: absolute;
    right: 20%;
    z-index: 0;
  }
  
  .hero-image img {
    max-width: 500px;
    opacity: 0.8;
  }
  </style>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navigation Bar -->
  <header>
    <div class="logo">TONES FASHION VERGE </div>
    <nav>
      <ul>
        <li><a href="https://www.tonesfashion.com/account/login?return_url=%2Faccount" target="https://www.tonesfashion.com/account/login?return_url=%2Faccount">log in</a></li>
        <li><a href="https://www.tonesfashion.com/" target="https://www.tonesfashion.com/">home</a></li>
        <li><a href="https://www.tonesfashion.com/collections/shirts" target="https://www.tonesfashion.com/collections/shirts">Collection</a></li>
        <li><a href="https://www.famousbirthdays.com/people/the-fashion-verge.html" target="https://www.famousbirthdays.com/people/the-fashion-verge.html">About us</a></li>
      </ul>
    </nav>
    <div class="icons">
      <a href="#"><i class="fas fa-shopping-cart"></i></a>
      <a href="#"><i class="fas fa-search"></i></a>
    </div>
  </header>

  <!-- Social Media Sidebar -->
  <div class="social-media">
    <a href="#"><i class="fab fa-facebook-f"></i></a>
    <a href="#"><i class="fab fa-twitter"></i></a>
    <a href="#"><i class="fab fa-instagram"></i></a>
  </div>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>FASHION <span class="highlight">MADE</span> SIMPLE</h1>
      <button>Shop Now</button>
    </div>
    <div class="hero-image">
      <img src="Fashion model.png" alt="Fashion Model">
    </div>
  </section>

  <!-- Link to Font Awesome for Icons -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <script src="script.js"></script>
</body>
</html>
