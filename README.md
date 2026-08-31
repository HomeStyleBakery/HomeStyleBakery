<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Home Style Bakery | Eggless • Organic • Homemade</title>

  <meta name="description" content="Home Style Bakery in London, Ontario. Homemade eggless vegetarian cakes, cheesecakes, breads, cookies and more, made with organic ingredients, no preservatives and no artificial colours.">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@500;600&family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
  --cream: #1e1e1e;
  --cream-dark: #151515;
  --sage: #8a8a8a;
  --sage-dark: #6f6f6f;
  --terracotta: #c9a77d;
  --terracotta-dark: #a98a64;
  --brown: #2a2a2a;
  --text: #f5f5f5;
  --muted: #b5b5b5;
  --white: #ffffff;
  --border: #3a3a3a;
  --shadow: 0 18px 50px rgba(0, 0, 0, .35);
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      font-family: "DM Sans", sans-serif;
      background: var(--cream);
      color: var(--text);
      line-height: 1.6;
    }
    img { width: 100%; display: block; }
    a { color: inherit; text-decoration: none; }

    .announcement {
      background: var(--sage-dark);
      color: #fff;
      text-align: center;
      padding: 9px 15px;
      font-size: 13px;
      letter-spacing: .3px;
    }

    nav {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: rgba(251,246,237,.95);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid var(--border);
    }

    .nav-container {
      max-width: 1200px;
      margin: auto;
      padding: 16px 25px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 25px;
    }

    .logo {
      font-family: "Playfair Display", serif;
      color: var(--sage-dark);
      font-size: 24px;
      font-weight: 700;
      line-height: 1;
    }

    .logo span {
      display: block;
      font-family: "Caveat", cursive;
      color: var(--terracotta);
      font-size: 16px;
      margin-top: 4px;
      font-weight: 500;
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 27px;
      list-style: none;
      font-size: 14px;
      font-weight: 600;
    }

    .nav-links a:hover { color: var(--terracotta); }

    .nav-order {
      background: var(--terracotta);
      color: #fff !important;
      padding: 11px 18px;
      border-radius: 30px;
      transition: .25s;
    }

    .nav-order:hover {
      background: var(--terracotta-dark);
      transform: translateY(-2px);
    }

    .hero {
      max-width: 1250px;
      min-height: 690px;
      margin: auto;
      padding: 65px 25px;
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      gap: 55px;
    }

    .hero-content { padding-left: 20px; }

    .eyebrow {
      color: var(--terracotta);
      font-family: "Caveat", cursive;
      font-size: 26px;
      margin-bottom: 10px;
    }

    .hero h1 {
      font-family: "Playfair Display", serif;
      color: var(--brown);
      font-size: clamp(48px, 6vw, 76px);
      line-height: 1.02;
      margin-bottom: 23px;
    }

    .hero h1 em {
      color: var(--sage);
      font-style: normal;
    }

    .hero-description {
      max-width: 560px;
      color: var(--muted);
      font-size: 17px;
      line-height: 1.8;
      margin-bottom: 29px;
    }

    .hero-buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-bottom: 28px;
    }

    .button {
      display: inline-flex;
      justify-content: center;
      align-items: center;
      padding: 14px 24px;
      border-radius: 30px;
      font-weight: 700;
      font-size: 14px;
      transition: .25s;
    }

    .button-primary {
      background: var(--terracotta);
      color: #fff;
      box-shadow: 0 8px 22px rgba(184,102,78,.22);
    }

    .button-primary:hover {
      background: var(--terracotta-dark);
      transform: translateY(-2px);
    }

    .button-secondary {
      border: 1px solid var(--sage);
      color: var(--sage-dark);
    }

    .button-secondary:hover {
      background: var(--sage);
      color: #fff;
    }

    .mini-promise {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .mini-promise span {
      background: #fff;
      border: 1px solid var(--border);
      border-radius: 30px;
      padding: 7px 12px;
      font-size: 12px;
      font-weight: 700;
    }

    .hero-photo {
      position: relative;
      height: 560px;
    }

    .hero-photo img {
      height: 100%;
      object-fit: cover;
      border-radius: 45% 45% 18px 18px;
      box-shadow: var(--shadow);
    }

    .hero-badge {
      position: absolute;
      bottom: 28px;
      left: -25px;
      width: 150px;
      height: 150px;
      border-radius: 50%;
      background: var(--sage);
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
      font-family: "Playfair Display", serif;
      font-size: 16px;
      line-height: 1.35;
      box-shadow: 0 12px 30px rgba(77,89,54,.22);
    }

    .section {
      max-width: 1200px;
      margin: auto;
      padding: 85px 25px;
    }

    .section-heading {
      text-align: center;
      max-width: 700px;
      margin: 0 auto 45px;
    }

    .section-heading .eyebrow { margin-bottom: 2px; }

    .section-heading h2 {
      font-family: "Playfair Display", serif;
      color: var(--brown);
      font-size: clamp(34px, 4vw, 50px);
      line-height: 1.15;
      margin-bottom: 14px;
    }

    .section-heading p { color: var(--muted); }

    /* Product cards */

    .products {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 25px;
    }

    .product-card {
      background: #fff;
      border: 1px solid var(--border);
      border-radius: 22px;
      overflow: hidden;
      box-shadow: 0 8px 25px rgba(74,56,45,.06);
      transition: transform .3s, box-shadow .3s;
    }

    .product-card:hover {
      transform: translateY(-7px);
      box-shadow: var(--shadow);
    }

    .product-image {
      height: 265px;
      overflow: hidden;
      background: var(--cream-dark);
    }

    .product-image img {
      height: 100%;
      object-fit: cover;
      transition: transform .5s;
    }

    .product-card:hover .product-image img { transform: scale(1.05); }

    .product-info { padding: 23px; }

    .tag {
      display: inline-block;
      color: var(--sage-dark);
      background: #edf0e6;
      border-radius: 30px;
      padding: 5px 10px;
      font-size: 10px;
      font-weight: 800;
      letter-spacing: .8px;
      margin-bottom: 10px;
    }

    .product-info h3 {
      font-family: "Playfair Display", serif;
      color: var(--brown);
      font-size: 25px;
      margin-bottom: 7px;
    }

    .product-info p {
      color: var(--muted);
      font-size: 14px;
      margin-bottom: 18px;
    }

    .product-button {
      display: inline-block;
      color: var(--terracotta-dark);
      font-weight: 700;
      font-size: 13px;
    }

    .product-button:hover { text-decoration: underline; }

    /* Promise */

    .promise-section {
      background: var(--sage-dark);
      color: #fff;
    }

    .promise-inner {
      max-width: 1200px;
      margin: auto;
      padding: 85px 25px;
    }

    .promise-inner .section-heading h2 { color: #fff; }
    .promise-inner .section-heading p { color: rgba(255,255,255,.78); }

    .promise-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 20px;
    }

    .promise-card {
      text-align: center;
      padding: 30px 18px;
      border: 1px solid rgba(255,255,255,.17);
      border-radius: 20px;
      background: rgba(255,255,255,.05);
    }

    .promise-icon {
      font-size: 34px;
      margin-bottom: 13px;
    }

    .promise-card h3 {
      font-family: "Playfair Display", serif;
      font-size: 21px;
      margin-bottom: 7px;
    }

    .promise-card p {
      color: rgba(255,255,255,.74);
      font-size: 13px;
    }

    /* Story */

    .story {
      max-width: 1200px;
      margin: auto;
      padding: 90px 25px;
      display: grid;
      grid-template-columns: .9fr 1.1fr;
      gap: 70px;
      align-items: center;
    }

    .story-image {
      height: 520px;
    }

    .story-image img {
      height: 100%;
      object-fit: cover;
      border-radius: 25px;
      box-shadow: var(--shadow);
    }

    .story-copy .eyebrow { margin-bottom: 5px; }

    .story-copy h2 {
      font-family: "Playfair Display", serif;
      color: var(--brown);
      font-size: clamp(36px, 4vw, 52px);
      line-height: 1.12;
      margin-bottom: 20px;
    }

    .story-copy p {
      color: var(--muted);
      margin-bottom: 16px;
    }

    .signature {
      color: var(--terracotta);
      font-family: "Caveat", cursive;
      font-size: 30px;
      margin-top: 22px;
    }

    /* CTA */

    .order-section {
      background: var(--cream-dark);
      padding: 85px 25px;
    }

    .order-box {
      max-width: 950px;
      margin: auto;
      text-align: center;
      background: #fff;
      border: 1px solid var(--border);
      border-radius: 30px;
      padding: 65px 25px;
      box-shadow: var(--shadow);
    }

    .order-box .eyebrow { margin-bottom: 2px; }

    .order-box h2 {
      font-family: "Playfair Display", serif;
      color: var(--brown);
      font-size: clamp(36px, 5vw, 58px);
      margin-bottom: 12px;
    }

    .order-box p {
      color: var(--muted);
      max-width: 620px;
      margin: 0 auto 25px;
    }

    .whatsapp-number {
      display: block;
      color: var(--sage-dark);
      font-weight: 700;
      margin-top: 15px;
    }

    /* Footer */

    footer {
      background: var(--brown);
      color: #fff;
      padding: 45px 25px 25px;
    }

    .footer-inner {
      max-width: 1200px;
      margin: auto;
      display: grid;
      grid-template-columns: 1.5fr 1fr 1fr;
      gap: 40px;
      padding-bottom: 35px;
    }

    footer h3 {
      font-family: "Playfair Display", serif;
      font-size: 23px;
      margin-bottom: 10px;
    }

    footer p, footer a {
      color: rgba(255,255,255,.7);
      font-size: 13px;
    }

    footer a:hover { color: #fff; }

    .footer-links {
      display: flex;
      flex-direction: column;
      gap: 7px;
    }

    .copyright {
      max-width: 1200px;
      margin: auto;
      padding-top: 20px;
      border-top: 1px solid rgba(255,255,255,.15);
      text-align: center;
      color: rgba(255,255,255,.55);
      font-size: 12px;
    }

    /* Mobile */

    @media (max-width: 900px) {
      .nav-links { gap: 13px; }
      .hero { grid-template-columns: 1fr; padding-top: 45px; }
      .hero-content { padding-left: 0; }
      .hero-photo { height: 500px; }
      .products { grid-template-columns: repeat(2, 1fr); }
      .promise-grid { grid-template-columns: repeat(2, 1fr); }
      .story { grid-template-columns: 1fr; gap: 40px; }
      .story-image { height: 430px; }
      .footer-inner { grid-template-columns: 1fr 1fr; }
    }

    @media (max-width: 650px) {
      .announcement { font-size: 11px; }

      .nav-container {
        padding: 14px 18px;
      }

      .logo { font-size: 20px; }

      .nav-links li:not(:last-child) { display: none; }

      .nav-links { margin-left: auto; }

      .nav-order {
        padding: 9px 14px;
        font-size: 12px;
      }

      .hero {
        padding: 40px 18px 65px;
        min-height: auto;
      }

      .hero h1 { font-size: 47px; }

      .hero-description { font-size: 15px; }

      .hero-photo {
        height: 390px;
      }

      .hero-badge {
        width: 115px;
        height: 115px;
        left: -5px;
        bottom: 15px;
        font-size: 13px;
      }

      .section {
        padding: 65px 18px;
      }

      .products {
        grid-template-columns: 1fr;
      }

      .product-image { height: 280px; }

      .promise-inner { padding: 65px 18px; }

      .promise-grid {
        grid-template-columns: 1fr 1fr;
        gap: 12px;
      }

      .promise-card { padding: 23px 10px; }

      .story {
        padding: 65px 18px;
      }

      .story-image { height: 360px; }

      .order-section { padding: 60px 18px; }

      .order-box {
        padding: 45px 18px;
      }

      .footer-inner {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

  <!-- TOP MESSAGE -->
  <div class="announcement">
    🌿 Eggless • Vegetarian • Organic Ingredients • No Preservatives • No Artificial Colours
  </div>

  <!-- NAVIGATION -->
  <nav>
    <div class="nav-container">

      <a href="#home" class="logo">
        Home Style Bakery
        <span>Homemade with heart</span>
      </a>

      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Our Bakery</a></li>
        <li><a href="#promise">Why Us</a></li>
        <li><a href="#story">Our Story</a></li>
        <li>
          <a
            href="https://wa.me/14379967968?text=Hi%20Home%20Style%20Bakery!%20I%20would%20like%20to%20place%20an%20order."
            target="_blank"
            rel="noopener"
            class="nav-order"
          >
            Order Now
          </a>
        </li>
      </ul>

    </div>
  </nav>

  <!-- HERO -->
  <main id="home">

    <section class="hero">

      <div class="hero-content">

        <div class="eyebrow">Fresh from our kitchen ✦</div>

        <h1>
          Baked with love.<br>
          Made with <em>goodness.</em>
        </h1>

        <p class="hero-description">
          Delicious homemade treats made with carefully selected organic
          ingredients. Completely eggless and vegetarian, with no preservatives
          and no artificial colours.
        </p>

        <div class="hero-buttons">
          <a
            href="https://wa.me/14379967968?text=Hi%20Home%20Style%20Bakery!%20I%20would%20like%20to%20place%20an%20order."
            target="_blank"
            rel="noopener"
            class="button button-primary"
          >
            Order on WhatsApp →
          </a>

          <a href="#products" class="button button-secondary">
            Explore Our Bakery
          </a>
        </div>

        <div class="mini-promise">
          <span>🌱 Organic</span>
          <span>🥚 Eggless</span>
          <span>🌿 Vegetarian</span>
          <span>🚫 No Preservatives</span>
        </div>

      </div>

      <!-- HERO IMAGE SLOT -->
      <div class="hero-photo">
        <img
          src="images/hero-cake.jpg"
          alt="Beautiful homemade cake from Home Style Bakery"
          onerror="this.src='https://placehold.co/900x1100/f1e7d7/66734a?text=Add+hero-cake.jpg+here'"
        >

        <div class="hero-badge">
          Made fresh<br>
          with care<br>
          in London, ON
        </div>
      </div>

    </section>

    <!-- PRODUCTS -->
    <section class="section" id="products">

      <div class="section-heading">
        <div class="eyebrow">Something delicious awaits</div>
        <h2>Fresh From Our Kitchen</h2>
        <p>
          From celebration cakes to fresh bread, everything is prepared with
          care and the ingredients we believe belong in good food.
        </p>
      </div>

      <div class="products">

        <!-- LEMON CAKE -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/lemon-cake.jpg"
              alt="Eggless homemade lemon cake"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Lemon+Cake'"
            >
          </div>
          <div class="product-info">
            <span class="tag">EGGLESS</span>
            <h3>Lemon Cake</h3>
            <p>Light, fresh and full of natural lemon flavour. Homemade and made with care.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20a%20Lemon%20Cake.">
              Order this →
            </a>
          </div>
        </article>

        <!-- BANANA CAKE -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/banana-cake.jpg"
              alt="Homemade eggless banana cake"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Banana+Cake'"
            >
          </div>
          <div class="product-info">
            <span class="tag">HOMEMADE</span>
            <h3>Banana Cake</h3>
            <p>Moist, comforting and naturally delicious — a classic homemade favourite.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20a%20Banana%20Cake.">
              Order this →
            </a>
          </div>
        </article>

        <!-- PECAN CAKE -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/pecan-cake.jpg"
              alt="Homemade pecan cake"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Pecan+Cake'"
            >
          </div>
          <div class="product-info">
            <span class="tag">PREMIUM</span>
            <h3>Pecan Cake</h3>
            <p>Rich homemade cake finished with the delicious flavour and texture of pecans.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20a%20Pecan%20Cake.">
              Order this →
            </a>
          </div>
        </article>

        <!-- WALNUT CAKE -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/walnut-cake.jpg"
              alt="Homemade walnut cake"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Walnut+Cake'"
            >
          </div>
          <div class="product-info">
            <span class="tag">FAVOURITE</span>
            <h3>Walnut Cake</h3>
            <p>A deliciously nutty homemade cake with generous pieces of walnut throughout.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20a%20Walnut%20Cake.">
              Order this →
            </a>
          </div>
        </article>

        <!-- STRAWBERRY CHEESECAKE -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/strawberry-cheesecake.jpg"
              alt="Fresh strawberry cheesecake"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Strawberry+Cheesecake'"
            >
          </div>
          <div class="product-info">
            <span class="tag">FRESH</span>
            <h3>Strawberry Cheesecake</h3>
            <p>Creamy, rich and topped with the bright flavour of strawberries.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20a%20Strawberry%20Cheesecake.">
              Order this →
            </a>
          </div>
        </article>

        <!-- CHEESECAKE -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/cheesecake.jpg"
              alt="Fresh homemade cheesecake"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Cheesecake'"
            >
          </div>
          <div class="product-info">
            <span class="tag">MADE FRESH</span>
            <h3>Classic Cheesecake</h3>
            <p>Rich, creamy and made fresh to order for a simple, delicious dessert.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20a%20Cheesecake.">
              Order this →
            </a>
          </div>
        </article>

        <!-- COOKIES -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/cookies.jpg"
              alt="Homemade natural ingredient cookies"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Cookies'"
            >
          </div>
          <div class="product-info">
            <span class="tag">BAKED FRESH</span>
            <h3>Homemade Cookies</h3>
            <p>Simple, comforting cookies made with quality ingredients and homemade goodness.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20Cookies.">
              Order this →
            </a>
          </div>
        </article>

        <!-- FOCACCIA -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/focaccia.jpg"
              alt="Fresh homemade focaccia bread"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Focaccia'"
            >
          </div>
          <div class="product-info">
            <span class="tag">FRESH BAKED</span>
            <h3>Focaccia Bread</h3>
            <p>Freshly baked focaccia with a soft centre and deliciously golden crust.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20Focaccia%20Bread.">
              Order this →
            </a>
          </div>
        </article>

        <!-- BREAD -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/bread.jpg"
              alt="Fresh homemade bread"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Fresh+Bread'"
            >
          </div>
          <div class="product-info">
            <span class="tag">HOMEMADE</span>
            <h3>Fresh Bread</h3>
            <p>Soft, fresh and made with the simple goodness of homemade bread.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20Fresh%20Bread.">
              Order this →
            </a>
          </div>
        </article>

        <!-- CUSTARD -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/custard.jpg"
              alt="Homemade custard dessert"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=Custard'"
            >
          </div>
          <div class="product-info">
            <span class="tag">HOMEMADE</span>
            <h3>Homemade Custard</h3>
            <p>Silky, comforting custard prepared with care for a delicious homemade treat.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20Custard.">
              Order this →
            </a>
          </div>
        </article>

        <!-- GHEE -->
        <article class="product-card">
          <div class="product-image">
            <img
              src="images/ghee.jpg"
              alt="A2 Desi Ghee"
              onerror="this.src='https://placehold.co/800x600/f1e7d7/66734a?text=A2+Desi+Ghee'"
            >
          </div>
          <div class="product-info">
            <span class="tag">TRADITIONAL</span>
            <h3>A2 Desi Ghee</h3>
            <p>Traditionally prepared ghee made with care and a focus on simple ingredients.</p>
            <a class="product-button" target="_blank" rel="noopener"
              href="https://wa.me/14379967968?text=Hi!%20I%27d%20like%20to%20order%20A2%20Desi%20Ghee.">
              Order this →
            </a>
          </div>
        </article>

      </div>
    </section>

    <!-- BRAND PROMISE -->
    <section class="promise-section" id="promise">

      <div class="promise-inner">

        <div class="section-heading">
          <div class="eyebrow">The Home Style difference</div>
          <h2>Good food starts with good ingredients.</h2>
          <p>
            We believe homemade food should be simple, honest and made with
            ingredients you can feel good about.
          </p>
        </div>

        <div class="promise-grid">

          <div class="promise-card">
            <div class="promise-icon">🌿</div>
            <h3>Organic Ingredients</h3>
            <p>We choose organic ingredients wherever possible to keep our recipes simple and wholesome.</p>
          </div>

          <div class="promise-card">
            <div class="promise-icon">🥚</div>
            <h3>100% Eggless</h3>
            <p>Every item is made without eggs, so everyone can enjoy our homemade treats.</p>
          </div>

          <div class="promise-card">
            <div class="promise-icon">🎨</div>
            <h3>No Artificial Colours</h3>
            <p>We avoid artificial colours and let our food look naturally delicious.</p>
          </div>

          <div class="promise-card">
            <div class="promise-icon">🚫</div>
            <h3>No Preservatives</h3>
            <p>Our focus is fresh, homemade food without unnecessary preservatives.</p>
          </div>

        </div>
      </div>
    </section>

    <!-- STORY -->
    <section class="story" id="story">

      <div class="story-image">
        <img
          src="images/our-kitchen.jpg"
          alt="Home Style Bakery kitchen"
          onerror="this.src='https://placehold.co/900x1100/f1e7d7/66734a?text=Our+Kitchen'"
        >
      </div>

      <div class="story-copy">

        <div class="eyebrow">A little taste of home</div>

        <h2>Made the way homemade food should be.</h2>

        <p>
          At Home Style Bakery, we believe the best food doesn't need to be
          complicated. It starts with good ingredients, traditional care and
          the patience to make things properly.
        </p>

        <p>
          From cakes and cheesecakes to fresh breads, focaccia, cookies and
          custards, every order is prepared with the same care we'd put into
          food for our own family.
        </p>

        <p>
          Proudly serving the London, Ontario community with homemade,
          eggless and vegetarian goodness.
        </p>

        <div class="signature">Made with love ♡</div>

      </div>

    </section>

    <!-- ORDER CTA -->
    <section class="order-section">

      <div class="order-box">

        <div class="eyebrow">Ready for something delicious?</div>

        <h2>Let's make your next treat.</h2>

        <p>
          Tell us what you're looking for and we'll be happy to help with your
          order. Cakes, cheesecakes, breads, cookies and more — made fresh with care.
        </p>

        <a
          href="https://wa.me/14379967968?text=Hi%20Home%20Style%20Bakery!%20I%20would%20like%20to%20place%20an%20order."
          target="_blank"
          rel="noopener"
          class="button button-primary"
        >
          Order on WhatsApp →
        </a>

        <span class="whatsapp-number">
          WhatsApp: +1 437-996-7968
        </span>

        <p style="margin-top:12px; font-size:13px;">
          📍 London, Ontario, Canada
        </p>

      </div>

    </section>

  </main>

  <!-- FOOTER -->
  <footer>

    <div class="footer-inner">

      <div>
        <h3>Home Style Bakery</h3>
        <p>
          Homemade goodness made with organic ingredients,
          without eggs, preservatives or artificial colours.
        </p>
      </div>

      <div>
        <h3>Explore</h3>
        <div class="footer-links">
          <a href="#home">Home</a>
          <a href="#products">Our Bakery</a>
          <a href="#promise">Why Us</a>
          <a href="#story">Our Story</a>
        </div>
      </div>

      <div>
        <h3>Order</h3>
        <div class="footer-links">
          <a
            href="https://wa.me/14379967968?text=Hi%20Home%20Style%20Bakery!%20I%20would%20like%20to%20place%20an%20order."
            target="_blank"
            rel="noopener"
          >
            WhatsApp Us
          </a>
          <a href="tel:+14379967968">+1 437-996-7968</a>
          <a href="#products">View Products</a>
        </div>
      </div>

    </div>

    <div class="copyright">
      © 2026 Home Style Bakery · London, Ontario · Made with love ♡
    </div>

  </footer>

</body>
</html>
