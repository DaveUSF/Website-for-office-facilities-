<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Office Facilities</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
  <h1>Office Facilities Management</h1>
  <nav>
    <a href="#services">Services</a>
    <a href="#request">Request Service</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h2>Reliable Workplace Solutions</h2>
  <p>Maintaining a clean, safe, and productive office environment.</p>
</section>

<section id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">Cleaning & Sanitation</div>
    <div class="card">Maintenance & Repairs</div>
    <div class="card">IT & Equipment Support</div>
    <div class="card">Security & Access Control</div>
  </div>
</section>

<section id="request">
  <h2>Request a Service</h2>
  <form onsubmit="submitRequest(event)">
    <input type="text" placeholder="Full Name" required>
    <input type="email" placeholder="Email Address" required>
    <select required>
      <option value="">Select Service</option>
      <option>Cleaning</option>
      <option>Maintenance</option>
      <option>IT Support</option>
      <option>Security</option>
    </select>
    <textarea placeholder="Describe the issue..." required></textarea>
    <button type="submit">Submit Request</button>
  </form>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>Email: facilities@office.com</p>
  <p>Phone: (555) 123-4567</p>
</section>

<footer>
  <p>© 2026 Office Facilities Management</p>
</footer>

<script src="script.js"></script>
</body>
</html>
