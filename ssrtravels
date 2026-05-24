<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SSR Travels - Drop Taxi Service</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins',sans-serif;
    }

    body{
      background:#f8f5ef;
      color:#222;
    }

    header{
      background:linear-gradient(135deg,#2b1700,#8b5a00);
      color:#fff;
      padding:18px 8%;
      display:flex;
      justify-content:space-between;
      align-items:center;
      position:sticky;
      top:0;
      z-index:1000;
    }

    .logo{
      font-size:32px;
      font-weight:700;
      letter-spacing:2px;
    }

    .logo span{
      color:#ffcc66;
    }

    nav a{
      text-decoration:none;
      color:#fff;
      margin-left:25px;
      font-weight:500;
      transition:.3s;
    }

    nav a:hover{
      color:#ffcc66;
    }

    .hero{
      min-height:90vh;
      display:flex;
      align-items:center;
      justify-content:space-between;
      padding:60px 8%;
      background:
      linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),
      url('https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1600&auto=format&fit=crop');
      background-size:cover;
      background-position:center;
      color:white;
      flex-wrap:wrap;
    }

    .hero-text{
      max-width:550px;
    }

    .hero-text h1{
      font-size:58px;
      line-height:1.1;
      margin-bottom:20px;
    }

    .hero-text h1 span{
      color:#ffcc66;
    }

    .hero-text p{
      font-size:18px;
      margin-bottom:30px;
      line-height:1.7;
    }

    .btn{
      display:inline-block;
      padding:14px 32px;
      background:#ffcc66;
      color:#000;
      border-radius:8px;
      text-decoration:none;
      font-weight:600;
      transition:.3s;
    }

    .btn:hover{
      background:#fff;
      transform:translateY(-2px);
    }

    .booking-box{
      background:white;
      padding:35px;
      border-radius:18px;
      width:360px;
      box-shadow:0 10px 30px rgba(0,0,0,.2);
      color:#222;
    }

    .booking-box h2{
      margin-bottom:20px;
      color:#5c3600;
    }

    .input-box{
      margin-bottom:16px;
    }

    .input-box input,
    .input-box select{
      width:100%;
      padding:14px;
      border:1px solid #ddd;
      border-radius:8px;
      outline:none;
      font-size:15px;
    }

    .book-btn{
      width:100%;
      border:none;
      padding:14px;
      background:#5c3600;
      color:white;
      border-radius:8px;
      font-size:16px;
      cursor:pointer;
      transition:.3s;
    }

    .book-btn:hover{
      background:#8b5a00;
    }

    section{
      padding:80px 8%;
    }

    .section-title{
      text-align:center;
      margin-bottom:50px;
    }

    .section-title h2{
      font-size:40px;
      color:#5c3600;
      margin-bottom:10px;
    }

    .section-title p{
      color:#777;
    }

    .services{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:25px;
    }

    .service-card{
      background:white;
      padding:35px 25px;
      border-radius:15px;
      text-align:center;
      box-shadow:0 5px 15px rgba(0,0,0,.08);
      transition:.3s;
    }

    .service-card:hover{
      transform:translateY(-8px);
    }

    .service-card h3{
      margin:15px 0;
      color:#5c3600;
    }

    .routes{
      overflow-x:auto;
    }

    table{
      width:100%;
      border-collapse:collapse;
      background:white;
      border-radius:12px;
      overflow:hidden;
      box-shadow:0 5px 15px rgba(0,0,0,.08);
    }

    table th{
      background:#5c3600;
      color:white;
      padding:16px;
    }

    table td{
      padding:16px;
      text-align:center;
      border-bottom:1px solid #eee;
    }

    .contact{
      background:linear-gradient(135deg,#2b1700,#8b5a00);
      color:white;
      border-radius:20px;
      text-align:center;
      padding:60px 30px;
    }

    .contact h2{
      font-size:42px;
      margin-bottom:15px;
    }

    .contact p{
      margin-bottom:20px;
      font-size:18px;
    }

    .phone{
      font-size:38px;
      font-weight:700;
      color:#ffcc66;
      margin-bottom:25px;
    }

    footer{
      background:#1a1a1a;
      color:#bbb;
      text-align:center;
      padding:25px;
      font-size:14px;
    }

    @media(max-width:900px){

      .hero{
        flex-direction:column;
        gap:40px;
        text-align:center;
      }

      .hero-text h1{
        font-size:42px;
      }

      nav{
        display:none;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">SSR <span>TRAVELS</span></div>

    <nav>
      <a href="#">Home</a>
      <a href="#services">Services</a>
      <a href="#routes">Routes</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">

    <div class="hero-text">
      <h1>Safe & Comfortable <span>Drop Taxi</span> Service</h1>

      <p>
        Bangalore to Chennai, Coimbatore, Madurai, Salem and more.
        Affordable one-way drop taxi service with professional drivers
        and 24/7 customer support.
      </p>

      <a href="tel:9500163182" class="btn">Call Now</a>
    </div>

    <div class="booking-box">
      <h2>Book Your Ride</h2>

      <div class="input-box">
        <input type="text" placeholder="Pickup Location">
      </div>

      <div class="input-box">
        <input type="text" placeholder="Drop Location">
      </div>

      <div class="input-box">
        <input type="date">
      </div>

      <div class="input-box">
        <select>
          <option>Select Vehicle</option>
          <option>Sedan</option>
          <option>SUV</option>
          <option>Tempo Traveller</option>
        </select>
      </div>

      <button class="book-btn">Book Taxi</button>
    </div>

  </section>

  <section id="services">

    <div class="section-title">
      <h2>Our Services</h2>
      <p>Reliable taxi service with safety and comfort.</p>
    </div>

    <div class="services">

      <div class="service-card">
        <h3>Driver Bata Included</h3>
        <p>No hidden charges. Professional drivers included.</p>
      </div>

      <div class="service-card">
        <h3>Toll Permit Included</h3>
        <p>Easy interstate travel with permits included.</p>
      </div>

      <div class="service-card">
        <h3>Safe & Secure</h3>
        <p>Well maintained vehicles for your comfortable ride.</p>
      </div>

      <div class="service-card">
        <h3>24/7 Support</h3>
        <p>Customer support available anytime for assistance.</p>
      </div>

    </div>

  </section>

  <section id="routes">

    <div class="section-title">
      <h2>Popular Routes</h2>
      <p>Bangalore to Tamil Nadu Drop Taxi Pricing</p>
    </div>

    <div class="routes">
      <table>

        <tr>
          <th>From</th>
          <th>To</th>
          <th>Distance</th>
          <th>Fare</th>
        </tr>

        <tr>
          <td>Bangalore</td>
          <td>Chennai</td>
          <td>340 KM</td>
          <td>₹5160</td>
        </tr>

        <tr>
          <td>Bangalore</td>
          <td>Coimbatore</td>
          <td>314 KM</td>
          <td>₹4796</td>
        </tr>

        <tr>
          <td>Bangalore</td>
          <td>Madurai</td>
          <td>421 KM</td>
          <td>₹6294</td>
        </tr>

        <tr>
          <td>Bangalore</td>
          <td>Salem</td>
          <td>187 KM</td>
          <td>₹3018</td>
        </tr>

        <tr>
          <td>Bangalore</td>
          <td>Erode</td>
          <td>237 KM</td>
          <td>₹2220</td>
        </tr>

      </table>
    </div>

  </section>

  <section id="contact">

    <div class="contact">
      <h2>Book Your Ride Today</h2>

      <p>Travel Safe • Reach Happy</p>

      <div class="phone">9500163182</div>

      <a href="https://wa.me/919500163182" class="btn">
        WhatsApp Booking
      </a>
    </div>

  </section>

  <footer>
    © 2025 SSR Travels. All Rights Reserved.
  </footer>

</body>
</html>
