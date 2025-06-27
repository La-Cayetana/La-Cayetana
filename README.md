<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Ropa Upcycling • Exclusividad Sostenible</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="hero">
    <div class="overlay">
      <h1>Ropa Upcycling</h1>
      <p>Transformamos prendas en piezas exclusivas, llenas de color, creatividad y conciencia ambiental.</p>
      <a href="#productos" class="btn">Ver Productos</a>
    </div>
  </header>

  <nav>
    <ul>
      <li><a href="#productos">Productos</a></li>
      <li><a href="#nosotros">Nosotros</a></li>
      <li><a href="#tienda">Tienda</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <main>
    <section id="productos" class="galeria">
      <h2>Galería de Productos</h2>
      <div class="productos-grid">
        <div class="producto">
          <img src="product1.jpg" alt="Bolso bordado creativo">
          <h3>Bolsos bordados creativos</h3>
          <p>¡Lleva arte y sostenibilidad contigo!</p>
        </div>
        <div class="producto">
          <img src="product2.jpg" alt="Chaqueta intervenida original">
          <h3>Chaquetas intervenidas</h3>
          <p>Piezas vintage reinventadas con bordados originales y detalles únicos.</p>
        </div>
        <div class="producto">
          <img src="product3.jpg" alt="Camisa estampada y colorida">
          <h3>Camisas estampadas y coloridas</h3>
          <p>Camisas llenas de vida y personalidad, perfectas para destacar.</p>
        </div>
        <div class="producto">
          <img src="product4.jpg" alt="Jeans bordados florales">
          <h3>Jeans bordados</h3>
          <p>Vaqueros intervenidos con flores y patrones artesanales, ideales para un look auténtico.</p>
        </div>
      </div>
    </section>

    <section id="nosotros" class="about">
      <h2>¿Quiénes somos?</h2>
      <p>
        Creemos en la moda circular y en dar nueva vida a prendas olvidadas. Cada pieza cuenta una historia y está hecha a mano con dedicación y cariño.
        <br>
        <strong>¡Viste diferente, viste con impacto positivo!</strong>
      </p>
    </section>

    <section id="tienda" class="tienda">
      <h2>Tienda</h2>
      <p>Descubre todas las prendas disponibles y elige tu favorita. Recuerda: cada producto es único e irrepetible.</p>
      <ul class="filtros">
        <li><button>Bolsos</button></li>
        <li><button>Chaquetas</button></li>
        <li><button>Camisas</button></li>
        <li><button>Jeans</button></li>
      </ul>
      <div class="tienda-grid">
        <!-- Aquí puedes repetir los productos o integrar tu sistema de e-commerce -->
      </div>
    </section>

    <section id="contacto" class="contacto">
      <h2>Contacto y Redes</h2>
      <form>
        <input type="text" placeholder="Tu nombre" required>
        <input type="email" placeholder="Tu correo" required>
        <textarea placeholder="¿En qué podemos ayudarte?" required></textarea>
        <button type="submit">Enviar</button>
      </form>
      <div class="redes">
        <a href="https://www.instagram.com/lacayetana.upcycling/" target="_blank" aria-label="Instagram">
          <img src="instagram.svg" alt="Instagram">
        </a>
        <a href="https://www.facebook.com/" target="_blank" aria-label="Facebook">
          <img src="facebook.svg" alt="Facebook">
        </a>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Ropa Upcycling. Hecho con ♥ en España.</p>
  </footer>
</body>
</html>
