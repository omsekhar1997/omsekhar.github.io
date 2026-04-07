<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Omsekhar Mandala | Digital Marketing Expert</title>

<link href="https://api.fontshare.com/v2/css?f[]=general-sans@400,500,600,700&display=swap" rel="stylesheet"/>

<style>
body {
  margin: 0;
  font-family: 'General Sans', sans-serif;
  background: #f7f6f2;
  color: #221f1a;
}

/* Container */
.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

/* Header */
header {
  position: sticky;
  top: 0;
  background: #fff;
  padding: 15px 0;
  border-bottom: 1px solid #eee;
}

.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-weight: 700;
}

.nav-links a {
  margin-left: 20px;
  text-decoration: none;
  color: #666;
}

/* HERO SECTION */
.hero {
  padding: 80px 0;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center; /* FIXED GAP */
  gap: 40px;
}

/* TEXT */
.hero-copy h1 {
  font-size: clamp(2.5rem, 5vw, 5rem);
  line-height: 1.05; /* FIXED */
  letter-spacing: -0.03em;
  max-width: 14ch; /* FIXED */
  word-break: keep-all;
}

.hero-accent {
  color: #d66a00;
  font-weight: 800;
}

.hero-copy p {
  margin-top: 12px;
  color: #666;
  max-width: 500px;
}

/* BUTTONS */
.btn {
  display: inline-block;
  padding: 12px 22px;
  border-radius: 30px;
  margin-top: 20px;
  text-decoration: none;
  font-weight: 600;
}

.btn-primary {
  background: #0f6b6f;
  color: white;
}

.btn-secondary {
  border: 1px solid #ccc;
  color: #333;
  margin-left: 10px;
}

/* RIGHT CARD */
.hero-card {
  background: #fff;
  padding: 25px;
  border-radius: 12px;
  border: 1px solid #eee;
}

.mini-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
  margin-top: 20px;
}

.mini-stat {
  background: #f2f2f2;
  padding: 15px;
  border-radius: 8px;
}

.mini-stat strong {
  display: block;
  font-size: 20px;
}

/* MOBILE */
@media (max-width: 768px) {
  .hero-grid {
    grid-template-columns: 1fr;
  }

  .hero-copy h1 {
    max-width: 100%;
  }

  .btn {
    display: block;
    margin-right: 0;
  }

  .btn-secondary {
    margin-left: 0;
  }
}
</style>
</head>

<body>

<header>
  <div class="container nav">
    <div class="logo">Omsekhar Mandala</div>
    <div class="nav-links">
      <a href="#">Services</a>
      <a href="#">Results</a>
      <a href="#">Contact</a>
    </div>
  </div>
</header>

<section class="hero">
  <div class="container hero-grid">

    <!-- LEFT CONTENT -->
    <div class="hero-copy">

      <h1>
        <span class="hero-accent">Driving leads, visibility,</span><br>
        and scalable business growth<br>
        through digital marketing.
      </h1>

      <p>
        I help businesses generate high-quality leads using Google Ads, Meta Ads,
        and high-converting funnels.
      </p>

      <a href="#" class="btn btn-primary">View Case Studies</a>
      <a href="#" class="btn btn-secondary">Hire Me</a>

    </div>

    <!-- RIGHT CARD -->
    <div class="hero-card">

      <p><strong>Executive Snapshot</strong></p>
      <p style="color:#666;">
        Results-driven marketer focused on lead generation and ROI-based growth systems.
      </p>

      <div class="mini-grid">
        <div class="mini-stat">
          <span>Leads</span>
          <strong>4000+</strong>
        </div>
        <div class="mini-stat">
          <span>Avg CPL</span>
          <strong>₹375</strong>
        </div>
        <div class="mini-stat">
          <span>Platforms</span>
          <strong>Google | Meta</strong>
        </div>
        <div class="mini-stat">
          <span>Focus</span>
          <strong>ROI</strong>
        </div>
      </div>

    </div>

  </div>
</section>

</body>
</html>
