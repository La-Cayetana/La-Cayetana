<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>La Cayetana</title>

  <!-- Tipografías: Elegante para título, moderna para cuerpo -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Unbounded:wght@400;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Unbounded', sans-serif;
      background-color: #4b1d1d; /* Vino tinto profundo */
      color: #3eeeff; /* Azul eléctrico */
      padding: 2rem;
      text-align: center;
    }
    header {
      font-family: 'Playfair Display', serif;
      font-size: 3.2rem;
      margin-bottom: 1rem;
      color: #ffffff;
    }
    .subtitle {
      font-size: 1.3rem;
      color: #b3eaff;
      margin-bottom: 2rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 1rem;
      margin-bottom: 2rem;
    }
    .gallery img {
      width: 100%;
      border-radius: 12px;
      object-fit: cover;
      height: 220px;
      border: 2px solid #3eeeff;
    }
    .cta {
      margin: 2rem 0;
    }
    .cta a {
      text-decoration: none;
      background: #3eeeff;
      color: #4b1d1d;
      padding: 0.8rem 1.6rem;
      border-radius: 8px;
      font-weight: bold;
      transition: background 0.3s;
    }
    .cta a:hover {
      background: #1cbfd9;
    }
    .section {
      margin: 3rem 0;
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
      line-height: 1.6;
    }
    footer {
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #ddd;
    }
  </style>
</head>
<body>

  <header>La Cayetana</header>
  <div class="subtitle">Moda circular + creatividad consciente desde Valencia</div>

  <div class="gallery">
    <img src="https://via.placeholder.com/300x300?text=Prenda+1" alt="Prenda 1">
    <img src="https://via.placeholder.com/300x300?text=Prenda+2" alt="Prenda 2">
    <img src="https://via.placeholder.com/300x300?text=Prenda+3" alt="Prenda 3">
    <img src="https://via.placeholder.com/300x300?text=Prenda+4" alt="Prenda 4">
  </div>

  <div class="cta">
    <a href="https://instagram.com/lacayetana.upcycling" target="_blank">Síguenos en Instagram</a>
  </div>

  <div class="section">
    <h2>¿Qué es La Cayetana?</h2>
    <p>
      La Cayetana es una marca circular de moda intervenida y arte textil con base en Valencia.  
      No hacemos moda rápida: contamos historias a través de cada prenda.  
      <br><br>
      Transformamos ropa olvidada en piezas únicas, llenas de vida, memoria y estilo.  
      Bordamos, manchamos, recortamos, tejemos, pintamos  
      y creamos comunidad.  
      <br><br>
      No vendemos ropa. Compartimos procesos, caos y creatividad.
    </p>
  </div>

  <footer>
    © 2025 La Cayetana. Hecho con amor desde Valencia.
  </footer>

</body>
</html>
