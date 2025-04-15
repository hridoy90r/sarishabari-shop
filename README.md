# sarishabari-shop<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sarishabari Online Shop</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f8f9fa;
    }
    .navbar-brand {
      font-weight: bold;
    }
    .hero {
      background: #e3f2fd;
      padding: 60px 20px;
      text-align: center;
    }
    .product {
      border: 1px solid #ddd;
      padding: 15px;
      border-radius: 10px;
      background: white;
    }
    .form-section {
      background-color: #ffffff;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Sarishabari Shop</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#home">হোম</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">অ্যাবাউট</a></li>
          <li class="nav-item"><a class="nav-link" href="#services">সার্ভিসেস</a></li>
          <li class="nav-item"><a class="nav-link" href="#shop">শপ</a></li>
          <li class="nav-item"><a class="nav-link" href="#reviews">রিভিউ</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">কন্ট্যাক্ট</a></li>
          <li class="nav-item"><a class="nav-link" href="#login">লগইন</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <div class="container">
      <h1>স্বাগতম সারিশাবাড়ি অনলাইন শপে!</h1>
      <p>সেরা মানের প্রোডাক্ট ঘরে বসেই পেতে আজই অর্ডার করুন।</p>
    </div>
  </section>

  <!-- Products Section -->
  <section class="py-5" id="shop">
    <div class="container">
      <h2 class="mb-4">আমাদের প্রোডাক্টসমূহ</h2>
      <div class="row g-4">
        <div class="col-md-3">
          <div class="product">
            <h5>জামা</h5>
            <p>স্টাইলিশ পুরুষ ও মহিলা জামা</p>
            <a href="#" class="btn btn-primary btn-sm">বিস্তারিত দেখুন</a>
          </div>
        </div>
        <div class="col-md-3">
          <div class="product">
            <h5>কসমেটিকস</h5>
            <p>বিশ্বস্ত কসমেটিক ব্র্যান্ডের পণ্য</p>
            <a href="#" class="btn btn-primary btn-sm">বিস্তারিত দেখুন</a>
          </div>
        </div>
        <div class="col-md-3">
          <div class="product">
            <h5>ঘরোয়া পণ্য</h5>
            <p>প্রয়োজনীয় বাসার আইটেম</p>
            <a href="#" class="btn btn-primary btn-sm">বিস্তারিত দেখুন</a>
          </div>
        </div>
        <div class="col-md-3">
          <div class="product">
            <h5>ইলেকট্রনিকস</h5>
            <p>স্মার্ট গ্যাজেট ও আনুষঙ্গিক</p>
            <a href="#" class="btn btn-primary btn-sm">বিস্তারিত দেখুন</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Customer Review Section -->
  <section class="py-5 bg-light" id="reviews">
    <div class="container">
      <h2 class="mb-4">কাস্টমার রিভিউ</h2>
      <blockquote class="blockquote">
        <p>"প্রোডাক্ট কোয়ালিটি দারুণ এবং সময়মতো ডেলিভারি পেয়েছি!"</p>
        <footer class="blockquote-footer">রুমানা ইসলাম</footer>
      </blockquote>
      <blockquote class="blockquote">
        <p>"বিশ্বাসযোগ্য এবং সহজ অর্ডারিং সিস্টেম। খুবই খুশি।"</p>
        <footer class="blockquote-footer">শামীম হোসেন</footer>
      </blockquote>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="py-5" id="contact">
    <div class="container">
      <h2 class="mb-4">যোগাযোগ করুন</h2>
      <div class="form-section">
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">আপনার নাম</label>
            <input type="text" class="form-control" id="name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">ইমেইল</label>
            <input type="email" class="form-control" id="email" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">মেসেজ</label>
            <textarea class="form-control" id="message" rows="4" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">পাঠান</button>
        </form>
      </div>
    </div>
  </section>

  <!-- Login/Register Section -->
  <section class="py-5 bg-light" id="login">
    <div class="container">
      <h2 class="mb-4">লগইন / রেজিস্টার</h2>
      <div class="form-section">
        <form>
          <div class="mb-3">
            <label for="username" class="form-label">ইউজারনেম</label>
            <input type="text" class="form-control" id="username" required>
          </div>
          <div class="mb-3">
            <label for="password" class="form-label">পাসওয়ার্ড</label>
            <input type="password" class="form-control" id="password" required>
          </div>
          <button type="submit" class="btn btn-success">লগইন</button>
          <p class="mt-2">নতুন ইউজার? <a href="#">রেজিস্টার করুন</a></p>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3 mt-5">
    <p>&copy; 2025 Sarishabari Online Shop. All rights reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
