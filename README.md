<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Feroz Fisherman | Professional Sport Netting Services Pakistan</title>

  <meta name="description" content="Professional sports netting, cricket nets, safety nets and protective netting services across Pakistan. Contact us for quality netting and installation.">
  <meta name="keywords" content="sports netting Pakistan, cricket net Karachi, safety nets Karachi, indoor cricket nets, fishing nets, bird protection nets, Feroz Fisherman">
  <meta name="author" content="Feroz Fisherman">

  <meta property="og:title" content="Feroz Fisherman - Sport Netting Services">
  <meta property="og:description" content="Professional netting solutions across Pakistan">
  <meta property="og:type" content="website">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      color: #17202a;
      background: #f7f9fa;
    }

    a {
      text-decoration: none;
    }

    /* HEADER */
    header {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: rgba(255,255,255,0.97);
      box-shadow: 0 2px 15px rgba(0,0,0,0.08);
    }

    .navbar {
      max-width: 1200px;
      margin: auto;
      padding: 15px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo {
      font-size: 24px;
      font-weight: 800;
      color: #087f5b;
    }

    .logo span {
      color: #f39c12;
    }

    nav a {
      color: #222;
      margin-left: 25px;
      font-weight: 600;
    }

    nav a:hover {
      color: #087f5b;
    }

    /* HERO */
    .hero {
      min-height: 650px;
      display: flex;
      align-items: center;
      background:
        linear-gradient(rgba(0,0,0,.60),rgba(0,0,0,.60)),
        url("https://images.unsplash.com/photo-1540747913346-19e32dc3e97e?auto=format&fit=crop&w=1800&q=85")
        center/cover;
      color: white;
    }

    .hero-content {
      max-width: 1200px;
      width: 100%;
      margin: auto;
      padding: 80px 20px;
    }

    .hero h1 {
      font-size: clamp(42px, 6vw, 75px);
      line-height: 1.05;
      max-width: 800px;
      margin-bottom: 25px;
    }

    .hero p {
      font-size: 21px;
      max-width: 700px;
      margin-bottom: 35px;
    }

    .buttons {
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 15px 27px;
      border-radius: 50px;
      font-weight: bold;
      display: inline-block;
      transition: .3s;
    }

    .btn-primary {
      background: #087f5b;
      color: white;
    }

    .btn-primary:hover {
      background: #056647;
      transform: translateY(-3px);
    }

    .btn-whatsapp {
      background: #25d366;
      color: white;
    }

    .btn-whatsapp:hover {
      transform: translateY(-3px);
    }

    /* GENERAL */
    section {
      padding: 80px 20px;
    }

    .container {
      max-width: 1200px;
      margin: auto;
    }

    .section-title {
      text-align: center;
      margin-bottom: 50px;
    }

    .section-title h2 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    .section-title p {
      color: #687078;
    }

    /* SERVICES */
    .services {
      display: grid;
      grid-template-columns: repeat(3,1fr);
      gap: 25px;
    }

    .service {
      background: white;
      border-radius: 18px;
      overflow: hidden;
      box-shadow: 0 8px 30px rgba(0,0,0,.08);
      transition: .3s;
    }

    .service:hover {
      transform: translateY(-8px);
    }

    .service img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .service-content {
      padding: 25px;
    }

    .service h3 {
      font-size: 22px;
      margin-bottom: 10px;
    }

    .service p {
      color: #667085;
    }

    /* ABOUT */
    .about {
      background: white;
    }

    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 50px;
      align-items: center;
    }

    .about img {
      width: 100%;
      border-radius: 20px;
      box-shadow: 0 15px 40px rgba(0,0,0,.15);
    }

    .about h2 {
      font-size: 40px;
      margin-bottom: 20px;
    }

    .about p {
      color: #667085;
      margin-bottom: 18px;
    }

    /* WHY US */
    .why {
      display: grid;
      grid-template-columns: repeat(4,1fr);
      gap: 20px;
    }

    .why-box {
      background: white;
      padding: 30px 20px;
      text-align: center;
      border-radius: 18px;
      box-shadow: 0 7px 25px rgba(0,0,0,.07);
    }

    .why-box .icon {
      font-size: 40px;
      margin-bottom: 15px;
    }

    .why-box h3 {
      margin-bottom: 8px;
    }

    /* GALLERY */
    .gallery {
      display: grid;
      grid-template-columns: repeat(3,1fr);
      gap: 15px;
    }

    .gallery img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      border-radius: 15px;
      transition: .3s;
    }

    .gallery img:hover {
      transform: scale(1.03);
    }

    /* CTA */
    .cta {
      background: #087f5b;
      color: white;
      text-align: center;
    }

    .cta h2 {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .cta p {
      margin-bottom: 25px;
      font-size: 18px;
    }

    /* CONTACT */
    .contact-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
    }

    .contact-card {
      background: white;
      padding: 35px;
      border-radius: 20px;
      box-shadow: 0 7px 25px rgba(0,0,0,.07);
    }

    .contact-card h3 {
      font-size: 25px;
      margin-bottom: 20px;
    }

    .contact-item {
      margin: 15px 0;
      font-size: 17px;
    }

    .map {
      width: 100%;
      height: 350px;
      border: 0;
      border-radius: 20px;
    }

    /* FOOTER */
    footer {
      background: #111827;
      color: white;
      text-align: center;
      padding: 35px 20px;
    }

    footer p {
      color: #cbd5e1;
    }

    /* FLOATING WHATSAPP */
    .whatsapp {
      position: fixed;
      right: 20px;
      bottom: 20px;
      width: 62px;
      height: 62px;
      background: #25d366;
      color: white;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 30px;
      box-shadow: 0 5px 20px rgba(0,0,0,.25);
      z-index: 9999;
    }

    /* MOBILE */
    @media(max-width: 900px) {
      nav {
        display: none;
      }

      .services,
      .gallery {
        grid-template-columns: 1fr 1fr;
      }

      .about-grid,
      .contact-grid {
        grid-template-columns: 1fr;
      }

      .why {
        grid-template-columns: 1fr 1fr;
      }
    }

    @media(max-width: 600px) {
      section {
        padding: 60px 15px;
      }

      .hero {
        min-height: 600px;
      }

      .services,
      .gallery,
      .why {
        grid-template-columns: 1fr;
      }

      .hero h1 {
        font-size: 43px;
      }

      .hero p {
        font-size: 17px;
      }

      .section-title h2,
      .about h2,
      .cta h2 {
        font-size: 32px;
      }

      .gallery img {
        height: 230px;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="navbar">
    <div class="logo">
      Feroz<span>Fisherman</span>
    </div>

    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<!-- HERO -->
<section class="hero" id="home">
  <div class="hero-content">

    <h1>Professional Sport & Safety Netting Services</h1>

    <p>
      High-quality cricket nets, sports netting, safety nets,
      bird protection nets and custom netting solutions across Pakistan.
    </p>

    <div class="buttons">
      <a class="btn btn-primary"
         href="#services">
         View Services
      </a>

      <a class="btn btn-whatsapp"
         href="https://wa.me/923452355608"
         target="_blank">
         WhatsApp Us
      </a>
    </div>

  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <div class="container">

    <div class="section-title">
      <h2>Our Services</h2>
      <p>Professional netting solutions for homes, businesses and sports facilities.</p>
    </div>

    <div class="services">

      <div class="service">
        <img src="https://images.unsplash.com/photo-1531415074968-036ba1b575da?auto=format&fit=crop&w=900&q=85">
        <div class="service-content">
          <h3>Indoor Cricket Nets</h3>
          <p>
            Complete cricket netting solutions for indoor cricket
            academies, schools, clubs and training facilities.
          </p>
        </div>
      </div>

      <div class="service">
        <img src="https://images.unsplash.com/photo-1593786481097-46f4c8e1e6c4?auto=format&fit=crop&w=900&q=85">
        <div class="service-content">
          <h3>Sports Netting</h3>
          <p>
            Professional sports protection nets for cricket,
            football, badminton and other sports facilities.
          </p>
        </div>
      </div>

      <div class="service">
        <img src="https://images.unsplash.com/photo-1527515862127-a9badb13b12e?auto=format&fit=crop&w=900&q=85">
        <div class="service-content">
          <h3>Safety Nets</h3>
          <p>
            Durable safety netting for construction sites,
            balconies, buildings and commercial properties.
          </p>
        </div>
      </div>

      <div class="service">
        <img src="https://images.unsplash.com/photo-1444464666168-49d633b86797?auto=format&fit=crop&w=900&q=85">
        <div class="service-content">
          <h3>Bird Protection Nets</h3>
          <p>
            Effective bird control netting for balconies,
            warehouses, factories and commercial buildings.
          </p>
        </div>
      </div>

      <div class="service">
        <img src="https://images.unsplash.com/photo-1544551763-46a013bb70d5?auto=format&fit=crop&w=900&q=85">
        <div class="service-content">
          <h3>Fishing Nets</h3>
          <p>
            Quality fishing net solutions for commercial
            fishermen and marine applications.
          </p>
        </div>
      </div>

      <div class="service">
        <img src="https://images.unsplash.com/photo-1589923188900-85dae523342b?auto=format&fit=crop&w=900&q=85">
        <div class="service-content">
          <h3>Custom Netting</h3>
          <p>
            Custom-made netting according to your required
            size, material, mesh and application.
          </p>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="about" id="about">
  <div class="container">

    <div class="about-grid">

      <div>
        <img src="https://images.unsplash.com/photo-1579952363873-27f3bade9f55?auto=format&fit=crop&w=1200&q=85">
      </div>

      <div>
        <h2>Quality Netting You Can Trust</h2>

        <p>
          Feroz Fisherman provides professional netting solutions
          for sports, safety, fishing and property protection.
        </p>

        <p>
          We focus on strong materials, accurate measurements,
          professional installation and long-lasting performance.
        </p>

        <p>
          Our services are available for residential, commercial,
          industrial and sports facilities.
        </p>

        <a class="btn btn-primary"
           href="https://wa.me/923452355608"
           target="_blank">
           Get a Free Quote
        </a>
      </div>

    </div>
  </div>
</section>

<!-- WHY US -->
<section>
  <div class="container">

    <div class="section-title">
      <h2>Why Choose Us?</h2>
      <p>Professional service from measurement to installation.</p>
    </div>

    <div class="why">

      <div class="why-box">
        <div class="icon">⭐</div>
        <h3>Quality Material</h3>
        <p>Strong and durable netting materials.</p>
      </div>

      <div class="why-box">
        <div class="icon">📏</div>
        <h3>Custom Sizes</h3>
        <p>Netting manufactured according to your measurements.</p>
      </div>

      <div class="why-box">
        <div class="icon">🔧</div>
        <h3>Professional Installation</h3>
        <p>Experienced installation for different applications.</p>
      </div>

      <div class="why-box">
        <div class="icon">🇵🇰</div>
        <h3>Across Pakistan</h3>
        <p>Services available in multiple cities across Pakistan.</p>
      </div>

    </div>
  </div>
</section>

<!-- GALLERY -->
<section id="gallery">
  <div class="container">

    <div class="section-title">
      <h2>Our Work</h2>
      <p>Explore our netting solutions and installations.</p>
    </div>

    <div class="gallery">

      <img src="https://images.unsplash.com/photo-1531415074968-036ba1b575da?auto=format&fit=crop&w=1000&q=85">

      <img src="https://images.unsplash.com/photo-1579952363873-27f3bade9f55?auto=format&fit=crop&w=1000&q=85">

      <img src="https://images.unsplash.com/photo-1593786481097-46f4c8e1e6c4?auto=format&fit=crop&w=1000&q=85">

      <img src="https://images.unsplash.com/photo-1544551763-46a013bb70d5?auto=format&fit=crop&w=1000&q=85">

      <img src="https://images.unsplash.com/photo-1444464666168-49d633b86797?auto=format&fit=crop&w=1000&q=85">

      <img src="https://images.unsplash.com/photo-1527515862127-a9badb13b12e?auto=format&fit=crop&w=1000&q=85">

    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta">
  <div class="container">

    <h2>Need Professional Netting?</h2>

    <p>
      Contact us today for measurements, pricing and installation.
    </p>

    <div class="buttons" style="justify-content:center;">

      <a class="btn btn-whatsapp"
         href="https://wa.me/923452355608"
         target="_blank">
         💬 WhatsApp Now
      </a>

      <a class="btn"
         style="background:white;color:#087f5b;"
         href="tel:+923452355608">
         📞 Call Now
      </a>

    </div>

  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="container">

    <div class="section-title">
      <h2>Contact Us</h2>
      <p>Get in touch for a quotation.</p>
    </div>

    <div class="contact-grid">

      <div class="contact-card">

        <h3>Feroz Fisherman</h3>

        <div class="contact-item">
          📞 <strong>Phone:</strong>
          <a href="tel:+923452355608">
            +92 345 2355608
          </a>
        </div>

        <div class="contact-item">
          💬 <strong>WhatsApp:</strong>
          <a href="https://wa.me/923452355608" target="_blank">
            Chat on WhatsApp
          </a>
        </div>

        <div class="contact-item">
          📍 <strong>Service Area:</strong>
          Pakistan
        </div>

        <div class="contact-item">
          ⭐ <strong>Google Business:</strong>
          <a href="https://share.google/XUAconVaBemGcqYk3"
             target="_blank">
            View Google Business Profile
          </a>
        </div>

      </div>

      <div>
        <!-- Replace the URL below with your exact Google Maps embed URL -->
        <iframe
          class="map"
          src="https://www.google.com/maps?q=Karachi%20Pakistan&output=embed"
          loading="lazy">
        </iframe>
      </div>

    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>
    © 2026 Feroz Fisherman. All Rights Reserved.
  </p>

  <p>
    Professional Sport Netting & Safety Netting Services in Pakistan
  </p>
</footer>

<!-- FLOATING WHATSAPP -->
<a class="whatsapp"
   href="https://wa.me/923452355608"
   target="_blank"
   aria-label="Chat on WhatsApp">
  💬
</a>

</body>
</html>
