# DEST1[index.html.html](https://github.com/user-attachments/files/22193953/index.html.html)
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Con Visión y Convicción 4: Desintoxicados - 11 de Octubre 2025 en Iglesia Betesda.">
  <title>Con Visión y Convicción 4</title>
  <style>
    :root {
      --principal: #FFD700;
      --fondo: #000;
      --secundario: #1a1a1a;
      --texto: #fff;
      --sombra: rgba(255, 215, 0, 0.4);
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background: var(--fondo);
      color: var(--texto);
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 3rem 1rem 2rem;
      background: var(--secundario);
      border-bottom: 4px solid var(--principal);
    }

    header h1 {
      font-size: clamp(2rem, 5vw, 3.5rem);
      color: var(--principal);
      text-transform: uppercase;
      text-shadow: 0 0 15px var(--sombra);
      margin: 0.5rem 0;
    }

    header p {
      font-size: 1.2rem;
      color: #ccc;
      margin: 0;
    }

    .countdown {
      margin-top: 1rem;
      font-size: 1.5rem;
      font-weight: bold;
      letter-spacing: 1px;
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0%, 100% { text-shadow: 0 0 5px var(--sombra); }
      50% { text-shadow: 0 0 20px var(--sombra); }
    }

    main {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 2rem 1rem;
    }

    .card-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5rem;
      max-width: 900px;
      width: 100%;
    }

    .card {
      background: var(--secundario);
      border: 2px solid var(--principal);
      border-radius: 20px;
      padding: 2rem;
      color: var(--principal);
      font-weight: bold;
      font-size: 1.2rem;
      text-align: center;
      transition: transform 0.3s, background 0.3s, color 0.3s, box-shadow 0.3s;
      cursor: pointer;
    }

    .card:hover,
    .card:focus-visible {
      background: var(--principal);
      color: var(--fondo);
      transform: translateY(-8px);
      box-shadow: 0 8px 20px var(--sombra);
      outline: none;
    }

    .section {
      display: none;
      max-width: 900px;
      margin: auto;
      padding: 1.5rem;
      text-align: left;
      animation: fadeIn 0.6s ease-in-out;
    }

    .section.active {
      display: block;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(15px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .back-btn {
      display: inline-block;
      margin-top: 1.5rem;
      padding: 0.7rem 1.5rem;
      background: var(--principal);
      color: var(--fondo);
      border-radius: 10px;
      font-weight: bold;
      text-decoration: none;
      cursor: pointer;
      transition: background 0.3s;
    }

    .back-btn:hover,
    .back-btn:focus-visible {
      background: #e6c200;
      outline: none;
    }

    footer {
      background: var(--secundario);
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      border-top: 2px solid var(--principal);
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>Con Visión y Convicción 4: Desintoxicados</h1>
    <p>11 de Octubre 2025 - Iglesia Betesda</p>
    <div class="countdown" id="countdown" aria-live="polite"></div>
  </header>

  <main>
    <!-- MENÚ PRINCIPAL -->
    <nav class="card-container" id="menu" aria-label="Menú principal">
      <button class="card" data-section="juegos">🎮 Juegos</button>
      <button class="card" data-section="programa">🗓️ Programa</button>
      <button class="card" data-section="invitados">🎤 Invitados</button>
      <button class="card" data-section="registro">📝 Registro</button>
    </nav>

    <!-- SECCIONES -->
   <section class="section" id="juegos">
  <h2>🎮 Juegos</h2>
  <article>
    <h3>La carrera de la Vida</h3>
    <p>
      <strong>Equipos:</strong> Los equipos estarán integrados de 
      <b>3 a 5 participantes</b> y cada uno tendrá que realizar un mini juego 
      para lograr el objetivo.
    </p>
    <h4>Mini Juegos:</h4>
    <ul>
      <li>⚔️ Esgrimas</li>
      <li>📖 Preguntas bíblicas</li>
      <li>🧩 Rompecabezas</li>
      <li>✨ ¡Y más!</li>
    </ul>
  </article>
  <figure style="text-align:center; margin-top:1rem;">
    <img src="imagenes/juegos.jpg" alt="Participantes jugando en dinámicas del evento" style="max-width:100%; border-radius:15px; box-shadow:0 0 15px var(--sombra);">
    <figcaption style="color:#ccc; margin-top:0.5rem;">Diversión y unidad en cada dinámica</figcaption>
  </figure>
  <button class="back-btn" onclick="volverMenu()">⬅ Volver</button>
</section>

<section class="section" id="programa">
  <h2>🗓️ Programa</h2>
  <ol>
    <li>🙏 Inicio</li>
    <li>🎶 Alabanza</li>
    <li>🎲 Rompehielos</li>
    <li>⭐ Participación Especial</li>
    <li>📖 Predicación y Ministración</li>
    <li>🎮 Juegos</li>
    <li>🏆 Premiación</li>
    <li>🍽️ Despedida y Comida</li>
  </ol>
  <figure style="text-align:center; margin-top:1rem;">
    <img src="imagenes/programa.jpg" alt="Programa del evento cristiano" style="max-width:100%; border-radius:15px; box-shadow:0 0 15px var(--sombra);">
    <figcaption style="color:#ccc; margin-top:0.5rem;">Un programa lleno de bendición</figcaption>
  </figure>
  <button class="back-btn" onclick="volverMenu()">⬅ Volver</button>
</section>

<section class="section" id="invitados">
  <h2>🎤 Invitados</h2>
  <p><strong>Iglesias de todas partes de San Quintín</strong></p>
  <h3>📜 Antecedentes de Ganadores:</h3>
  <ul>
    <li>Con Visión y Convicción 1 “Tiempo de Luz” → <em>Templo Monte Moria (La Providencia)</em></li>
    <li>Con Visión y Convicción 2 “Levántate y Resplandece” → <em>Iglesia Betesda (Díaz Ordaz)</em></li>
    <li>Con Visión y Convicción 3 “Encontrando a Jesús” → <em>Iglesia (San Quintín)</em></li>
    <li>Con Visión y Convicción 4 “Desintoxicados” → <strong>¡Puedes ser tú y tu iglesia!</strong></li>
  </ul>
  <figure style="text-align:center; margin-top:1rem;">
    <img src="imagenes/invitados.jpg" alt="Conferencistas e iglesias invitadas" style="max-width:100%; border-radius:15px; box-shadow:0 0 15px var(--sombra);">
    <figcaption style="color:#ccc; margin-top:0.5rem;">Unidos en Cristo, de diferentes iglesias</figcaption>
  </figure>
  <button class="back-btn" onclick="volverMenu()">⬅ Volver</button>
</section>

<section class="section" id="registro">
  <h2>📝 Registro</h2>
  <p>Puedes confirmar tu participación enviándonos un mensaje en nuestra <strong>Página de Facebook</strong> o comunicándote a nuestro <strong>WhatsApp</strong>.</p>
  <ul>
    <li>📱 Facebook: <a href="https://www.facebook.com/profile.php?id=61569053580998" target="_blank">Jóvenes MEJ</a></li>
    <li>💬 WhatsApp: <a href="https://wa.me/" target="_blank">616 137 1165</a></li>
  </ul>
  <p>📍 También podrás registrarte el mismo día del evento, Para mayor informacion puedes contactarnos en las redes sociales de la parte de arriba Dios te bendiga.</p>
  <figure style="text-align:center; margin-top:1rem;">
    <img src="imagenes/registro.jpg" alt="Registro de participantes" style="max-width:100%; border-radius:15px; box-shadow:0 0 15px var(--sombra);">
    <figcaption style="color:#ccc; margin-top:0.5rem;">Asegura tu lugar en esta gran experiencia</figcaption>
  </figure>
  <button class="back-btn" onclick="volverMenu()">⬅ Volver</button>
</section>
  </main>

  <footer>
    &copy; 2025 Con Visión y Convicción | Todos los derechos reservados
  </footer>

  <script>
    // Cuenta regresiva
    const countdown = document.getElementById("countdown");
    const eventDate = new Date("Oct 11, 2025 17:00:00").getTime();

    function updateCountdown() {
      const now = Date.now();
      const distance = eventDate - now;

      if (distance <= 0) {
        countdown.textContent = "🎉 ¡El evento ha comenzado!";
        return;
      }

      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);

      countdown.textContent = `⏳ Faltan ${days}d ${hours}h ${minutes}m ${seconds}s`;
    }

    setInterval(updateCountdown, 1000);
    updateCountdown();

    // Navegación entre secciones
    const cards = document.querySelectorAll(".card");
    const menu = document.getElementById("menu");
    const sections = document.querySelectorAll(".section");

    cards.forEach(card => {
      card.addEventListener("click", () => {
        const sectionId = card.dataset.section;
        menu.style.display = "none";
        sections.forEach(sec => sec.classList.remove("active"));
        document.getElementById(sectionId).classList.add("active");
      });
    });

    function volverMenu() {
      sections.forEach(sec => sec.classList.remove("active"));
      menu.style.display = "grid";
    }
  </script>
</body>
</html>
