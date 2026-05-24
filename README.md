# sevenking.github.io
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Barbería Seven King - Talca</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      background-color: #000000; /* FONDO TOTALMENTE NEGRO */
      color: #ffffff;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #1a1a1a 0%, #000000 100%);
      color: white;
      padding: 30px 20px;
      text-align: center;
      border-bottom: 4px solid #d4af37;
    }

    .logo {
      max-width: 250px;
      margin: 0 auto 15px;
    }

    .logo img {
      width: 100%;
      height: auto;
    }

    header h1 {
      margin: 0;
      font-size: 36px;
      color: #d4af37;
      letter-spacing: 1px;
    }

    header p {
      margin-top: 8px;
      font-size: 16px;
      color: #cccccc;
    }

    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 0 20px;
    }

    .section-title {
      color: #d4af37;
      font-size: 24px;
      margin-bottom: 20px;
      border-bottom: 2px solid #d4af37;
      padding-bottom: 5px;
      text-align: center;
    }

    .card {
      background: #121212;
      border-radius: 12px;
      padding: 30px;
      margin-bottom: 30px;
      box-shadow: 0 4px 12px rgba(212, 175, 55, 0.1);
      border: 2px solid #d4af37;
    }

    .price-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .price-item {
      background: #1e1e1e;
      border: 2px solid #d4af37;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
    }

    .price-item h3 {
      margin: 0 0 10px;
      color: #ffffff;
      font-size: 18px;
      font-weight: bold;
    }

    .price {
      font-size: 26px;
      font-weight: bold;
      color: #d4af37;
    }

    .info-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
    }

    .info-box {
      background: #1e1e1e;
      border: 2px solid #d4af37;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
    }

    .info-box h3 {
      color: #d4af37;
      margin-bottom: 15px;
      font-size: 20px;
    }

    .info-box p {
      font-size: 17px;
      margin: 8px 0;
      color: #ffffff;
    }

    .info-box a {
      color: #d4af37;
      font-weight: bold;
      text-decoration: none;
    }

    .info-box a:hover {
      text-decoration: underline;
    }

    .btn-wsp {
      display: block;
      margin: 12px auto;
      background-color: #25d366;
      color: #ffffff !important;
      padding: 12px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      font-size: 16px;
      transition: background 0.3s ease;
      max-width: 220px;
    }

    .btn-wsp:hover {
      background-color: #128c7e;
      text-decoration: none !important;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #000000;
      color: #d4af37;
      border-top: 3px solid #d4af37;
      margin-top: 20px;
    }

    @media (max-width: 700px) {
      .info-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <img src="logo-sevenking.jpeg" alt="Barbería Seven King - Talca">
    </div>
    <h1>BARBERÍA SEVEN KING</h1>
    <p>El estilo real para tu cabello y barba | Talca, Maule</p>
  </header>

  <div class="container">

    <div class="card">
      <h2 class="section-title">💈 Nuestros Servicios y Precios</h2>
      <div class="price-list">
        <!-- SERVICIOS QUE TENÍAS ANTES -->
        <div class="price-item">
          <h3>Corte Clásico</h3>
          <div class="price">$10.000</div>
        </div>
        <div class="price-item">
          <h3>Perfilado de Barba</h3>
          <div class="price">$5.000</div>
        </div>
        <div class="price-item">
          <h3>Perfilado de Cejas</h3>
          <div class="price">$3.000</div>
        </div>
        <div class="price-item">
          <h3>Corte + Barba</h3>
          <div class="price">$13.000</div>
        </div>
        <div class="price-item">
          <h3>Corte + Diseño</h3>
          <div class="price">$15.000</div>
        </div>

        <!-- NUEVOS SERVICIOS AGREGADOS -->
        <div class="price-item">
          <h3>Tinte de Pelo</h3>
          <div class="price">$18.000</div>
        </div>
        <div class="price-item">
          <h3>Visos</h3>
          <div class="price">$20.000</div>
        </div>
        <div class="price-item">
          <h3>Mechas Platinadas</h3>
          <div class="price">$25.000</div>
        </div>
      </div>
    </div>

    <div class="info-grid">
      <div class="info-box">
        <h3>⏰ Horario de Atención</h3>
        <p>Lunes a Sábado: <strong>10:00 AM - 8:00 PM</strong></p>
        <p>Domingos: Cerrado</p>

        <h3 style="margin-top:20px;">📍 Ubicación</h3>
        <p>Trece Ote. 940<br>3460352 Talca, Maule</p>
      </div>

      <div class="info-box">
        <h3>📲 Reserva tu hora</h3>
        
        <p><strong>WhatsApp 1:</strong> +56 9 1234 5678</p>
        <a class="btn-wsp" href="https://wa.me/56912345678" target="_blank">Escribir al 1</a>

        <p style="margin-top:10px;"><strong>WhatsApp 2:</strong> +56 9 8765 4321</p>
        <a class="btn-wsp" href="https://wa.me/56987654321" target="_blank">Escribir al 2</a>

        <p style="margin-top:15px;">📸 Instagram: <a href="https://instagram.com/barbería_sevenking_" target="_blank">@barbería_sevenking_</a></p>
      </div>
    </div>

  </div>

  <footer>
    <p>© 2026 Barbería Seven King - Talca | Todos los derechos reservados</p>
  </footer>

</body>
</html>
