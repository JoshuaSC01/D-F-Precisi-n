<!DOCTYPE html>
<html lang="es">
<head>$1
    .section::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.4);
      z-index: 0;
      border-radius: 10px;
    }
    .section * {
      position: relative;
      z-index: 1;
    }
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
