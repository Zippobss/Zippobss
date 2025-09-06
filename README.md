<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Zippobss | Social Media</title>

  <meta name="description" content="Zippobss - moje social media: TikTok, YouTube, Instagram, Discord. Sprawdź i dołącz do mojej społeczności!" />

  <link rel="icon" href="https://upload.wikimedia.org/wikipedia/en/a/a9/TikTok_logo.svg" type="image/svg+xml" />

  <style>
    /* Reset i podstawy */
    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #1a1a2e, #16213e);
      color: #e0e0e0;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      padding: 60px 20px 40px;
      position: relative;
    }

    a {
      color: inherit;
      text-decoration: none;
      display: flex;
      align-items: center;
      width: 320px;
      max-width: 90vw;
      background: rgba(255 255 255 / 0.1);
      border-radius: 12px;
      padding: 15px 25px;
      box-shadow: 0 6px 12px rgba(0,0,0,0.25);
      cursor: pointer;
      margin: 12px 0;
      transition: background 0.3s, transform 0.2s;
      user-select: none;
    }

    a:hover {
      color: #f39c12;
      background: rgba(255 255 255 / 0.25);
      transform: translateY(-4px);
    }

    a img {
      width: 40px;
      height: 40px;
      margin-right: 18px;
      object-fit: contain;
      border-radius: 6px;
      flex-shrink: 0;
      background: transparent;
      transition: transform 0.3s ease, filter 0.3s ease;
    }

    a:hover img {
      animation: pulse 1s infinite;
    }

    @keyframes pulse {
      0%, 100% {
        transform: scale(1);
        filter: drop-shadow(0 0 0px #f39c12);
      }
      50% {
        transform: scale(1.1);
        filter: drop-shadow(0 0 8px #f39c12);
      }
    }

    span {
      font-size: 1.2rem;
      font-weight: 600;
      color: inherit;
      display: flex;
      flex-direction: column;
      justify-content: center;
      text-align: left;
    }

    small {
      font-weight: 400;
      font-size: 0.8rem;
      color: #ddd;
      margin-top: 2px;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 6px;
      color: #f39c12;
      text-shadow: 1px 1px 5px rgba(243,156,18,0.6);
      user-select: none;
      text-align: center;
    }

    h2 {
      font-size: 2rem;
      margin-top: 50px;
      color: #f39c12;
      text-shadow: 1px 1px 5px rgba(243,156,18,0.6);
      user-select: none;
    }

    p {
      font-size: 1.2rem;
      margin-bottom: 30px;
      color: #cfcfcf;
      user-select: none;
      text-align: center;
    }

    /* Sekcja współpracujących */
    .partners {
      width: 90vw;
      max-width: 600px;
      text-align: center;
      color: #f39c12;
      margin-top: 40px;
    }

    .partners-list {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 20px;
    }

    .partner {
      color: inherit;
      text-decoration: none;
      width: 100px;
      display: flex;
      flex-direction: column;
      align-items: center;
      user-select: none;
    }

    .partner img {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      box-shadow: 0 0 10px #f39c12;
      margin-bottom: 8px;
      object-fit: cover;
      background: #222;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .partner:hover img {
      transform: scale(1.1);
      box-shadow: 0 0 15px #f39c12;
    }

    .partner p {
      margin: 0;
      font-weight: 600;
      font-size: 1rem;
    }

    footer {
      margin-top: 40px;
      font-size: 0.9rem;
      color: #999;
      user-select: none;
      text-align: center;
    }

    @media (max-width: 400px) {
      h1 {
        font-size: 2.4rem;
      }
      a {
        width: 90vw;
      }
      .partner {
        width: 80px;
      }
      .partner img {
        width: 50px;
        height: 50px;
      }
    }
  </style>
</head>
<body>
  <h1>Zippobss</h1>

  <p>Sprawdź moje social media:</p>

  <a href="https://www.tiktok.com/@zippobss" target="_blank" rel="noopener noreferrer" aria-label="TikTok">
    <img src="https://upload.wikimedia.org/wikipedia/en/a/a9/TikTok_logo.svg" alt="TikTok logo" />
    <span>TikTok</span>
  </a>

  <a href="https://www.youtube.com/@zippobss" target="_blank" rel="noopener noreferrer" aria-label="YouTube">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube logo" />
    <span>YouTube</span>
  </a>

  <a href="https://www.instagram.com/zippobs42/" target="_blank" rel="noopener noreferrer" aria-label="Instagram">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/1200px-Instagram_logo_2016.svg.png" alt="Instagram logo" />
    <span>Instagram <small>(konto prywatne)</small></span>
  </a>

  <a href="https://dc.gg/starcraft" target="_blank" rel="noopener noreferrer" aria-label="Discord Server" style="align-items:center;">
    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111370.png" alt="Discord logo" />
    <span>
      Discord <small>(OBECNIE TRWA REKRUTACJA DO ADMINISTRACJI MINECRAFT I DISCORD!)</small><br />
      Nick: <small>zippo_bs</small>
    </span>
  </a>

  <a href="https://dc.gg/zippocommunity" target="_blank" rel="noopener noreferrer" aria-label="Community dla programistów - Discord">
  <img src="https://cdn-icons-png.flaticon.com/512/2111/2111370.png" alt="Discord logo" />
  <span>Community dla programistów <small>(+🔥Zippobss Community🔥)</small></span>
</a>

  <section class="partners">
    <h2>Strony naszych partnerów 🤝</h2>
    <div class="partners-list">
      <a href="https://dc.gg/zippocommunity" target="_blank" rel="noopener noreferrer" class="partner" aria-label="🔥Zippobss Community🔥">
        <img src="https://i.postimg.cc/YjGWdGFM/zippocommunity.png" alt="🔥Zippobss Community🔥" />
        <p>🔥Zippobss Community🔥<small>(Community dla programistów)</small></p>
      </a>
      <a href="https://dc.gg/" target="_blank" rel="noopener noreferrer" class="partner" aria-label="Partner 2">
        <img src="https://via.placeholder.com/60" alt="Partner 2" />
        <p>Partner 2</p>
      </a>
      <h6 style="color:#f39c12; margin-top: 16px; user-select:none; font-weight:600;">
        Aby zawrzeć wyższego lvl partnerstwo i być na powyższej liście pisz na dc: zippo_bs<br>
        (NIE ZAWIERAMY WSPÓŁPRAC Z OSOBAMI, KTÓRE NIE SĄ NA NASZYM SERWERZE DISCORD!)
      </h6>
    </div>
  </section>

  <footer>
    &copy; 2025 Zippobss. Wszystkie prawa zastrzeżone.
  </footer>
</body>
</html>
