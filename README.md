<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Photography Studio</title>
  <link rel="stylesheet" href="aj.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
</head>
<body>
  
  <header>
    <div class="logo"><img src="img35.png" width="150" height="50" alt="logo"></div>
    <nav class="nav">
      <ul>
        <li><a href="#services">Services</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Frame the Moment <br> <span>Capture the Story</span></h1>
    <p>Transform ordinary into extraordinary. Let us create stunning memories for you.</p>
    <button class="btn">Book Now</button>
  </section>

  <section id="services" class="services">
    <h2>What We Offer</h2>
    <p>Professional photography and videography services for all occasions.</p>
    <div class="service-cards">
      <div class="card">
        <h3>Photography</h3>
        <p>Stunning photography to capture your precious moments.</p>
      </div>
      <div class="card">
        <h3>Videography</h3>
        <p>Immersive videos that tell your story with elegance.</p>
      </div>
      <div class="card">
        <h3>Custom Shoots</h3>
        <p>Tailored photo and video shoots designed just for you.</p>
      </div>
    </div>
    <div class="stats">
      <div>
        <h3>1000+</h3>
        <p>Projects Completed</p>
      </div>
      <div>
        <h3>4.9/5</h3>
        <p>Customer Rating</p>
      </div>
      <div>
        <h3>50+</h3>
        <p>Team Members</p>
      </div>
    </div>
  </section>

  <section id="portfolio" class="portfolio">
    <h2>Featured Work</h2>
    <div class="gallery">
      <img src="img21.png" width="258.34" height="172.16" alt="Portfolio 1">
      <img src="img22.png" width="258.34" height="172.16" alt="portfolio 2">
      <img src="img23.png" width="258.34" height="172.16" alt="Portfolio 3">
      <img src="img24.png" width="258.34" height="172.16" alt="Portfolio 4">
    </div>
    <button class="btn">View More</button>
  </section>

  <section class="instagram">
    <h2>@yourstudiohandle</h2>
    <p>Follow us on Instagram for our latest creations and behind-the-scenes moments.</p>
    <div class="insta-gallery">
      <img src="img31.png" width="193.75" height="172"  alt="Instagram 1">
      <img src="img32.png" width="193.75" height="172"  alt="Instagram 2">
      <img src="img33.png" width="193.75" height="172"  alt="Instagram 3">
      <img src="img34.png" width="193.75" height="172"  alt="Instagram 4">
    </div>
  </section>

  <section id="contact" class="cta">
    <h2>Ready to Start Your Journey?</h2>
    <p>Let’s create something extraordinary together. Book your session today!</p>
    <button class="btn">Contact Us</button>
  </section>

  <footer>
    <p>&copy; 2025 ankit's studio. All Rights Reserved.</p>
    <ul>
      <li><a href="#">Privacy Policy</a></li>
      <li><a href="#">Terms of Service</a></li>
    </ul>
  </footer>
</body>
</html>
body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color:rgb(61, 61, 61);
    background-color: white;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    background: rgb(51, 52, 52);
    color: white;
    position: sticky;
    top: 0;
    z-index: 1000;
}

header .nav ul {
    display: flex;
    list-style: none;
    gap: 1.5rem;
}

header .nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s ease;
}

header .nav ul li a:hover {
    color: rgb(245, 96, 96);
}

.hero {
    text-align: center;
    padding: 5rem 2rem;
    background: linear-gradient(to bottom right, rgb(209, 33, 209), rgb(30, 128, 248));
    color: white;
}

.hero h1 {
    font-size: 3rem;
    line-height: 1.2;
    margin-bottom: 1rem;
    text-transform: capitalize;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.hero .btn {
    background: white;
    color: rgb(64, 64, 64);
    padding: 0.8rem 1.5rem;
    border: none;
    text-transform: uppercase;
    font-weight: bold;
    border-radius: 5px;
    cursor: pointer;
    transition:  0.3s ease;
}

.hero .btn:hover {
    background: rgb(255, 66, 66);
    color: white;
}

.carousel img {
    width: 100%;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.services {
    padding: 4rem 2rem;
    text-align: center;
    background-color: white;
}

.services h2 {
    font-size: 2.5rem;
    margin-bottom: 1.5rem;
    color: rgb(44, 44, 44);
}

.services .service-cards {
    display: flex;
    justify-content: center;
    gap: 2rem;
    flex-wrap: wrap;
}

.services .card {
    background: white;
    border-radius: 8px;
    padding: 2rem;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.services .card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
}

.services .card h3 {
    margin-bottom: 1rem;
    color: rgb(46, 112, 255);
}

.services .stats {
    margin-top: 2rem;
    display: flex;
    justify-content: center;
    gap: 2rem;
}

.services .stats div {
    background: white;
    padding: 1rem 2rem;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.portfolio {
    padding: 4rem 2rem;
    text-align: center;
}

.portfolio h2 {
    font-size: 2.5rem;
    margin-bottom: 1.5rem;
    color: rgb(47, 47, 47);
}

.portfolio .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
}

.portfolio .gallery img {
    width: 100%;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.portfolio .gallery img:hover {
    transform: scale(1.05);
    box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
}

.instagram {
    padding: 4rem 2rem;
    background: white;
    text-align: center;
}

.instagram h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: rgb(54, 54, 54);
}

.instagram p {
    margin-bottom: 2rem;
    color:grey;
}

.instagram .insta-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 1rem;
}

.instagram .insta-gallery img {
    width: 100%;
    border-radius: 8px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.instagram .insta-gallery img:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.cta {
    background: linear-gradient(to bottom right, rgb(217, 47, 217), rgb(42, 130, 255));
    color: white;
    text-align: center;
    padding: 4rem 2rem;
}

.cta h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.cta p {
    margin-bottom: 2rem;
    font-size: 1.2rem;
}

.cta .btn {
    background: white;
    color: rgb(60, 60, 60);
    padding: 0.8rem 1.5rem;
    border-radius: 5px;
    font-weight: bold;
    text-transform: uppercase;
    transition:  0.3s ease;
}

.cta .btn:hover {
    background: rgb(255, 61, 61);
    color: white;
}

footer {
    background: rgb(21, 23, 36);
    color: white;
    text-align: center;
    padding: 2rem;
}
