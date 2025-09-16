<!doctype html>
<html lang="my">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>MLBB Diamond Top-up — Coming Soon</title>
  <meta name="description" content="Fast • Secure • Instant — Global MLBB Diamond Top-up. Coming soon. Subscribe to get notified." />
  <!-- Open Graph for social shares -->
  <meta property="og:title" content="MLBB Diamond Top-up — Coming Soon" />
  <meta property="og:description" content="Fast • Secure • Instant — Global MLBB Diamond Top-up. Coming soon. Subscribe to get notified." />
  <meta property="og:image" content="banner-placeholder.jpg" />
  <meta name="theme-color" content="#0b1226" />

  <style>
    /* Simple modern style — single-file for easy hosting */
    :root{
      --bg:#071028;
      --card:#0f1724;
      --accent:#ffd166;
      --muted:#97a0b6;
      --glass: rgba(255,255,255,0.04);
      --glass-2: rgba(255,255,255,0.02);
      --radius:14px;
      --maxw:1100px;
    }
    *{box-sizing:border-box}
    body{
      margin:0; font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
      background: linear-gradient(180deg,#040816 0%, #071028 60%); color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
    }
    .wrap{max-width:var(--maxw); margin:32px auto; padding:24px}
    header{display:flex;align-items:center;gap:16px;margin-bottom:18px}
    .logo{
      width:60px;height:60px;border-radius:12px;background:linear-gradient(135deg,#ff9f1c,#ffdd00); display:flex;align-items:center;justify-content:center;color:#06102c;font-weight:700;font-size:20px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.45);
    }
    h1{margin:0;font-size:22px}
    p.lead{margin:6px 0 18px;color:var(--muted)}

    /* Hero */
    .hero{
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:var(--radius); padding:28px; display:grid; grid-template-columns: 1fr 360px; gap:20px; align-items:center;
      box-shadow: 0 8px 40px rgba(3,8,23,0.6);
      border: 1px solid rgba(255,255,255,0.03);
    }
    .hero-left h2{font-size:28px;margin:0 0 10px}
    .badge{display:inline-block;padding:6px 10px;border-radius:999px;background:var(--glass);color:var(--accent);font-weight:600;margin-bottom:8px}
    .hero-left ul{padding-left:18px;color:var(--muted);margin:14px 0}
    .cta{
      display:flex; gap:10px; margin-top:12px;
    }
    .btn{
      background:linear-gradient(90deg,var(--accent),#ffb84d);
      color:#06102c;padding:12px 16px;border-radius:12px;border:none;font-weight:700;cursor:pointer;
      box-shadow: 0 8px 20px rgba(255,170,50,0.12);
    }
    .btn.alt{
      background:transparent;color:#e6eef8;border:1px solid rgba(255,255,255,0.06);
    }

    /* Right card */
    .card{
      background: linear-gradient(180deg,var(--card), #0b1320);
      padding:18px;border-radius:12px; border:1px solid rgba(255,255,255,0.03);
    }
    .card h3{margin:0 0 8px}
    .price-list{display:flex;flex-direction:column;gap:10px}
    .package{display:flex;justify-content:space-between;align-items:center;padding:10px;border-radius:10px;background:var(--glass-2)}
    .package .name{font-weight:700}
    .small{font-size:13px;color:var(--muted)}

    /* Sections */
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:22px}
    .feature{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent); padding:16px;border-radius:12px}
    .center{text-align:center}
    footer{margin-top:28px;color:var(--muted);font-size:13px;padding:12px 0;text-align:center}

    /* Responsive */
    @media (max-width:880px){
      .hero{grid-template-columns:1fr; padding:18px}
      .grid{grid-template-columns:1fr}
    }

    /* small badge */
    .pill{display:inline-block;padding:6px 10px;background:rgba(255,255,255,0.03);border-radius:999px;color:var(--accent);font-weight:700}
    a.link{color:var(--accent);text-decoration:none}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">GD</div>
      <div>
        <h1>Global MLBB Top-up</h1>
        <p class="lead">Fast • Secure • Instant — Buy diamonds from anywhere in the world.</p>
      </div>
    </header>

    <!-- HERO -->
    <main class="hero" id="top">
      <div class="hero-left">
        <div class="badge">COMING SOON</div>
        <h2>💎 MLBB Diamond Top-up — Instant Delivery</h2>
        <p class="small">We are preparing to launch our official Codashop partner store. Subscribe to get launch updates, special promos and whitelist early access.</p>

        <ul>
          <li>🔒 Secure payments (PayPal, Card)</li>
          <li>⚡ Instant diamond delivery</li>
          <li>🌍 Global support & multi-currency</li>
        </ul>

        <div class="cta">
          <button class="btn" onclick="document.getElementById('orderFrame').scrollIntoView({behavior:'smooth'})">Notify / Order Now</button>
          <button class="btn alt" onclick="openSupport()">Contact Support</button>
        </div>
      </div>

      <aside class="card">
        <h3>Popular Packages</h3>
        <div class="price-list" aria-hidden="false">
          <div class="package"><div><div class="name">86 Diamonds</div><div class="small">Starter</div></div><div>$1.99</div></div>
          <div class="package"><div><div class="name">172 Diamonds</div><div class="small">Value</div></div><div>$3.50</div></div>
          <div class="package"><div><div class="name">514 Diamonds</div><div class="small">Best Seller</div></div><div>$9.50</div></div>
        </div>

        <hr style="opacity:.06;margin:12px 0" />
        <p class="small">Note: Prices are sample only. Real prices will reflect supplier (Codashop) rates + margin. API integration will enable instant auto-topup.</p>
      </aside>
    </main>

    <!-- FEATURES -->
    <section class="grid" aria-label="features">
      <div class="feature center">
        <div class="pill">Secure</div>
        <h4 style="margin-top:10px">Trusted Payments</h4>
        <p class="small">SSL + Verified gateways (PayPal/Stripe) — PCI compliance via gateway.</p>
      </div>
      <div class="feature center">
        <div class="pill">Fast</div>
        <h4 style="margin-top:10px">Instant Top-up</h4>
        <p class="small">Order processed automatically after supplier API call (future).</p>
      </div>
      <div class="feature center">
        <div class="pill">Support</div>
        <h4 style="margin-top:10px">24/7 Support</h4>
        <p class="small">Live chat & ticketing for refunds and help.</p>
      </div>
    </section>

    <!-- ORDER / FORM SECTION -->
    <section id="orderFrame" style="margin-top:22px">
      <h3 style="margin-bottom:8px">Place a pre-order / Get Notified</h3>
      <p class="small">Use the form below to request a top-up or to subscribe for launch notifications.</p>

      <!-- EMBED GOOGLE FORM (replace the src with your Google Form "embed" URL) -->
      <div style="margin-top:12px;border-radius:12px;overflow:hidden;border:1px solid rgba(255,255,255,0.03)">
        <iframe
          src="https://docs.google.com/forms/d/e/1FAIpQLSeXAMPLE_FORM_ID/viewform?embedded=true"
          width="100%" height="720" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
      </div>

      <p class="small" style="margin-top:10px">If you prefer, contact us: <a class="link" href="mailto:support@yourbrand.com">support@yourbrand.com</a></p>
    </section>

    <footer>
      © 2025 Global MLBB Top-up. Official Codashop partner application in progress.
    </footer>
  </div>

  <script>
    // small helpers — replace these with your real support flow
    function openSupport(){
      // open contact — can be replaced with WhatsApp/Telegram link
      window.location.href = "mailto:support@yourbrand.com";
    }

    /* FUTURE: when partner API available, replace iframe form with direct order flow:
       1) collect fields (mlbb_id, server, package, payment_token)
       2) POST to your backend (HTTPS) -> backend calls Codashop API with your partner key
       3) backend returns success -> show confirmation to user
       Security: never call supplier API direct from browser (exposes API keys).
    */
  </script>
</body>
</html>
