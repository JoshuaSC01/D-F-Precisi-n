<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>D&F Diseño y Fabricación</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1666634157070-6fd830fb5672?q=80&w=1470&auto=format&fit=crop');
      background-size: cover;
      background-position: center;
      color: white;
    }
    header {
      text-align: center;
      padding: 100px 20px 40px;
      background-color: rgba(0, 0, 0, 0.5);
    }
    header h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 20px;
    }
    nav {
      background-color: #001f3f;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px 0;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .section {
      padding: 40px 20px;
      background-color: rgba(255, 255, 255, 0.95);
      color: #222;
      max-width: 1000px;
      margin: auto;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      margin-top: 30px;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .service-box {
      background-color: #f1f1f1;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
      text-align: center;
    }
    .gallery-button a {
      display: inline-block;
      background-color: #001f3f;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      text-decoration: none;
      margin-top: 20px;
    }
    .contact input, .contact textarea {
      width: 100%;
      margin: 5px 0;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    .contact button {
      background-color: #28a745;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      background-color: #001f3f;
      color: white;
      padding: 30px 20px;
      margin-top: 40px;
    }
    footer a {
      color: #28a745;
      margin: 0 10px;
      text-decoration: none;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 32px;
      }
      nav {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <header>
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
  <a href="https://wa.me/523315841619" target="_blank" style="position: fixed; bottom: 20px; right: 20px; background-color: #25D366; color: white; padding: 15px; border-radius: 50%; text-decoration: none; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);">
    <i class="fab fa-whatsapp" style="font-size: 24px;"></i>
  </a>
</body>
</html>
