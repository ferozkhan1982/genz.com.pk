<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>GenZ.com.pk — Premium Domain For Sale</title>
  <meta name="description" content="GenZ.com.pk is a premium Pakistani domain name available for sale. Contact us on WhatsApp to make an offer.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      width: 100%;
      height: 100%;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      overflow: hidden;
      color: #fff;
      background: #050816;
    }

    /* Animated background */
    .background {
      position: fixed;
      inset: 0;
      overflow: hidden;
      background:
        radial-gradient(circle at 20% 20%, rgba(0, 255, 180, 0.15), transparent 30%),
        radial-gradient(circle at 80% 30%, rgba(80, 90, 255, 0.18), transparent 30%),
        radial-gradient(circle at 50% 90%, rgba(255, 0, 150, 0.12), transparent 35%),
        #050816;
      z-index: -3;
    }

    .orb {
      position: absolute;
      border-radius: 50%;
      filter: blur(70px);
      opacity: 0.45;
      animation: float 16s ease-in-out infinite alternate;
    }

    .orb.one {
      width: 350px;
      height: 350px;
      background: #00ffc3;
      left: -100px;
      top: -80px;
    }

    .orb.two {
      width: 400px;
      height: 400px;
      background: #5b5cff;
      right: -130px;
      top: 10%;
      animation-delay: -5s;
    }

    .orb.three {
      width: 300px;
      height: 300px;
      background: #ff1493;
      bottom: -120px;
      left: 35%;
      animation-delay: -9s;
    }

    @keyframes float {
      0% {
        transform: translate(0, 0) scale(1);
      }
      50% {
        transform: translate(70px, 40px) scale(1.12);
      }
      100% {
        transform: translate(-40px, 90px) scale(0.95);
      }
    }

    /* Stars */
    .stars {
      position: absolute;
      inset: 0;
      background-image:
        radial-gradient(circle, rgba(255,255,255,.7) 1px, transparent 1px),
        radial-gradient(circle, rgba(255,255,255,.35) 1px, transparent 1px);
      background-size: 90px 90px, 150px 150px;
      background-position: 0 0, 40px 70px;
      opacity: .18;
      animation: starsMove 30s linear infinite;
    }

    @keyframes starsMove {
      from {
        transform: translateY(0);
      }
      to {
        transform: translateY(-90px);
      }
    }

    /* Main */
    .page {
      width: 100%;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 25px;
      text-align: center;
    }

    .card {
      width: min(900px, 100%);
      padding: 60px 35px;
      border: 1px solid rgba(255,255,255,.15);
      border-radius: 30px;
      background: rgba(10, 14, 35, .65);
      backdrop-filter: blur(20px);
      -webkit-backdrop-filter: blur(20px);
      box-shadow:
        0 30px 100px rgba(0,0,0,.45),
        inset 0 1px 0 rgba(255,255,255,.08);
      animation: cardIn 1.5s ease forwards;
    }

    @keyframes cardIn {
      from {
        opacity: 0;
        transform: translateY(35px) scale(.97);
      }
      to {
        opacity: 1;
        transform: translateY(0) scale(1);
      }
    }

    .badge {
      display: inline-block;
      padding: 9px 18px;
      border-radius: 50px;
      border: 1px solid rgba(0,255,195,.35);
      background: rgba(0,255,195,.08);
      color: #72ffe1;
      font-size: 13px;
      font-weight: bold;
      letter-spacing: 2px;
      text-transform: uppercase;
      margin-bottom: 25px;
    }

    .domain {
      font-size: clamp(48px, 10vw, 110px);
      line-height: .95;
      font-weight: 900;
      letter-spacing: -4px;
      margin-bottom: 25px;

      background: linear-gradient(
        90deg,
        #ffffff,
        #8fffe9,
        #ffffff,
        #a5a7ff,
        #ffffff
      );

      background-size: 300% auto;
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;

      animation: shine 7s linear infinite;
    }

    @keyframes shine {
      0% {
        background-position: 0% center;
      }
      100% {
        background-position: 300% center;
      }
    }

    .headline {
      font-size: clamp(22px, 4vw, 38px);
      font-weight: 700;
      margin-bottom: 15px;
    }

    .description {
      max-width: 650px;
      margin: 0 auto 35px;
      color: rgba(255,255,255,.68);
      font-size: 17px;
      line-height: 1.7;
    }

    .price-box {
      display: inline-flex;
      align-items: center;
      gap: 12px;
      padding: 12px 20px;
      border-radius: 50px;
      background: rgba(255,255,255,.07);
      border: 1px solid rgba(255,255,255,.12);
      margin-bottom: 35px;
      color: rgba(255,255,255,.85);
      font-size: 14px;
    }

    .dot {
      width: 9px;
      height: 9px;
      background: #00ffc3;
      border-radius: 50%;
      box-shadow: 0 0 15px #00ffc3;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0%, 100% {
        opacity: 1;
        transform: scale(1);
      }
      50% {
        opacity: .45;
        transform: scale(.7);
      }
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    .whatsapp-main {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 16px 30px;
      border-radius: 50px;
      background: #25D366;
      color: #fff;
      text-decoration: none;
      font-size: 16px;
      font-weight: 800;
      box-shadow: 0 12px 35px rgba(37,211,102,.28);
      transition: .3s ease;
    }

    .whatsapp-main:hover {
      transform: translateY(-4px);
      box-shadow: 0 18px 45px rgba(37,211,102,.4);
    }

    .whatsapp-icon {
      width: 23px;
      height: 23px;
      fill: currentColor;
    }

    .scroll-text {
      margin-top: 40px;
      font-size: 12px;
      letter-spacing: 2px;
      color: rgba(255,255,255,.35);
      text-transform: uppercase;
      animation: fade 3s ease-in-out infinite;
    }

    @keyframes fade {
      0%, 100% {
        opacity: .35;
      }
      50% {
        opacity: .8;
      }
    }

    /* Floating WhatsApp */
    .floating-whatsapp {
      position: fixed;
      right: 25px;
      bottom: 25px;
      width: 64px;
      height: 64px;
      border-radius: 50%;
      background: #25D366;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      color: white;
      box-shadow:
        0 8px 25px rgba(0,0,0,.35),
        0 0 0 0 rgba(37,211,102,.5);
      z-index: 100;
      animation: whatsappPulse 2.5s infinite;
      transition: .3s ease;
    }

    .floating-whatsapp:hover {
      transform: scale(1.12);
    }

    .floating-whatsapp svg {
      width: 34px;
      height: 34px;
      fill: white;
    }

    @keyframes whatsappPulse {
      0% {
        box-shadow:
          0 8px 25px rgba(0,0,0,.35),
          0 0 0 0 rgba(37,211,102,.55);
      }
      70% {
        box-shadow:
          0 8px 25px rgba(0,0,0,.35),
          0 0 0 18px rgba(37,211,102,0);
      }
      100% {
        box-shadow:
          0 8px 25px rgba(0,0,0,.35),
          0 0 0 0 rgba(37,211,102,0);
      }
    }

    .tooltip {
      position: absolute;
      right: 78px;
      white-space: nowrap;
      background: rgba(0,0,0,.75);
      color: #fff;
      padding: 9px 13px;
      border-radius: 8px;
      font-size: 13px;
      opacity: 0;
      pointer-events: none;
      transform: translateX(10px);
      transition: .3s ease;
    }

    .floating-whatsapp:hover .tooltip {
      opacity: 1;
      transform: translateX(0);
    }

    /* Mobile */
    @media (max-width: 600px) {
      .page {
        padding: 15px;
      }

      .card {
        padding: 45px 20px;
        border-radius: 24px;
      }

      .domain {
        font-size: clamp(42px, 14vw, 75px);
        letter-spacing: -3px;
      }

      .description {
        font-size: 15px;
      }

      .floating-whatsapp {
        width: 58px;
        height: 58px;
        right: 18px;
        bottom: 18px;
      }

      .floating-whatsapp svg {
        width: 30px;
        height: 30px;
      }

      .tooltip {
        display: none;
      }
    }
  </style>
</head>

<body>

  <!-- Animated Background -->
  <div class="background">
    <div class="stars"></div>
    <div class="orb one"></div>
    <div class="orb two"></div>
    <div class="orb three"></div>
  </div>

  <!-- Main Content -->
  <main class="page">

    <section class="card">

      <div class="badge">
        Premium Domain
      </div>

      <h1 class="domain">
        GenZ.com.pk
      </h1>

      <h2 class="headline">
        This Domain Is For Sale
      </h2>

      <p class="description">
        Own a memorable, powerful and brandable .com.pk domain.
        Perfect for an eCommerce business, technology brand,
        youth-focused company, startup or digital platform.
      </p>

      <div class="price-box">
        <span class="dot"></span>
        Available for Purchase
      </div>

      <div class="buttons">

        <a
          class="whatsapp-main"
          href="https://wa.me/923452355608?text=Hello%2C%20I%20am%20interested%20in%20buying%20GenZ.com.pk"
          target="_blank"
          rel="noopener noreferrer"
        >

          <svg class="whatsapp-icon" viewBox="0 0 24 24">
            <path d="M20.52 3.48A11.86 11.86 0 0 0 12.04 0C5.5 0 .18 5.32.18 11.86c0 2.09.55 4.13 1.6 5.93L.08 24l6.36-1.67a11.87 11.87 0 0 0 5.6 1.42h.01c6.54 0 11.86-5.32 11.86-11.86 0-3.17-1.24-6.15-3.39-8.41ZM12.05 21.73h-.01a9.84 9.84 0 0 1-5.02-1.37l-.36-.21-3.77.99 1.01-3.67-.23-.38a9.85 9.85 0 0 1-1.51-5.23c0-5.43 4.42-9.85 9.86-9.85 2.63 0 5.1 1.03 6.96 2.89a9.8 9.8 0 0 1 2.89 6.96c0 5.44-4.42 9.86-9.82 9.86Zm5.41-7.39c-.3-.15-1.77-.87-2.05-.97-.27-.1-.47-.15-.67.15-.2.3-.77.97-.94 1.17-.17.2-.35.22-.65.07-.3-.15-1.27-.47-2.42-1.5-.9-.8-1.5-1.79-1.67-2.09-.17-.3-.02-.46.13-.61.14-.14.3-.35.45-.52.15-.17.2-.3.3-.5.1-.2.05-.37-.02-.52-.07-.15-.67-1.61-.92-2.21-.24-.58-.49-.5-.67-.51h-.57c-.2 0-.52.07-.8.37-.27.3-1.05 1.02-1.05 2.49s1.07 2.89 1.22 3.09c.15.2 2.1 3.21 5.08 4.5.71.31 1.26.49 1.69.63.71.23 1.36.2 1.87.12.57-.08 1.77-.72 2.02-1.42.25-.7.25-1.3.17-1.42-.07-.12-.27-.2-.57-.35Z"/>
          </svg>

          Make an Offer
        </a>

      </div>

      <div class="scroll-text">
        Contact us on WhatsApp to discuss
      </div>

    </section>

  </main>

  <!-- Floating WhatsApp Button -->
  <a
    class="floating-whatsapp"
    href="https://wa.me/923452355608?text=Hello%2C%20I%20am%20interested%20in%20GenZ.com.pk"
    target="_blank"
    rel="noopener noreferrer"
    aria-label="Contact us on WhatsApp"
  >

    <span class="tooltip">
      Chat on WhatsApp
    </span>

    <svg viewBox="0 0 24 24">
      <path d="M20.52 3.48A11.86 11.86 0 0 0 12.04 0C5.5 0 .18 5.32.18 11.86c0 2.09.55 4.13 1.6 5.93L.08 24l6.36-1.67a11.87 11.87 0 0 0 5.6 1.42h.01c6.54 0 11.86-5.32 11.86-11.86 0-3.17-1.24-6.15-3.39-8.41ZM12.05 21.73h-.01a9.84 9.84 0 0 1-5.02-1.37l-.36-.21-3.77.99 1.01-3.67-.23-.38a9.85 9.85 0 0 1-1.51-5.23c0-5.43 4.42-9.85 9.86-9.85 2.63 0 5.1 1.03 6.96 2.89a9.8 9.8 0 0 1 2.89 6.96c0 5.44-4.42 9.86-9.82 9.86Zm5.41-7.39c-.3-.15-1.77-.87-2.05-.97-.27-.1-.47-.15-.67.15-.2.3-.77.97-.94 1.17-.17.2-.35.22-.65.07-.3-.15-1.27-.47-2.42-1.5-.9-.8-1.5-1.79-1.67-2.09-.17-.3-.02-.46.13-.61.14-.14.3-.35.45-.52.15-.17.2-.3.3-.5.1-.2.05-.37-.02-.52-.07-.15-.67-1.61-.92-2.21-.24-.58-.49-.5-.67-.51h-.57c-.2 0-.52.07-.8.37-.27.3-1.05 1.02-1.05 2.49s1.07 2.89 1.22 3.09c.15.2 2.1 3.21 5.08 4.5.71.31 1.26.49 1.69.63.71.23 1.36.2 1.87.12.57-.08 1.77-.72 2.02-1.42.25-.7.25-1.3.17-1.42-.07-.12-.27-.2-.57-.35Z"/>
    </svg>

  </a>

</body>
</html>
