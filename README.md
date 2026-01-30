<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cafeteria Premium</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #0c0b09;
      color: #f5f5f5;
      overflow-x: hidden;
    }

    a {
      text-decoration: none;
    }

    /* HERO */
    .hero {
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,.6), rgba(0,0,0,.6)),
      url('https://images.unsplash.com/photo-1511920170033-f8396924c348') center/cover;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 0 20px;
    }

    .hero h1 {
      font-size: 3.5rem;
      color: #cfa76e;
    }

    .hero p {
      margin: 20px 0;
      font-size: 1.2rem;
      max-width: 600px;
    }

    .btn {
      display: inline-block;
      padding: 14px 36px;
      background: #cfa76e;
      color: #000;
      border-radius: 40px;
      font-weight: 600;
      transition: .3s;
    }

    .btn:hover {
      transform: scale(1.05);
    }

    /* SECTIONS */
    section {
      padding: 80px 10%;
    }

    .title {
      text-align: center;
      font-size: 2.5rem;
      color: #cfa76e;
      margin-bottom: 60px;
    }

    /* EXPERIENCE */
    .experience {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 30px;
    }

    .exp-box {
      background: #151411;
      padding: 35px;
      border-radius: 20px;
      transition: .3s;
    }

    .exp-box:hover {
      transform: translateY(-10px);
    }

    .exp-box h3 {
      margin-bottom: 10px;
      color: #cfa76e;
    }

    /* MENU */
    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 25px;
    }

    .menu-card {
      background: #151411;
      padding: 25px;
      border-radius: 18px;
      text-align: center;
    }

    .menu-card span {
      display: block;
      margin-top: 10px;
      color: #cfa76e;
      font-weight: bold;
    }

    /* CTA */
    .cta {
      background: linear-gradient(135deg, #cfa76e, #8a6b3e);
      color: #000;
      text-align: center;
      padding: 80px 20px;
      border-radius: 30px;
      margin: 0 10%;
    }

    .cta h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    /* FOOTER */
    footer {
      background: #050504;
      text-align: center;
      padding: 25px;
      margin-top: 80px;
      font-size: .9rem;
      color: #aaa;
    }

    /* WHATSAPP */
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      padding: 16px;
      border-radius: 50%;
      font-size: 22px;
      color: #fff;
    }

  </style>
</head>
<body>

  <!-- HERO -->
  <section class="hero">
    <div>
      <h1>Café não é só bebida.</h1>
      <p>É experiência, aroma e momentos inesquecíveis em cada xícara.</p>
      <a href="#menu" class="btn">Conheça Nosso Cardápio</a>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section>
    <h2 class="title">Uma Experiência Única</h2>
    <div class="experience">
      <div class="exp-box">
        <h3>Grãos Selecionados</h3>
        <p>Cafés especiais escolhidos com rigor e qualidade extrema.</p>
      </div>
      <div class="exp-box">
        <h3>Ambiente Sofisticado</h3>
        <p>Design elegante pensado para conforto e inspiração.</p>
      </div>
      <div class="exp-box">
        <h3>Baristas Especialistas</h3>
        <p>Profissionais apaixonados pelo que fazem.</p>
      </div>
    </div>
  </section>

  <!-- MENU -->
  <section id="menu">
    <h2 class="title">Clássicos da Casa</h2>
    <div class="menu">
      <div class="menu-card">
        <h3>Espresso Premium</h3>
        <span>R$ 8,00</span>
      </div>
      <div class="menu-card">
        <h3>Cappuccino Cremoso</h3>
        <span>R$ 14,00</span>
      </div>
      <div class="menu-card">
        <h3>Latte Artesanal</h3>
        <span>R$ 16,00</span>
      </div>
      <div class="menu-card">
        <h3>Mocha Especial</h3>
        <span>R$ 18,00</span>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <div class="cta">
    <h2>Venha viver essa experiência</h2>
    <p>Reserve seu momento. O café perfeito te espera.</p>
    <br>
    <a href="https://wa.me/5500000000000" class="btn">Fazer Reserva</a>
  </div>

  <!-- FOOTER -->
  <footer>
    © 2026 • Cafeteria Premium • Todos os direitos reservados
  </footer>

  <a href="https://wa.me/5500000000000" class="whatsapp">☕</a>

</body>
</html>
