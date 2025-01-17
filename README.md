<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Washateria</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to Washateria</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#offers">Offers</a>
      <a href="#booking">Book Now</a>
      <a href="#contact">Contact Us</a>
    </nav>
  </header>

  <section id="services">
    <h2>Our Services</h2>
    <div class="service">
      <h3>Exteriora</h3>
      <p>A simple exterior wash for 4 KD.</p>
    </div>
    <div class="service">
      <h3>HOLA</h3>
      <p>Interior and exterior wash for 5-7 KD.</p>
    </div>
  </section>

  <section id="offers">
    <h2>Special Offers</h2>
    <p>Get 40% off on premium washes!</p>
  </section>

  <section id="booking">
    <h2>Book Your Wash</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="car">Car Type:</label>
      <select id="car" name="car">
        <option value="sedan">Sedan</option>
        <option value="suv">SUV</option>
        <option value="jeep">Jeep</option>
      </select>

      <label for="service">Choose Service:</label>
      <select id="service" name="service">
        <option value="exteriora">Exteriora</option>
        <option value="hola">HOLA</option>
      </select>

      <label for="date">Date:</label>
      <input type="date" id="date" name="date" required>

      <button type="submit">Submit</button>
    </form>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Phone: +965 12345678</p>
    <p>Email: info@washateria.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Washateria. All rights reserved.</p>
  </footer>
</body>
</html>
