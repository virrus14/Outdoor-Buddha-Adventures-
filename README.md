# Outdoor-Buddha-Adventures-
Trekking Company Website Description  A professional and user-friendly website for a trekking and adventure travel company, designed to showcase trekking packages, mountain destinations, and outdoor experiences.  

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Outdoor Buddha Adventures</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f7f2;
      color: #24352b;
    }

    header {
      background: #183b2a;
      color: white;
      padding: 22px;
      text-align: center;
    }

    nav {
      background: #10291d;
      padding: 15px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 10px;
    }

    .hero {
      background:
        linear-gradient(#0005, #0007),
        url("https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=1600&q=80");

      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      padding: 110px 20px;
    }

    .hero h1 {
      font-size: 42px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 25px;
    }

    .button {
      display: inline-block;
      background: #e49b42;
      color: white;
      padding: 14px 25px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 50px 20px;
      text-align: center;
    }

    .packages {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: white;
      padding: 25px;
      border-radius: 12px;
      width: 280px;
      box-shadow: 0 4px 15px #0001;
    }

    .card h3 {
      margin-bottom: 15px;
      color: #183b2a;
    }

    .card p {
      margin-bottom: 15px;
      line-height: 1.6;
    }

    footer {
      background: #183b2a;
      color: white;
      text-align: center;
      padding: 25px;
    }
  </style>
</head>

<body>

  <header>
    <h2>Outdoor Buddha Adventures</h2>
    <p>Explore Nature • Discover Adventure</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#treks">Treks</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero" id="home">
    <h1>Adventure Awaits You</h1>
    <p>Discover breathtaking mountains and unforgettable trekking experiences.</p>

    <a class="button" href="#treks">Explore Treks</a>
  </div>

  <section id="treks">
    <h2>Our Trekking Packages</h2>

    <div class="packages">

      <div class="card">
        <h3>Sandakphu Trek</h3>
        <p>Explore beautiful Himalayan trails and mountain views.</p>
        <p>Duration: 5 Days</p>
        <a class="button" href="#contact">Enquire Now</a>
      </div>

      <div class="card">
        <h3>Goechala Trek</h3>
        <p>Experience an exciting adventure in the Himalayas.</p>
        <p>Duration: 8 Days</p>
        <a class="button" href="#contact">Enquire Now</a>
      </div>

      <div class="card">
        <h3>Day Hiking</h3>
        <p>Enjoy refreshing nature walks and scenic trails.</p>
        <p>Duration: 1 Day</p>
        <a class="button" href="#contact">Enquire Now</a>
      </div>

    </div>
  </section>

  <section id="about">
    <h2>About Our Company</h2>
    <p style="max-width:700px;margin:20px auto;line-height:1.8;">
      Outdoor Buddha Adventures is your partner for memorable
      trekking and outdoor experiences. Discover nature, explore
      mountain trails, and create unforgettable memories with us.
    </p>
  </section>

  <section id="contact">
    <h2>Book Your Adventure</h2>
    <p style="margin:20px;">Contact us to plan your next trekking journey.</p>

    <a class="button"
       href="https://wa.me/91XXXXXXXXXX?text=Hello%2C%20I%20want%20to%20book%20a%20trek">
      WhatsApp Us
    </a>
  </section>

  <footer>
    <p>© 2026 Outdoor Buddha Adventures</p>
    <p>Explore More. Trek More.</p>
  </footer>

</body>
</html>
