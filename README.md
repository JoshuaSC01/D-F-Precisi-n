<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>D&F Diseño y Fabricación</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
      background: #f4f4f4;
      color: #111;
    }

    header {
      background: linear-gradient(rgba(0, 0, 30, 0.7), rgba(0, 0, 30, 0.7)),
        url('https://images.unsplash.com/photo-1602526217033-e57b94e1ab04?auto=format&fit=crop&w=1500&q=80');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 80px 20px;
      text-align: center;
    }

    header img {
      width: 120px;
      margin-bottom: 15px;
    }

    header h1 {
      font-size: 42px;
      margin: 10px 0;
    }

    header p {
      font-size: 20px;
      font-weight: 300;
    }

    nav {
      background-color: #001f3f;
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
      padding: 15px 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 16px;
    }

    .section {
      max-width: 1000px;
      margin: 30px auto;
      background: white;
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .service-box {
      background: #e6ecf1;
      padding: 20px;
      text-align: center;
      border-radius: 10px;
    }

    .gallery-button a {
      display: inline-block;
      background-color: #001f3f;
      color: white;
      padding: 12px 25px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 20px;
    }

    .contact input,
    .contact textarea {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 15px;
    }

    .contact button {
      background-color: #28a745;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    footer {
      background-color: #001f3f;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    footer a {
      color: #28a745;
      margin: 0 10px;
      text-decoration: none;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 28px;
      }
      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://maquinadosdf.github.io/DF-Presicion/logoDF.png" alt="Logo D&F" />
    <h1>D&F Diseño y Fabricación</h1>
    <p>Fabricamos ideas, no solo piezas</p>
  </header>

  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#servicios">Servicios</a>
    <a href="#galeria">Galería</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio" class="section">
    <h2>Bienvenido</h2>
    <p>Ofrecemos soluciones en maquinado de precisión, corte láser, diseño mecánico e impresión 3D para industrias que buscan calidad, compromiso y flexibilidad.</p>
  </section>

  <section id="nosotros" class="section">
    <h2>Sobre Nosotros</h2>
    <p>Nos adaptamos a cualquier diseño y fabricación de piezas, metales, polímeros y otros materiales. Contamos con la maquinaria necesaria para cumplir tus objetivos con precisión y puntualidad.</p>
  </section>

  <section id="servicios" class="section">
    <h2><i class="fas fa-cogs"></i> Nuestros Servicios</h2>
    <div class="services">
      <div class="service-box">
        <h3>Torno y Fresado</h3>
        <p>Maquinado convencional y de alta precisión.</p>
      </div>
      <div class="service-box">
        <h3>CNC</h3>
        <p>Producción eficiente y repetible de piezas complejas.</p>
      </div>
      <div class="service-box">
        <h3>Corte Láser</h3>
        <p>Corte de materiales metálicos con alta calidad de acabado.</p>
      </div>
      <div class="service-box">
        <h3>Diseño Mecánico</h3>
        <p>Modelado, simulación y desarrollo de soluciones técnicas.</p>
      </div>
    </div>
  </section>

  <section id="galeria" class="section">
    <h2>Galería de Trabajos</h2>
    <p>Conoce nuestros proyectos, piezas y resultados en redes sociales o en nuestra galería en línea.</p>
    <div class="gallery-button">
      <a href="https://maquinadosdf.github.io/DF-Presicion/" target="_blank">Visitar la Galería</a>
    </div>
  </section>

  <section id="contacto" class="section">
    <h2><i class="fas fa-envelope"></i> Contacto</h2>
    <div class="contact">
      <input type="text" placeholder="Nombre" />
      <input type="email" placeholder="Correo electrónico" />
      <textarea rows="4" placeholder="Mensaje"></textarea>
      <button>Enviar</button>
    </div>
    <p style="text-align:center; margin-top: 20px;">
      <strong>Correo:</strong> fsolyluna@hotmail.com | Joshuasolis_05@hotmail.com<br>
      <strong>Teléfono:</strong> 3310000793<br>
      <strong>Facebook:</strong> <a href="https://www.facebook.com/share/16ttoLTbHK/?mibextid=wwXIfr" target="_blank">D&F en Facebook</a><br>
      <strong>Instagram:</strong> <a href="https://www.instagram.com/df_precision" target="_blank">@df_precision</a><br>
      <strong>Sitio web:</strong> <a href="https://maquinadosdf.github.io/DF-Presicion/" target="_blank">DF-Presicion</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 D&F Diseño y Fabricación - Todos los derechos reservados.</p>
    <p>Contáctanos: fsolyluna@hotmail.com | Joshuasolis_05@hotmail.com | Tel: 3310000793</p>
    <p>Síguenos en:
      <a href="https://www.facebook.com/share/16ttoLTbHK/?mibextid=wwXIfr" target="_blank">Facebook</a>
      <a href="https://www.instagram.com/df_precision" target="_blank">Instagram</a>
      <a href="https://maquinadosdf.github.io/DF-Presicion/" target="_blank">Sitio Web</a>
    </p>
  </footer>

  <!-- Botón de WhatsApp flotante -->
  <a href="https://wa.me/523315841619" target="_blank"
     style="position: fixed; bottom: 20px; right: 20px; background-color: #25D366; color: white; padding: 15px; border-radius: 50%; text-decoration: none; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2); z-index: 999;">
    <i class="fab fa-whatsapp" style="font-size: 24px;"></i>
  </a>
</body>
</html>
