<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Smart Parking System</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #222;
    }
    header {
      background: #004aad;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      margin: 0 10px;
      color: #fff;
      text-decoration: none;
    }
    .hero {
      text-align: center;
      padding: 3rem 1rem;
      background: linear-gradient(135deg, #4facfe, #00f2fe);
      color: white;
    }
    .hero h1 {
      font-size: 2.5rem;
margin-bottom: 1rem;
    }
    .section {
      padding: 2rem 1rem;
      max-width: 1000px;
      margin: auto;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .card h3 { margin-top: 0; }
    .btn {
      display: inline-block;
      padding: 0.5rem 1rem;
      background: #004aad;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 0.5rem;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #eee;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
<header>
    <h1>Smart Parking System</h1>
    <nav>
      <a href="#features">Features</a>
      <a href="#lots">Find Parking</a>
      <a href="#pricing">Pricing</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Find a Parking Spot in Seconds</h1>
    <p>Real‑time availability, easy booking, and secure payments.</p>
    <a href="#lots" class="btn">Find Parking</a>
  </section>

  <section id="features" class="section">
    <h2>Features</h2>
    <div class="cards">
      <div class="card">
        <h3>Real‑time Data</h3>
        <p>See available spots instantly with live updates.</p>
      </div>
      <div class="card">
        <h3>EV Support</h3>
        <p>Reserve and charge your electric vehicle with ease.</p>
      </div>
      <div class="card">
        <h3>Secure Payments</h3>
        <p>Pay with UPI, cards, or wallets safely and quickly.</p>
      </div>
      <div class="card">
        <h3>Open API</h3>
        <p>Integrate parking data into your apps and systems.</p>
      </div>
    </div>
</section>

  <section id="lots" class="section">
    <h2>Nearby Parking Lots</h2>
    <div class="cards">
      <div class="card">
        <h3>City Center Plaza</h3>
        <p>68 free spots · ₹40/hr · EV Ready</p>
        <a href="#" class="btn">Book</a>
      </div>
      <div class="card">
        <h3>Riverfront West</h3>
        <p>12 free spots · ₹30/hr · Open Lot</p>
        <a href="#" class="btn">Book</a>
      </div>
      <div class="card">
        <h3>Tech Park Tower</h3>
        <p>180 free spots · ₹60/hr · EV Ready</p>
        <a href="#" class="btn">Book</a>
      </div>
    </div>
  </section>

  <section id="pricing" class="section">
    <h2>Pricing Plans</h2>
    <div class="cards">
      <div class="card">
        <h3>Starter</h3>
        <p>Free · 2 parking lots · Basic analytics</p>
        <a href="#" class="btn">Choose</a>
      </div>
      <div class="card">
        <h3>Pro</h3>
        <p>₹4,999/mo · 20 lots · Realtime API</p>
        <a href="#" class="btn">Choose</a>
      </div>
      <div class="card">
        <h3>Enterprise</h3>
<p>Custom · Unlimited lots · Custom dashboards</p>
        <a href="#" class="btn">Contact Sales</a>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: hello@smartparking.example<br>Phone: ‪+91‑98765‑43210‬</p>
    <a href="mailto:hello@smartparking.example" class="btn">Send Email</a>
  </section>

  <footer>
    © <span id="year"></span> Smart Parking System. All rights reserved.
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
