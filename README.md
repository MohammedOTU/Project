<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <title>Dog Walking</title>
</head>
<body>

  <header>
    <img src="logo.png" alt="Company Logo">
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#register">Register</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#faq">Help/FAQ</a></li>
        <li><a href="#team">Meet the Team</a></li>
        <li><a href="#location">Our Location</a></li>
      </ul>
    </nav>
  </header>

  <main>
       <header>
    <img src="packages.png" alt="Packages of Dog Walking">
     </header>

    <section id="home">
      <button id="registerButton" onclick="location.href='#register'">Register</button>
      <div id="dogPhotos">
        <img src="dog1.jpg" alt="Dog 1">
        <img src="dog2.jpg" alt="Dog 2">
        <!-- Add more dog images -->
      </div>
      <div id="whyChooseUs">
        <h2>Why Choose Us?</h2>
        <p>We provide reliable and caring dog walking services to keep your furry friend happy and healthy.</p>
      </div>
      <div id="aboutUs">
        <h2>About Us</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
      </div>
      <div id="reviews">
        <h2>Reviews</h2>
        <div class="review">
          <p>"Great service! My dog loves their walks."</p>
          <p>- Happy Customer</p>
        </div>
        <!-- Add more reviews -->
      </div>
      <div id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@dogwalking.com</p>
        <p>Phone: 123-456-7890</p>
      </div>
    </section>

    <section id="register">
      <h2>Register Your Pet</h2>
      <!-- Registration form goes here -->
    </section>

    <section id="about">
      <h2>About Us</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
    </section>

    <section id="faq">
      <h2>Help/FAQ</h2>
      <!-- Add FAQ content here -->
    </section>

    <section id="team">
      <h2>Meet the Team</h2>
      <!-- Add team members and their info here -->
    </section>

    <section id="location">
      <h2>Our Location</h2>
      <!-- Add map with pin and address here -->
    </section>
  </main>

  <footer>
    <div id="contactFooter">
      <p>Follow us on social media:</p>
      <a href="#" target="_blank">Facebook</a>
      <a href="#" target="_blank">Twitter</a>
      <a href="#" target="_blank">Instagram</a>
    </div>
  </footer>

</body>
</html>
