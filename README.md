<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nature Exploration</title>
  <style>
    :root {
      --bg-color: #f2e6d9; /* Light beige */
      --nav-bg-color: #8b5e3c; /* Brown */
      --text-color: #3a2e25; /* Dark brown */
      --highlight-color: #a8875a; /* Sandy brown */
    }

    body {
      font-family: Arial, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
    }

    header {
      background-color: var(--nav-bg-color);
      padding: 1rem;
      text-align: center;
      color: #fff;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: var(--highlight-color);
    }

    nav a {
      color: #fff;
      padding: 1rem;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      background-color: var(--nav-bg-color);
    }

    section {
      padding: 2rem;
      margin: 1rem;
      border-radius: 8px;
      background-color: #e0ccb2;
    }

    #home, #promo, #about, #explore, #tour, #reservations, #store, #gallery {
      min-height: 200px;
    }

    footer {
      background-color: var(--nav-bg-color);
      text-align: center;
      padding: 1rem;
      color: #fff;
      position: relative;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Nature Exploration</h1>
  </header>

  <!-- Navigation Menu with Internal Links -->
  <nav>
    <a href="#home">Home</a>
    <a href="#promo">Promotional Video</a>
    <a href="#about">About Us</a>
    <a href="#explore">Explore with Birds & Animals</a>
    <a href="#tour">Virtual Tour</a>
    <a href="#reservations">Reservations</a>
    <a href="#store">Store</a>
    <a href="#gallery">Visitors Gallery</a>
  </nav>

  <!-- Sections -->
  <section id="home">
    <h2>Home</h2>
    <p>Welcome to Nature Exploration, your gateway to the wonders of the wild.</p>
  </section>

  <section id="promo">
    <h2>Promotional Video</h2>
    <p>Experience nature through our captivating video tour.</p>
    <!-- Embed your promotional video here with an iframe -->
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Learn more about our mission to connect people with nature.</p>
  </section>

  <section id="explore">
    <h2>Explore with Birds & Animals</h2>
    <p>Discover the amazing wildlife and natural habitats.</p>
  </section>

  <section id="tour">
    <h2>Virtual Tour</h2>
    <p>Take a virtual stroll through our natural landscape.</p>
  </section>

  <section id="reservations">
    <h2>Reservations</h2>
    <p>Book your visit using our interactive calendar below.</p>
    <!-- Placeholder for a calendar -->
  </section>

  <section id="store">
    <h2>Store</h2>
    <p>Shop for exclusive Nature Exploration merchandise.</p>
    <!-- Add links to an external store or product listings -->
  </section>

  <section id="gallery">
    <h2>Visitors Gallery</h2>
    <p>Check out the beautiful photos shared by our visitors.</p>
    <!-- Gallery or photo sharing -->
  </section>

  <footer>
    <p>&copy; 2024 Nature Exploration. All rights reserved.</p>
    <p>Visit us at: <a href="https://yourusername.github.io/nature-exploration/" target="_blank">GitHub Pages Link</a></p>
  </footer>

</body>
</html>


