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
:root{
  --bg:#0b1220;
  --card:#121b2f;
  --text:#e9eefc;
  --muted:#b7c2e2;
  --accent:#6ea8fe;
  --border:rgba(255,255,255,.10);
}
*{box-sizing:border-box}
body{
  margin:0;
  font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  background: linear-gradient(180deg, var(--bg), #060a12 70%);
  color:var(--text);
}
a{color:inherit}
.container{max-width:1100px;margin:0 auto;padding:24px}
.nav{
  display:flex;align-items:center;justify-content:space-between;gap:16px;
  padding:14px 0;border-bottom:1px solid var(--border);
}
.brand{display:flex;flex-direction:column;gap:2px}
.brand strong{font-size:18px}
.brand span{font-size:13px;color:var(--muted)}
.menu{display:flex;gap:14px;flex-wrap:wrap}
.menu a{opacity:.9;text-decoration:none;font-size:14px}
.menu a:hover{opacity:1;text-decoration:underline}
.hero{
  padding:44px 0 18px;
  display:grid;grid-template-columns:1.25fr .75fr;gap:22px;align-items:start
}
.hero h1{margin:0 0 10px;font-size:42px;line-height:1.1}
.hero p{margin:0 0 18px;color:var(--muted);font-size:16px;line-height:1.6}
.card{
  background:rgba(18,27,47,.72);
  border:1px solid var(--border);
  border-radius:18px;
  padding:18px;
  box-shadow:0 20px 60px rgba(0,0,0,.25);
}
.btnrow{display:flex;gap:12px;flex-wrap:wrap}
.btn{
  display:inline-flex;align-items:center;justify-content:center;
  padding:11px 14px;border-radius:12px;text-decoration:none;
  border:1px solid var(--border);font-weight:600;font-size:14px;
}
.btn.primary{background:var(--accent);color:#071022;border-color:transparent}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
h2{margin:10px 0 10px;font-size:22px}
ul{margin:10px 0 0;padding-left:18px;color:var(--muted);line-height:1.6}
.small{color:var(--muted);font-size:13px;line-height:1.6}
.footer{
  margin-top:34px;padding:18px 0;border-top:1px solid var(--border);
  display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap
}
input, textarea{
  width:100%;padding:11px 12px;border-radius:12px;
  border:1px solid var(--border);background:rgba(255,255,255,.04);
  color:var(--text);outline:none
}
label{display:block;font-size:13px;color:var(--muted);margin:10px 0 6px}
@media (max-width:900px){
  .hero{grid-template-columns:1fr}
  .grid2,.grid3{grid-template-columns:1fr}
  .hero h1{font-size:34px}
}
function $(sel){ return document.querySelector(sel); }
function setText(sel, text){ const el=$(sel); if(el) el.textContent=text; }
function setHTML(sel, html){ const el=$(sel); if(el) el.innerHTML=html; }

function mountNav(){
  const s = window.SITE;
  setText("#companyName", s.companyName);
  setText("#tagline", s.tagline);
  setHTML("#navLinks", `
    <a href="index.html">Home</a>
    <a href="candidates.html">For Candidates</a>
    <a href="schools.html">For Schools</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
    <a href="blog.html">Blog</a>
    <a href="policies.html">Policies</a>
  `);

  setText("#footerCompany", s.companyName);
  setText("#footerPhone", s.phonePrimary);
  setText("#footerEmail", s.email);

  const loc = s.locations?.[0];
  if(loc) setHTML("#footerAddress", `${loc.city}<br>${loc.line1}<br>${loc.line2}`);
  if(s.socials?.linkedin) $("#lnkLinkedIn")?.setAttribute("href", s.socials.linkedin);
  if(s.socials?.facebook) $("#lnkFacebook")?.setAttribute("href", s.socials.facebook);
}
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Home</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <div class="nav">
      <div class="brand">
        <strong id="companyName"></strong>
        <span id="tagline"></span>
      </div>
      <div class="menu" id="navLinks"></div>
    </div>

    <section class="hero">
      <div>
        <h1 id="homeHeadline"></h1>
        <p id="homeIntro"></p>
        <div class="btnrow">
          <a class="btn primary" id="ctaPrimary" href="#">For Candidates</a>
          <a class="btn" id="ctaSecondary" href="#">For Schools</a>
        </div>
      </div>

      <div class="card">
        <h2>How we help schools</h2>
        <ul id="homeRoles"></ul>
        <p class="small" style="margin-top:12px">
          Need cover fast? <a href="contact.html">Contact us</a> to discuss requirements.
        </p>
      </div>
    </section>

    <div class="grid2">
      <div class="card">
        <h2>What you can expect</h2>
        <ul id="homeBullets"></ul>
      </div>
      <div class="card">
        <h2>Testimonials</h2>
        <div id="homeTestimonials"></div>
      </div>
    </div>

    <div class="footer">
      <div>
        <strong id="footerCompany"></strong>
        <div class="small" id="footerAddress"></div>
      </div>
      <div class="small">
        <div><strong>Phone:</strong> <span id="footerPhone"></span></div>
        <div><strong>Email:</strong> <span id="footerEmail"></span></div>
        <div style="margin-top:10px">
          <a id="lnkLinkedIn" href="#" target="_blank" rel="noreferrer">LinkedIn</a> ·
          <a id="lnkFacebook" href="#" target="_blank" rel="noreferrer">Facebook</a>
        </div>
      </div>
    </div>
  </div>

  <script src="config.js"></script>
  <script src="app.js"></script>
  <script>
    mountNav();
    const s = window.SITE;
    document.title = s.companyName + " | Home";
    document.querySelector("#homeHeadline").textContent = s.home.headline + s.companyName;
    document.querySelector("#homeIntro").textContent = s.home.intro;
    document.querySelector("#ctaPrimary").textContent = s.primaryCTA.label;
    document.querySelector("#ctaPrimary").href = s.primaryCTA.href;
    document.querySelector("#ctaSecondary").textContent = s.secondaryCTA.label;
    document.querySelector("#ctaSecondary").href = s.secondaryCTA.href;

    document.querySelector("#homeBullets").innerHTML =
      s.home.bullets.map(x => `<li>${x}</li>`).join("");

    document.querySelector("#homeRoles").innerHTML =
      s.home.roles.map(x => `<li>${x}</li>`).join("");

    document.querySelector("#homeTestimonials").innerHTML =
      s.home.testimonials.map(t => `
        <div style="margin:10px 0 14px">
          <div class="small">“${t.quote}”</div>
          <div style="margin-top:6px;opacity:.9"><strong>${t.name}</strong></div>
        </div>
      `).join("");
  </script>
</body>
</html>
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>For Candidates</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <div class="nav">
      <div class="brand">
        <strong id="companyName"></strong>
        <span id="tagline"></span>
      </div>
      <div class="menu" id="navLinks"></div>
    </div>

    <section class="hero">
      <div>
        <h1 id="candTitle"></h1>
        <p id="candText"></p>
        <div class="btnrow">
          <a class="btn primary" href="contact.html">Apply / Enquire</a>
          <a class="btn" href="schools.html">Hiring? Go to Schools</a>
        </div>
      </div>
      <div class="card">
        <h2>Highlights</h2>
        <ul id="candHighlights"></ul>
      </div>
    </section>

    <div class="card">
      <h2>How it works</h2>
      <div class="grid3" id="candSteps"></div>
    </div>

    <div class="footer">
      <div>
        <strong id="footerCompany"></strong>
        <div class="small" id="footerAddress"></div>
      </div>
      <div class="small">
        <div><strong>Phone:</strong> <span id="footerPhone"></span></div>
        <div><strong>Email:</strong> <span id="footerEmail"></span></div>
      </div>
    </div>
  </div>

  <script src="config.js"></script>
  <script src="app.js"></script>
  <script>
    mountNav();
    const s = window.SITE;
    document.title = s.companyName + " | For Candidates";
    document.querySelector("#candTitle").textContent = s.candidates.heroTitle;
    document.querySelector("#candText").textContent = s.candidates.heroText;

    document.querySelector("#candHighlights").innerHTML =
      s.candidates.highlights.map(x => `<li>${x}</li>`).join("");

    document.querySelector("#candSteps").innerHTML =
      s.candidates.steps.map((x,i)=>`
        <div class="card" style="padding:14px">
          <strong>Step ${i+1}</strong>
          <div class="small" style="margin-top:6px">${x}</div>
        </div>
      `).join("");
  </script>
</body>
</html>
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>For Schools</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <div class="nav">
      <div class="brand">
        <strong id="companyName"></strong>
        <span id="tagline"></span>
      </div>
      <div class="menu" id="navLinks"></div>
    </div>

    <section class="hero">
      <div>
        <h1 id="schTitle"></h1>
        <p id="schText"></p>
        <div class="btnrow">
          <a class="btn primary" href="contact.html">Request Staff</a>
          <a class="btn" href="candidates.html">Looking for work?</a>
        </div>
      </div>

      <div class="card">
        <h2>Services</h2>
        <ul id="schServices"></ul>
      </div>
    </section>

    <div class="grid2">
      <div class="card">
        <h2>Our approach</h2>
        <ul id="schApproach"></ul>
      </div>
      <div class="card">
        <h2>Compliance</h2>
        <p class="small">
          Add your compliance summary here (DBS/background checks, references, right-to-work, safeguarding training, etc.).
        </p>
        <a class="btn" href="policies.html">View Policies</a>
      </div>
    </div>

    <div class="footer">
      <div>
        <strong id="footerCompany"></strong>
        <div class="small" id="footerAddress"></div>
      </div>
      <div class="small">
        <div><strong>Phone:</strong> <span id="footerPhone"></span></div>
        <div><strong>Email:</strong> <span id="footerEmail"></span></div>
      </div>
    </div>
  </div>

  <script src="config.js"></script>
  <script src="app.js"></script>
  <script>
    mountNav();
    const s = window.SITE;
    document.title = s.companyName + " | For Schools";
    document.querySelector("#schTitle").textContent = s.schools.heroTitle;
    document.querySelector("#schText").textContent = s.schools.heroText;

    document.querySelector("#schServices").innerHTML =
      s.schools.services.map(x => `<li>${x}</li>`).join("");

    document.querySelector("#schApproach").innerHTML =
      s.schools.approach.map(x => `<li>${x}</li>`).join("");
  </script>
</body>
</html>
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>About</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <div class="nav">
      <div class="brand">
        <strong id="companyName"></strong>
        <span id="tagline"></span>
      </div>
      <div class="menu" id="navLinks"></div>
    </div>

    <section class="hero">
      <div>
        <h1 id="abtTitle"></h1>
        <p class="small">Update this page with your story, values, and what makes your service different.</p>
      </div>
      <div class="card">
        <h2>Quick links</h2>
        <div class="btnrow">
          <a class="btn primary" href="candidates.html">Candidates</a>
          <a class="btn" href="schools.html">Schools</a>
          <a class="btn" href="contact.html">Contact</a>
        </div>
      </div>
    </section>

    <div class="grid3" id="abtBlocks"></div>

    <div class="footer">
      <div>
        <strong id="footerCompany"></strong>
        <div class="small" id="footerAddress"></div>
      </div>
      <div class="small">
        <div><strong>Phone:</strong> <span id="footerPhone"></span></div>
        <div><strong>Email:</strong> <span id="footerEmail"></span></div>
      </div>
    </div>
  </div>

  <script src="config.js"></script>
  <script src="app.js"></script>
  <script>
    mountNav();
    const s = window.SITE;
    document.title = s.companyName + " | About";
    document.querySelector("#abtTitle").textContent = s.about.title;

    document.querySelector("#abtBlocks").innerHTML =
      s.about.blocks.map(b=>`
        <div class="card">
          <h2>${b.heading}</h2>
          <p class="small">${b.text}</p>
        </div>
      `).join("");
  </script>
</body>
</html>
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Contact</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <div class="nav">
      <div class="brand">
        <strong id="companyName"></strong>
        <span id="tagline"></span>
      </div>
      <div class="menu" id="navLinks"></div>
    </div>

    <section class="hero">
      <div>
        <h1 id="ctTitle"></h1>
        <p class="small" id="ctNote"></p>
        <div class="card" style="margin-top:16px">
          <h2>Quick contact</h2>
          <div class="small"><strong>Phone:</strong> <span id="phone"></span></div>
          <div class="small"><strong>Email:</strong> <a id="emailLink" href="#">Email us</a></div>
        </div>
      </div>

      <div class="card">
        <h2>Send a message</h2>
        <form id="contactForm">
          <label>Your name</label>
          <input name="name" required />
          <label>Your email</label>
          <input name="email" type="email" required />
          <label>Message</label>
          <textarea name="message" rows="6" required></textarea>
          <div class="btnrow" style="margin-top:12px">
            <button class="btn primary" type="submit">Generate email</button>
            <a class="btn" href="index.html">Back home</a>
          </div>
          <p class="small" style="margin-top:10px">
            This free site generates an email for you to send (no paid form backend needed).
          </p>
        </form>
      </div>
    </section>

    <div class="footer">
      <div>
        <strong id="footerCompany"></strong>
        <div class="small" id="footerAddress"></div>
      </div>
      <div class="small">
        <div><strong>Phone:</strong> <span id="footerPhone"></span></div>
        <div><strong>Email:</strong> <span id="footerEmail"></span></div>
      </div>
    </div>
  </div>

  <script src="config.js"></script>
  <script src="app.js"></script>
  <script>
    mountNav();
    const s = window.SITE;
    document.title = s.companyName + " | Contact";
    document.querySelector("#ctTitle").textContent = s.contact.title;
    document.querySelector("#ctNote").textContent = s.contact.note;
    document.querySelector("#phone").textContent = s.phonePrimary;

    const mail = s.email;
    const emailLink = document.querySelector("#emailLink");
    emailLink.textContent = mail;
    emailLink.href = "mailto:" + mail;

    document.querySelector("#contactForm").addEventListener("submit", (e)=>{
      e.preventDefault();
      const fd = new FormData(e.target);
      const subject = encodeURIComponent("Enquiry for " + s.companyName);
      const body = encodeURIComponent(
        `Name: ${fd.get("name")}\nEmail: ${fd.get("email")}\n\nMessage:\n${fd.get("message")}`
      );
      window.location.href = `mailto:${mail}?subject=${subject}&body=${body}`;
    });
  </script>
</body>
</html>
<!doctype html><html lang="en"><head>
<meta charset="utf-8"/><meta name="viewport" content="width=device-width,initial-scale=1"/>
<title>Blog</title><link rel="stylesheet" href="styles.css"/>
</head><body><div class="container">
<div class="nav"><div class="brand"><strong id="companyName"></strong><span id="tagline"></span></div>
<div class="menu" id="navLinks"></div></div>

<section class="hero">
  <div><h1>Blog</h1><p class="small">Add articles here later (or link to Medium/Substack).</p></div>
  <div class="card"><h2>Coming soon</h2><p class="small">Tip: You can duplicate this page for each post.</p></div>
</section>

<div class="footer"><div><strong id="footerCompany"></strong><div class="small" id="footerAddress"></div></div>
<div class="small"><div><strong>Phone:</strong> <span id="footerPhone"></span></div>
<div><strong>Email:</strong> <span id="footerEmail"></span></div></div></div>
</div>
<script src="config.js"></script><script src="app.js"></script><script>mountNav();</script>
</body></html>
<!doctype html><html lang="en"><head>
<meta charset="utf-8"/><meta name="viewport" content="width=device-width,initial-scale=1"/>
<title>Policies</title><link rel="stylesheet" href="styles.css"/>
</head><body><div class="container">
<div class="nav"><div class="brand"><strong id="companyName"></strong><span id="tagline"></span></div>
<div class="menu" id="navLinks"></div></div>

<section class="hero">
  <div>
    <h1>Policies</h1>
    <p class="small">
      Add your safeguarding, recruitment, privacy, equal opportunities, and compliance policy links here.
    </p>
  </div>
  <div class="card">
    <h2>Suggested list</h2>
    <ul>
      <li>Safeguarding Policy</li>
      <li>Recruitment & Vetting Policy</li>
      <li>Privacy Policy</li>
      <li>Equal Opportunities</li>
      <li>Complaints Policy</li>
    </ul>
  </div>
</section>

<div class="footer"><div><strong id="footerCompany"></strong><div class="small" id="footerAddress"></div></div>
<div class="small"><div><strong>Phone:</strong> <span id="footerPhone"></span></div>
<div><strong>Email:</strong> <span id="footerEmail"></span></div></div></div>
</div>
<script src="config.js"></script><script src="app.js"></script><script>mountNav();</script>
</body></html>
