<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NT² - Danza y Motivación</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f8ff;
      color: #333;
    }
    header {
      background-color: #87cefa;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 80px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      background: #e0f0ff;
      padding: 10px 0;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 50px 20px;
    }
    .hero h1 {
      font-size: 2.5em;
      color: #005a9c;
    }
    .hero p {
      font-size: 1.2em;
      color: #333;
    }
    .btn {
      background-color: #005a9c;
      color: #fff;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      display: inline-block;
      margin-top: 20px;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 10px;
      background: white;
    }
    .product img {
      max-width: 100%;
      border-radius: 8px;
    }
    form {
      display: flex;
      flex-direction: column;
      max-width: 400px;
      margin: 0 auto;
      gap: 10px;
    }
    input, textarea {
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    footer {
      background: #e0f0ff;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="NT² Logo" />
  </header>  <nav>
    <a href="#home">Inicio / Home</a>
    <a href="#productos">Productos / Products</a>
    <a href="#nosotros">Nosotros / About</a>
    <a href="#contacto">Contacto / Contact</a>
  </nav>  <section class="hero" id="home">
    <h1>Bienvenidos a NT²</h1>
    <p>Inspirados por la danza, creamos productos con alma y frases que motivan el corazón.</p>
    <a href="#productos" class="btn">Ver Productos / See Products</a>
  </section>  <section class="section" id="productos">
    <h2>Productos / Products</h2>
    <div class="products-grid">
      <div class="product">
        <img src="pulsera.jpg" alt="Pulsera" />
        <h3>Pulsera de inspiración / Inspirational Bracelet</h3>
        <p>$8.00</p>
      </div>
      <div class="product">
        <img src="pullover.jpg" alt="Pullover" />
        <h3>Pullover NT² / NT² Pullover</h3>
        <p>$25.00</p>
      </div>
      <div class="product">
        <img src="conjunto.jpg" alt="Conjunto Deportivo" />
        <h3>Conjunto Deportivo / Sports Set</h3>
        <p>$35.00</p>
      </div>
    </div>
  </section>  <section class="section" id="nosotros">
    <h2>Nosotros / About Us</h2>
    <p>NT² nace del sueño de una joven bailarina que desea compartir su pasión por la danza y la motivación a través de productos hermosos y llenos de significado.</p>
    <p>Inspirados en el movimiento, la gracia y la fuerza interior, cada artículo está diseñado con amor y dedicación.</p>
  </section>  <section class="section" id="contacto">
    <h2>Contacto / Contact</h2>
    <form>
      <input type="text" placeholder="Nombre / Name" required />
      <input type="email" placeholder="Email" required />
      <textarea placeholder="Mensaje / Message" rows="4" required></textarea>
      <button type="submit" class="btn">Enviar / Send</button>
    </form>
    <p>
      También puedes escribirnos por WhatsApp o seguirnos en Instagram.
    </p>
  </section>  <footer>
    &copy; 2025 NT². Todos los derechos reservados. / All rights reserved.
  </footer>
</body>
</html>
