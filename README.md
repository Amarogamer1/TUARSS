# TUARSS
<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <title>TUARSS - Tienda Escolar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f8fb;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #007bff;
      color: white;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    .contenedor {
      padding: 20px;
      text-align: center;
    }
    .productos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 20px;
    }
    .producto {
      background-color: white;
      border-radius: 10px;
      padding: 15px;
      width: 220px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .producto:hover {
      transform: scale(1.03);
    }
    .producto img {
      width: 100%;
      border-radius: 8px;
    }
    .producto h3 {
      margin: 10px 0 5px;
    }
    .producto p {
      margin: 0 0 10px;
      color: #007bff;
      font-weight: bold;
    }
    .producto button {
      background-color: #28a745;
      color: white;
      border: none;
      padding: 8px 12px;
      border-radius: 5px;
      cursor: pointer;
    }
    .producto button:hover {
      background-color: #218838;
    }
    .mensaje {
      margin-top: 30px;
      font-size: 18px;
      color: #555;
    }
    footer {
      background-color: #f1f1f1;
      padding: 15px;
      text-align: center;
      margin-top: 40px;
    }
  </style>
  <script>
    function agregarAlCarrito(nombre) {
      alert('Agregaste "' + nombre + '" al carrito (esto es solo una demo).');
    }
  </script>
</head>
<body>
  <header>
    <h1>TUARSS 🛒</h1>
    <p>Tu tienda de útiles escolares al mejor precio</p>
  </header>

  <div class="contenedor">
    <div class="productos">
      <div class="producto">
        <div class="producto">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Papel_lustre.jpg/800px-Papel_lustre.jpg" alt="Papel lustre">
  <h3>Papel lustre</h3>
  <p>$600 CLP</p>
  <button onclick="agregarAlCarrito('Papel lustre')">Comprar producto</button>
</div>

<div class="producto">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f2/Water_bottle_01.jpg/640px-Water_bottle_01.jpg" alt="Botella de plástico">
  <h3>Botella de plástico</h3>
  <p>$1.000 CLP</p>
  <button onclick="agregarAlCarrito('Botella de plástico')">Comprar producto</button>
</div>
        <img src="Lapiz.jpg" alt="Lápiz escolar">
        <h3>Set de lápices</h3>
        <p>$1.000 CLP</p>
        <button onclick="agregarAlCarrito('Set de lápices')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="Cuaderno.jpg" alt="Cuaderno escolar">
        <h3>Cuaderno universitario</h3>
        <p>$1.500 CLP</p>
        <button onclick="agregarAlCarrito('Cuaderno universitario')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="Mochila.jpg" alt="Mochila escolar">
        <h3>Mochila resistente</h3>
        <p>$15.000 CLP</p>
        <button onclick="agregarAlCarrito('Mochila resistente')">Comprar producto</button>
      </div>

      <!-- Nuevos 17 productos -->
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Estuche" alt="Estuche escolar">
        <h3>Estuche escolar</h3>
        <p>$2.000 CLP</p>
        <button onclick="agregarAlCarrito('Estuche escolar')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Regla" alt="Regla 30cm">
        <h3>Regla 30cm</h3>
        <p>$800 CLP</p>
        <button onclick="agregarAlCarrito('Regla 30cm')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Goma" alt="Goma de borrar">
        <h3>Goma de borrar</h3>
        <p>$500 CLP</p>
        <button onclick="agregarAlCarrito('Goma de borrar')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Tijeras" alt="Tijeras escolares">
        <h3>Tijeras escolares</h3>
        <p>$1.200 CLP</p>
        <button onclick="agregarAlCarrito('Tijeras escolares')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Pega" alt="Pega en barra">
        <h3>Pega en barra</h3>
        <p>$700 CLP</p>
        <button onclick="agregarAlCarrito('Pega en barra')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Lapiz+mina" alt="Lápiz mina">
        <h3>Lápiz mina</h3>
        <p>$600 CLP</p>
        <button onclick="agregarAlCarrito('Lápiz mina')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Corrector" alt="Corrector líquido">
        <h3>Corrector líquido</h3>
        <p>$1.000 CLP</p>
        <button onclick="agregarAlCarrito('Corrector líquido')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Saca+puntas" alt="Sacapuntas">
        <h3>Sacapuntas</h3>
        <p>$400 CLP</p>
        <button onclick="agregarAlCarrito('Sacapuntas')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Cartuchera" alt="Cartuchera metálica">
        <h3>Cartuchera metálica</h3>
        <p>$2.500 CLP</p>
        <button onclick="agregarAlCarrito('Cartuchera metálica')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Carpeta" alt="Carpeta plástica">
        <h3>Carpeta plástica</h3>
        <p>$1.200 CLP</p>
        <button onclick="agregarAlCarrito('Carpeta plástica')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Colores" alt="Colores de madera">
        <h3>Colores de madera</h3>
        <p>$3.000 CLP</p>
        <button onclick="agregarAlCarrito('Colores de madera')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Marcadores" alt="Marcadores permanentes">
        <h3>Marcadores permanentes</h3>
        <p>$2.000 CLP</p>
        <button onclick="agregarAlCarrito('Marcadores permanentes')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Resaltadores" alt="Resaltadores">
        <h3>Resaltadores</h3>
        <p>$1.800 CLP</p>
        <button onclick="agregarAlCarrito('Resaltadores')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Block+dibujo" alt="Block de dibujo">
        <h3>Block de dibujo</h3>
        <p>$2.200 CLP</p>
        <button onclick="agregarAlCarrito('Block de dibujo')">Comprar producto</button>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/220x150?text=Compás" alt="Compás escolar">
        <h3>Compás escolar</h3>
        <p>$1.700 CLP</p>
        <button onclick="agregarAlCarrito('Compás escolar')">Comprar producto</button>
      </div>
    </div>

    <p class="mensaje">🎉 ¡Pronto más productos disponibles en TUARSS!</p>
  </div>

  <footer>
    &copy; 2025 TUARSS - Todos los derechos reservados.
  </footer>
</body>
</html>
