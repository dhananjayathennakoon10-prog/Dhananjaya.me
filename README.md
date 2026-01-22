
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dhananjaya Thennakoon</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: #fafafa;
      color: #1f2937;
    }

    /* NAV */
    nav {
      max-width: 1200px;
      margin: auto;
      padding: 25px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav .logo {
      font-style: italic;
      font-weight: 500;
      color: #111827;
    }

    nav .menu a {
      margin-left: 28px;
      text-decoration: none;
      color: #6b7280;
      font-size: 0.95rem;
    }

    nav .menu a.active,
    nav .menu a:hover {
      color: #2563eb;
    }

    /* HERO */
    .hero {
      max-width: 1200px;
      margin: auto;
      padding: 80px 20px;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 80px;
      align-items: center;
    }

    .hero img {
      width: 100%;
      max-width: 420px;
      border-radius: 12px;
      background: #e5e7eb;
    }

    .hero p {
      font-size: 1rem;
      line-height: 1.8;
      color: #374151;
    }

    .hero a {
      color: #2563eb;
      text-decoration: none;
    }

    /* SECTIONS */
    section {
      max-width: 1200px;
      margin: auto;
      padding: 100px 20px;
      border-top: 1px solid #e5e7eb;
    }

    section h2 {
      font-size: 1.6rem;
      margin-bottom: 20px;
    }

    section p {
      max-width: 700px;
      color: #4b5563;
      line-height: 1.7;
    }

    footer {
      max-width: 1200px;
      margin: auto;
      padding: 40px 20px;
      border-top: 1px solid #e5e7eb;
      color: #6b7280;
      font-size: 0.9rem;
    }

    @media (max-width: 900px) {
      .hero {
        grid-template-columns: 1fr;
        gap: 40px;
      }
    }
  </style>
</head>
<body>

  <nav>
    <div class="logo">dhananjaya.me</div>
    <div class="menu">
      <a class="active" href="#home">home</a>
      <a href="#business">business</a>
      <a href="#media">media</a>
      <a href="#apps">apps</a>
      <a href="#philanthropy">philanthropy</a>
      <a href="#contact">contact</a>
    </div>
  </nav>

  <div class="hero" id="home">
    <img src="https://via.placeholder.com/420x520" alt="Profile">
    <p>
      I'm <strong>Dhananjaya Thennakoon</strong>, an entrepreneur and creator focused on
      business, media, technology, and meaningful impact.
      <br><br>
      I build digital products, create content, and explore ideas that help people grow.
      This space is a simple reflection of my work and thinking.
    </p>
  </div>

   

  <section class="logos">
    <div class="logo-row">
      <img src="https://via.placeholder.com/100x40" alt="logo">
      <img src="https://via.placeholder.com/100x40" alt="logo">
      <img src="https://via.placeholder.com/100x40" alt="logo">
      <img src="https://via.placeholder.com/100x40" alt="logo">
      <img src="https://via.placeholder.com/100x40" alt="logo">
      <img src="https://via.placeholder.com/100x40" alt="logo">
    </div>
  </section>

  <footer>
    <p>© 2026 Dhananjaya Thennakoon</p>
    <div class="social">
      <span>Facebook</span> · <span>Instagram</span> · <span>LinkedIn</span> · <span>YouTube</span>
    </div>
  </footer>

</body>
</html>
