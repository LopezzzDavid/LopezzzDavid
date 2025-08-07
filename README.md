<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>David López | Portafolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Fira Code', monospace;
      background-color: #121212;
      color: #f5f5f5;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(90deg, #1f1f1f, #292929);
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      color: #00bfff;
    }

    header p {
      font-style: italic;
      color: #cccccc;
    }

    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: #00bcd4;
      margin-bottom: 1rem;
      border-bottom: 1px solid #333;
      padding-bottom: 0.5rem;
    }

    .center {
      text-align: center;
    }

    .justify {
      text-align: justify;
    }

    .project {
      background: #1e1e1e;
      margin-bottom: 1.5rem;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 0 10px #000;
    }

    footer {
      text-align: center;
      padding: 1rem;
      color: #999;
      font-size: 0.9rem;
    }

    a {
      color: #00bfff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>David López</h1>
    <p>Estudiante de Ingeniería Electrónica - USTA Bogotá</p>
  </header>

  <section class="center">
    <h2>Sobre mí</h2>
    <p class="justify">
      Soy un estudiante de Ingeniería Electrónica apasionado por la automatización, el control de sistemas y la programación embebida. Me gusta explorar soluciones técnicas que mezclen software y hardware, buscando siempre la eficiencia, creatividad y funcionalidad en cada proyecto.
    </p>
  </section>

  <section>
    <h2 class="center">Proyectos destacados</h2>

    <div class="project">
      <h3>🚗 Carro seguidor de línea</h3>
      <p class="justify">Diseño de un carro controlado mediante sensores infrarrojos. Implementación analógica y digital, controlando la dirección y velocidad con PWM.</p>
    </div>

    <div class="project">
      <h3>🕷️ Araña robótica</h3>
      <p class="justify">Prototipo de robot con múltiples patas controlado desde el computador vía serial. Integración de interfaz en Python con firmware en C++.</p>
    </div>

    <div class="project">
      <h3>⚙️ Sistema de control de motores</h3>
      <p class="justify">Sistema de control para motores DC usando la DSP LAUNCHXL F28379D. Controladores PID y respuesta dinámica.</p>
    </div>

    <div class="project">
      <h3>💡 Driver de lámpara LED</h3>
      <p class="justify">Sistema de encendido y regulación de potencia para una lámpara LED usando Electrónica de Potencia y modulación PWM.</p>
    </div>
  </section>

  <section class="center">
    <h2>Contacto</h2>
    <p>
      📧 <a href="mailto:lopezzzdavid@example.com">lopezzzdavid@example.com</a><br />
      🔗 <a href="https://github.com/LopezzzDavid" target="_blank">github.com/LopezzzDavid</a><br />
      💼 <a href="https://linkedin.com/in/lopezzzdavid" target="_blank">linkedin.com/in/lopezzzdavid</a>
    </p>
  </section>

  <footer>
    <p>Última actualización: Agosto 2025 | Portafolio personal</p>
  </footer>
</body>
</html>
