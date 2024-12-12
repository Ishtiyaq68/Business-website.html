<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Business Name</title>
  <link rel="stylesheet" href="style.css">
  <style>
    /* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background: linear-gradient(to right, #aae1d9, #aaaee1, #d7bd85);
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  background: #333;
  color: #fff;
}
.nav-links {
  list-style: none;
  display: flex;
  gap: 15px;
}
.nav-links li a {
  color: #fff;
  text-decoration: none;
}

/* Hero Section */
.hero {
  text-align: center;
  padding: 50px;
  background: #f4f4f4;
}
.hero h1 {
  font-size: 3rem;
}
.cta {
  background: #333;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

/* Sections */
section {
  padding: 20px;
  text-align: center;
}
.services {
  display: flex;
  justify-content: space-around;
}

/* Contact Section */
form {
  max-width: 400px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 10px;
}
form input, form textarea, form button {
  padding: 10px;
  font-size: 1rem;
  
}
form button {
  background: linear-gradient(to right, #8c9e6e, #1396a9);;
  color: #fff;
  border: none;
  cursor: pointer;
  
}



  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <nav class="navbar">
      <div class="logo">BusinessName</div>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Welcome to my Website</h1>
    <p>Your trusted partner in [ishtiyaq rasool group of companies]</p>
    <a href="#services" class="cta">Our Services</a>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Us</h2>
    <p>We provide exceptional services to help your business grow.</p>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <h2>Our Services</h2>
    <div class="service">
      <h3>Service 1</h3>
      <p>Details about service 1.</p>
    </div>
    <div class="service">
      <h3>Service 2</h3>
      <p>Details about service 2.</p>
    </div>
    <div class="service">
      <h3>Service 3</h3>
      <p>Details about service 3.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 ishtiyaqrasooltraders. All Rights Reserved.</p>
  </footer>

  <script src="script.js">
    document.addEventListener("DOMContentLoaded", () => {
  console.log("Website is ready!");
  // Add interactive features here
});

  </script>
</body>
</html>
