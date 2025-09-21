<!doctype html>
<html lang="pa">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Tuhada Website Naam</title>
  <style>
    body{font-family:system-ui, -apple-system, "Segoe UI", Roboto, "Noto Sans", "Helvetica Neue"; margin:0; padding:0; line-height:1.6}
    header{background:#0b5; padding:24px; text-align:center; color:#fff}
    .container{max-width:980px; margin:20px auto; padding:0 16px}
    .hero{background:#f6f6f6; padding:20px; border-radius:8px}
    .grid{display:grid; grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); gap:12px; margin-top:12px}
    .card{padding:12px; border:1px solid #eee; border-radius:8px}
    footer{padding:16px; text-align:center; color:#666}
    a.btn{display:inline-block; padding:8px 14px; border-radius:6px; text-decoration:none; background:#07a; color:#fff}
  </style>
</head>
<body>
  <header>
    <h1>Tuhada Business / Naam</h1>
    <p>Short tagline — Punjabi / English</p>
  </header>

  <main class="container">
    <section class="hero">
      <h2>Welcome!</h2>
      <p>Eh simple website starter hai. Tusi is nu edit kar ke apne products, services, te contact info rakh sakde ho.</p>
      <a class="btn" href="#contact">Contact karo</a>
    </section>

    <section class="grid">
      <div class="card"><h3>Product 1</h3><p>Short description.</p></div>
      <div class="card"><h3>Product 2</h3><p>Short description.</p></div>
      <div class="card"><h3>About</h3><p>Thoda about text.</p></div>
    </section>

    <section id="contact" style="margin-top:18px">
      <h3>Contact</h3>
      <p>Phone: 98xxxxxxx • Email: you@example.com</p>
    </section>
  </main>

  <footer>
    © <span id="yr"></span> Tuhada Naam — Built with simple HTML
    <script>document.getElementById('yr').textContent=(new Date()).getFullYear();</script>
  </footer>
</body>
</html>
