   <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>You Home - Administración Airbnb</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #F8F3ED;
      color: #333333;
    }

    header {
      background-color: #E2725B;
      color: white;
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    header img {
      max-width: 250px;
      margin-bottom: 20px;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .services {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: space-between;
    }

    .service {
      flex: 1 1 45%;
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      border-left: 6px solid #E2725B;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .service h3 {
      margin-top: 0;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 600px;
      margin: auto;
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    input, textarea {
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
    }

    button {
      background-color: #E2725B;
      color: white;
      padding: 14px;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #cf634c;
    }

    .contact-info {
      margin-top: 30px;
      text-align: center;
    }

    #thank-you-message {
      display: none;
      color: green;
      font-weight: bold;
      margin-top: 20px;
      text-align: center;
    }

    footer {
      background-color: #8C4B2F;
      color: white;
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }
  </style>
</head>
<body>

  <header>
    <img src="ChatGPT Image Jul 13, 2025, 07_49_22 AM.png" alt="Logo You Home">
    <h1>You Home</h1>
    <p>Administración profesional de propiedades tipo Airbnb en Puerto Rico</p>
  </header>

  <section>
    <h2>Servicios</h2>
    <div class="services">
      <div class="service">
        <h3>Marketing y Gestión de Reservas</h3>
        <p>Perfiles optimizados en Airbnb, Booking y Vrbo. Precios dinámicos y campañas digitales para maximizar visibilidad y ocupación.</p>
      </div>
      <div class="service">
        <h3>Atención al Cliente 24/7</h3>
        <p>Respuesta rápida en inglés y español. Apoyo continuo ante consultas, emergencias y recomendaciones locales.</p>
      </div>
      <div class="service">
        <h3>Check-in / Check-out y Guías Locales</h3>
        <p>Auto check-in/out y manuales digitales con recomendaciones de playas, restaurantes y actividades.</p>
      </div>
      <div class="service">
        <h3>Limpieza y Mantenimiento</h3>
        <p>Limpieza estandarizada tras cada salida. Cambio de ropa de cama, ambientadores, reposición de insumos y reportes de daños.</p>
      </div>
    </div>
  </section>

  <section id="contacto">
  <h2>Contáctanos</h2>
  <form id="contact-form" action="https://formspree.io/f/mnqekgyr" method="POST">
    <input type="text" name="nombre" placeholder="Nombre" required>
    <input type="email" name="email" placeholder="Correo electrónico" required>
    <textarea name="mensaje" rows="5" placeholder="Cuéntanos sobre tu propiedad..." required></textarea>
    <button type="submit">Enviar</button>
  </form>

  <div id="thank-you-message" style="display: none; margin-top: 20px;">
    ¡Gracias por contactarnos! Te responderemos pronto.
  </div>

  <div class="contact-info" style="margin-top: 20px;">
    <p><strong>Correo electrónico:</strong> <a href="mailto:youhomeinfo.pr@gmail.com">youhomeinfo.pr@gmail.com</a></p>
    <p><strong>Teléfono:</strong> <a href="tel:+19394014259">939-401-4259</a></p>
  </div>
</section>

<footer>
  <p>&copy; 2025 You Home - Administración Airbnb en Puerto Rico. Todos los derechos reservados.</p>
</footer>

<script>
  const form = document.getElementById('contact-form');
  const thankYouMessage = document.getElementById('thank-you-message');

  form.addEventListener('submit', async function (e) {
    e.preventDefault(); // Evita que la página se recargue (puedes quitar esta línea si no usas fetch)
    
    const formData = new FormData(form

