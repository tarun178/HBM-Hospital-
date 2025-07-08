<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HBM Hospital</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #fdfefe;
            color: #333;
        }
        .navbar {
            background-color: #e3f2fd;
        }
        .navbar-brand, .nav-link {
            color: #0056b3 !important;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1580281657522-279c0e8b0c83?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.7);
        }
        .logo {
            max-height: 60px;
        }
        .service-icon {
            font-size: 3rem;
            color: #0288d1;
        }
        .p-4.border {
            background-color: #ffffff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        footer {
            background-color: #f0f4f8;
            padding: 20px 0;
            color: #333;
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img src="logo.png" alt="HBM Hospital Logo" class="logo">
      HBM Hospital
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#services">Our Services</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact Us</a></li>
      </ul>
    </div>
  </div>
</nav>

<section id="home" class="hero">
  <div class="text-center">
    <h1>HBM Hospital</h1>
    <p class="lead">जहाँ भरोसा भी इलाज का हिस्सा है</p>
  </div>
</section>

<section id="services" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Our Services</h2>
    <div class="row g-4">
      <div class="col-md-4 text-center">
        <div class="p-4 border rounded">
          <i class="service-icon bi bi-heart-pulse"></i>
          <h4 class="mt-3">Emergency Care</h4>
          <p>24x7 emergency services with advanced life-support systems.</p>
        </div>
      </div>
      <div class="col-md-4 text-center">
        <div class="p-4 border rounded">
          <i class="service-icon bi bi-syringe"></i>
          <h4 class="mt-3">Diagnostics</h4>
          <p>High-quality lab and imaging facilities at one roof.</p>
        </div>
      </div>
      <div class="col-md-4 text-center">
        <div class="p-4 border rounded">
          <i class="service-icon bi bi-hospital"></i>
          <h4 class="mt-3">Inpatient Services</h4>
          <p>Comfortable rooms and dedicated staff for patient care.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="contact" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-4">Contact Us</h2>
    <div class="row">
      <div class="col-md-6 mb-4">
        <h5>Our Location</h5>
        <p>Gopiram Complex, Jusri Road, Tanki Tiraha, Makrana</p>
        <div class="ratio ratio-16x9">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3560.1234567890123!2d74.746123!3d27.038456!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39632b2c3e0a1234%3A0xabcdef1234567890!2sGopiram%20Complex%2C%20Makrana!5e0!3m2!1sen!2sin!4v1690000000000" allowfullscreen="" loading="lazy"></iframe>
        </div>
      </div>
      <div class="col-md-6">
        <h5>Get in Touch</h5>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Name</label>
            <input type="text" class="form-control" id="name" placeholder="अपना नाम दर्ज करें">
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email</label>
            <input type="email" class="form-control" id="email" placeholder="अपना ईमेल दर्ज करें">
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="4" placeholder="अपना संदेश दर्ज करें"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">भेजें</button>
        </form>
      </div>
    </div>
  </div>
</section>

<footer class="text-center">
  <div class="container">
    <p>&copy; 2025 HBM Hospital. सर्वाधिकार सुरक्षित।</p>
  </div>
</footer>

<!-- Bootstrap JS & Icons -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.js"></script>
</body>
</html>
