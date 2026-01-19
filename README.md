<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Inspiring Teachers | Education Recruitment</title>

  <!-- Basic SEO -->
  <meta name="description" content="Education recruitment agency connecting schools with inspiring teachers and support staff." />

  <!-- Google Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Inter', sans-serif;
      color: #1f2937;
      background: #ffffff;
      line-height: 1.6;
    }
    a { text-decoration: none; color: inherit; }

    /* Layout */
    .container { max-width: 1200px; margin: auto; padding: 24px; }
    .grid { display: grid; gap: 24px; }
    .grid-2 { grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); }
    .grid-3 { grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); }

    /* Header */
    header {
      background: #0f172a;
      color: #ffffff;
      padding: 20px 0;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    nav strong { font-size: 22px; }
    nav a { margin-left: 18px; font-size: 14px; opacity: 0.9; }
    nav a:hover { opacity: 1; text-decoration: underline; }

    /* Hero */
    .hero {
      background: linear-gradient(135deg, #1e3a8a, #2563eb);
      color: #ffffff;
      padding: 80px 24px;
      text-align: center;
    }
    .hero h1 { font-size: 42px; margin-bottom: 16px; }
    .hero p { max-width: 700px; margin: auto; font-size: 18px; opacity: 0.95; }
    .hero .buttons {
      margin-top: 32px;
      display: flex;
      justify-content: center;
      gap: 16px;
      flex-wrap: wrap;
    }
    .btn {
      padding: 14px 22px;
      border-radius: 6px;
      font-weight: 600;
      font-size: 14px;
      display: inline-block;
    }
    .btn-primary { background: #ffffff; color: #1e3a8a; }
    .btn-secondary { background: transparent; border: 1px solid #ffffff; color: #ffffff; }

    /* Sections */
    section { padding: 70px 0; }
    h2 { font-size: 28px; margin-bottom: 18px; }
    .card {
      border: 1px solid #e5e7eb;
      border-radius: 8px;
      padding: 24px;
      background: #ffffff;
    }

    /* CTA */
    .cta {
      background: #f1f5f9;
      text-align: center;
      padding: 60px 24px;
    }

    /* Footer */
    footer {
      background: #0f172a;
      color: #cbd5f5;
      padding: 40px 0;
      font-size: 14px;
    }
    footer strong { color: #ffffff; }
    footer a { display: block; margin-top: 8px; opacity: 0.9; }
  </style>
</head>

<body>

<!-- HEADER -->
<header>
  <div class="container">
    <nav>
      <strong>Inspiring Teachers</strong>
      <div>
        <a href="#about">About</a>
        <a href="#candidates">Candidates</a>
        <a href="#schools">Schools</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </div>
</header>

<!-- HERO -->
<section class="hero">
  <h1>Education Recruitment That Puts People First</h1>
  <p>
    We connect inspiring teachers, teaching assistants, and support staff
    with schools that value quality, care, and long-term success.
  </p>
  <div class="buttons">
    <a href="#candidates" class="btn btn-primary">For Candidates</a>
    <a href="#schools" class="btn btn-secondary">For Schools</a>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="container">
    <div class="grid grid-2">
      <div>
        <h2>Welcome to Inspiring Teachers</h2>
        <p>
          We are an education recruitment agency built on trust, transparency,
          and genuine relationships. Our mission is simple: match the right
          educators with the right environments.
        </p>
      </div>
      <div class="card">
        <ul>
          <li>✔ Experienced education consultants</li>
          <li>✔ Fully vetted, compliant candidates</li>
          <li>✔ Day-to-day, long-term & permanent roles</li>
          <li>✔ Dedicated candidate & school support</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- CANDIDATES -->
<section id="candidates">
  <div class="container">
    <h2>For Candidates</h2>
    <div class="grid grid-3">
      <div class="card">Flexible supply & long-term roles</div>
      <div class="card">Clear registration & onboarding</div>
      <div class="card">Supportive consultants who care</div>
    </div>
  </div>
</section>

<!-- SCHOOLS -->
<section id="schools">
  <div class="container">
    <h2>For Schools</h2>
    <div class="grid grid-3">
      <div class="card">Fast, reliable cover staff</div>
      <div class="card">Compliance-first recruitment</div>
      <div class="card">Cost-effective staffing solutions</div>
    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta" id="contact">
  <h2>Let’s Work Together</h2>
  <p>Contact us today to discuss your staffing or career needs.</p>
  <a href="mailto:hello@inspiringteachers.org" class="btn btn-primary" style="margin-top:20px;">
    Get in Touch
  </a>
</section>

<!-- FOOTER -->
<footer>
  <div class="container grid grid-2">
    <div>
      <strong>Inspiring Teachers</strong>
      <p>Education Recruitment Agency</p>
    </div>
    <div>
      <a href="mailto:hello@inspiringteachers.org">hello@inspiringteachers.org</a>
      <a href="#">Privacy Policy</a>
      <a href="#">Safeguarding Policy</a>
    </div>
  </div>
</footer>

</body>
</html>
