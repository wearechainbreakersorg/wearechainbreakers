<!DOCTYPE html>
<html>
<head>
  <title>Chain Breakers</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin:0;
      font-family: 'Segoe UI', sans-serif;
      background:#0a0a0a;
      color:white;
    }

    .container {
      max-width:1100px;
      margin:auto;
      padding:60px 20px;
      text-align:center;
    }

    h1 {
      font-size:48px;
      margin-bottom:20px;
    }

    h2 {
      font-size:32px;
      margin-bottom:20px;
    }

    p {
      color:#ccc;
      line-height:1.6;
    }

    .btn {
      display:inline-block;
      margin:10px;
      padding:14px 28px;
      background:white;
      color:black;
      text-decoration:none;
      border-radius:8px;
      font-weight:bold;
    }

    .hero {
      background: linear-gradient(black, #111);
      padding:100px 20px;
    }

    .section {
      border-top:1px solid #222;
    }

    .grid {
      display:grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap:20px;
      margin-top:40px;
    }

    .card {
      background:#111;
      padding:25px;
      border-radius:12px;
      border:1px solid #222;
    }

    .highlight {
      font-size:20px;
      margin-top:20px;
    }

    footer {
      text-align:center;
      padding:30px;
      border-top:1px solid #222;
      color:#777;
    }
  </style>
</head>

<body>

<!-- HERO -->
<div class="hero">
  <div class="container">
    <h1>Breaking Chains.<br>Rebuilding Lives.</h1>
    <p class="highlight">
      Helping incarcerated individuals and returning citizens find freedom, purpose, and restoration.
    </p>
    <a href="#contact" class="btn">Get Involved</a>
  </div>
</div>

<!-- MISSION -->
<div class="container section">
  <h2>Our Mission</h2>
  <p>
    Born from personal transformation after serving nine years of a fifteen-year sentence,
    Chain Breakers exists to help incarcerated individuals and returning citizens break free 
    from cycles of bondage through faith in God, mentorship, and support.
  </p>
  <p>
    With humility and compassion, we meet people where they are—inside prison and beyond—
    offering hope, guidance, and practical tools to rebuild their lives.
  </p>
</div>

<!-- PROGRAMS -->
<div class="container section">
  <h2>Our Programs</h2>

  <div class="grid">
    <div class="card">
      <h3>Prison Outreach</h3>
      <p>Faith-based mentorship and encouragement inside prison.</p>
    </div>

    <div class="card">
      <h3>Reentry Support</h3>
      <p>Helping returning citizens rebuild and transition successfully.</p>
    </div>

    <div class="card">
      <h3>Basic Needs</h3>
      <p>Providing hygiene items, meals, clothing, and transportation.</p>
    </div>

    <div class="card">
      <h3>Community</h3>
      <p>Connecting individuals with mentorship and strong support systems.</p>
    </div>
  </div>
</div>

<!-- IMPACT -->
<div class="container section">
  <h2>Why It Matters</h2>
  <p>
    When people are given support, mentorship, and real opportunity,
    cycles can be broken. Every life restored strengthens families,
    communities, and future generations.
  </p>
</div>

<!-- GET INVOLVED -->
<div class="container section">
  <h2>Get Involved</h2>

  <div class="grid">
    <div class="card">
      <h3>Volunteer</h3>
      <p>Help support outreach, mentorship, and community efforts.</p>
    </div>

    <div class="card">
      <h3>Donate</h3>
      <p>Support meals, hygiene kits, and reentry assistance.</p>
    </div>

    <div class="card">
      <h3>Partner</h3>
      <p>Collaborate with us as a church, business, or organization.</p>
    </div>
  </div>
</div>

<!-- CONTACT -->
<div class="container section" id="contact">
  <h2>Contact Us</h2>
  <p>Email: info@chainbreakers.org</p>
  <p>Phone: 980-781-9366</p>
  <p>Website: WeAreChainBreakers.org</p>
</div>

<!-- FOOTER -->
<footer>
  © 2026 Chain Breakers. All rights reserved.
</footer>

</body>
</html>
