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
      flex: 1 1 30%;
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
    <h1>You Home</h1>
    <p>Administración profesional de propiedades tipo Airbnb en Puerto Rico</p>
  </header>

  <section>
    <h2>Servicios</h2>
    <div class="services">
      <div class="service">
        <h3>Gestión de Reservas</h3>
        <p>Respondemos a tus huéspedes, gestionamos el calendario y maximizamos tu ocupación para asegurar ingresos consistentes.</p>
      </div>
      <div class="service">
        <h3>Limpieza y Mantenimiento</h3>
        <p>Coordinamos limpieza profesional después de cada estadía y atendemos cualquier imprevisto técnico.</p>
      </div>
      <div class="service">
        <h3>Optimización del Perfil</h3>
        <p>Fotografías profesionales, descripciones atractivas y precios estratégicos para destacarte entre la competencia.</p>
      </div>
    </div>
  </section>

  <section> 
    <h2>Contáctanos</h2>
    <form>
      <input type="text" placeholder="Nombre" required>
      <input type="email" placeholder="Correo electrónico" required>
      <textarea rows="5" placeholder="Cuéntanos sobre tu propiedad..." required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 You Home - Administración Airbnb en Puerto Rico. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
