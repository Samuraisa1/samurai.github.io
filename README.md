<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Samurai Links</title>
  <style>
    :root{
      --bg: #000;
      --accent: #ff1a1a;
      --btn-radius: 10px;
      --max-width: 520px;
      font-family: Arial, Helvetica, sans-serif;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      background:var(--bg);
      color:#fff;
      padding:24px;
    }
    .card{
      width:100%;
      max-width:var(--max-width);
      text-align:center;
      padding:28px;
      border-radius:16px;
    }
    .logo{
      width:160px;
      height:160px;
      margin:0 auto 12px;
      border-radius:50%;
      overflow:hidden;
      border:4px solid var(--accent);
      display:flex;
      align-items:center;
      justify-content:center;
      background: #000;
    }
    .logo img{width:100%;height:100%;object-fit:contain;display:block}
    h1{
      margin:12px 0 6px;
      font-size:28px;
      color:var(--accent);
      letter-spacing:0.5px;
    }
    p.lead{margin:0 0 18px;color:#aaa;font-size:14px}
    .links{display:flex;flex-direction:column;gap:14px;align-items:center}
    .btn{
      display:inline-block;
      width:260px;
      max-width:90%;
      padding:14px 18px;
      border-radius:var(--btn-radius);
      text-decoration:none;
      color:#fff;
      background:linear-gradient(180deg, rgba(255,26,26,0.98), rgba(180,10,10,0.98));
      border:1px solid rgba(255,255,255,0.06);
      font-weight:700;
      transition:transform .12s ease, box-shadow .12s ease;
      text-align:center;
      box-shadow: 0 6px 18px rgba(0,0,0,0.6);
    }
    .btn:hover{transform:translateY(-4px);box-shadow:0 14px 40px rgba(255,10,10,0.12)}
    footer{margin-top:20px;color:#777;font-size:13px}
    @media (max-width:420px){
      h1{font-size:22px}
      .logo{width:120px;height:120px}
      .btn{width:220px}
    }
  </style>
</head>
<body>
  <main class="card" role="main">
    <div class="logo" aria-hidden="true">
      <img src="Sam.png" alt="Samurai Logo">
    </div>

    <h1>Samurai</h1>
    <p class="lead">All our links — follow & shop</p>

    <nav class="links" aria-label="Samurai links">
      <a class="btn" href="https://Samurai-Saudi.com" target="_blank" rel="noopener">Website</a>
      <a class="btn" href="https://www.instagram.com/samurai.saudi/?next=%2F" target="_blank" rel="noopener">Instagram</a>
      <a class="btn" href="https://snapchat.com/t/3wKlt27Y" target="_blank" rel="noopener">Snapchat</a>
      <a class="btn" href="https://www.tiktok.com/@samurai.saudi" target="_blank" rel="noopener">TikTok</a>
    </nav>

    <footer>© Samurai</footer>
  </main>
</body>
</html>
