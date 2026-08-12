<!-- DOMAIN FOR SALE POPUP -->
<div id="salePopup" class="sale-popup">

  <div class="sale-box">

    <button class="close-sale" onclick="closeSalePopup()">×</button>

    <div class="sale-icon">🌐</div>

    <div class="sale-label">DOMAIN FOR SALE</div>

    <h2>GenZ.com.pk</h2>

    <p class="sale-heading">
      This premium domain is available for sale.
    </p>

    <p class="sale-text">
      Own a short, memorable and brandable <strong>.com.pk</strong>
      domain for your business, brand or online project.
    </p>

    <div class="sale-features">
      <span>✓ Premium Name</span>
      <span>✓ Easy to Remember</span>
      <span>✓ Pakistan Domain</span>
    </div>

    <a
      class="offer-button"
      href="https://wa.me/923452355608?text=Hello%2C%20I%20am%20interested%20in%20buying%20GenZ.com.pk.%20I%20would%20like%20to%20make%20an%20offer."
      target="_blank">
      💬 Make an Offer
    </a>

    <p class="contact-sale">
      Serious buyers can contact us on WhatsApp
    </p>

  </div>

</div>

<style>

  /* DOMAIN SALE POPUP */

  .sale-popup {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.78);
    backdrop-filter: blur(7px);
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 999999;
    padding: 20px;
    animation: popupFade .4s ease;
  }

  .sale-box {
    width: 100%;
    max-width: 500px;
    background: white;
    border-radius: 25px;
    padding: 45px 30px 35px;
    text-align: center;
    position: relative;
    box-shadow: 0 25px 80px rgba(0,0,0,.35);
    animation: popupScale .4s ease;
  }

  .close-sale {
    position: absolute;
    right: 15px;
    top: 12px;
    border: none;
    background: #f1f3f5;
    color: #333;
    width: 38px;
    height: 38px;
    border-radius: 50%;
    font-size: 27px;
    cursor: pointer;
    line-height: 35px;
  }

  .close-sale:hover {
    background: #ddd;
  }

  .sale-icon {
    font-size: 48px;
    margin-bottom: 8px;
  }

  .sale-label {
    display: inline-block;
    background: #087f5b;
    color: white;
    padding: 7px 16px;
    border-radius: 30px;
    font-size: 12px;
    font-weight: bold;
    letter-spacing: 1.5px;
    margin-bottom: 15px;
  }

  .sale-box h2 {
    font-size: 42px;
    margin: 5px 0 12px;
    color: #111827;
    letter-spacing: -1px;
  }

  .sale-heading {
    font-size: 20px;
    font-weight: 700;
    color: #087f5b;
    margin-bottom: 12px;
  }

  .sale-text {
    color: #667085;
    font-size: 15px;
    line-height: 1.6;
    margin-bottom: 20px;
  }

  .sale-features {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 8px;
    margin-bottom: 25px;
  }

  .sale-features span {
    background: #f1f8f5;
    color: #087f5b;
    padding: 7px 10px;
    border-radius: 20px;
    font-size: 12px;
    font-weight: bold;
  }

  .offer-button {
    display: block;
    width: 100%;
    background: #25d366;
    color: white;
    padding: 16px 25px;
    border-radius: 50px;
    font-size: 18px;
    font-weight: bold;
    box-shadow: 0 8px 25px rgba(37,211,102,.3);
    transition: .3s;
  }

  .offer-button:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 30px rgba(37,211,102,.4);
  }

  .contact-sale {
    font-size: 12px;
    color: #98a2b3;
    margin-top: 15px;
  }

  @keyframes popupFade {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

  @keyframes popupScale {
    from {
      transform: scale(.85);
      opacity: 0;
    }
    to {
      transform: scale(1);
      opacity: 1;
    }
  }

  @media(max-width:600px) {

    .sale-box {
      padding: 40px 22px 28px;
      border-radius: 20px;
    }

    .sale-box h2 {
      font-size: 32px;
    }

    .sale-heading {
      font-size: 17px;
    }

    .sale-text {
      font-size: 14px;
    }

  }

</style>

<script>

  function closeSalePopup() {
    document.getElementById("salePopup").style.display = "none";
  }

</script>
