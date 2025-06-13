 <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TUARSS - Tienda Escolar</title>
 
    <style>
    .encabezado {
      background-color: #333333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .productos {
      background-color: #04376B;
      padding: 20px;
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
    }
    .producto {
      background-color: white;
      border-radius: 8px;
      padding: 15px;
      width: 200px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.15);
      text-align: center;
    }
  </style>
</head>

<body>

  <div class="encabezado">
    <h1>TUARSS 🦖⛩️🛒</h1>
    <p>Tu tienda de útiles escolares al mejor precio</p>
  </div>

  <!-- carrito fuera de contenedores, fijo en la esquina -->
  <div class="carrito" style="
    position: fixed;
    top: 20px;
    right: 20px;
    font-size: 20px;
    background-color: white;
    color: black;
    padding: 8px 14px;
    border-radius: 20px;
    font-weight: bold;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    z-index: 1000;
    cursor: pointer;
  ">
    🛒 <span id="contador-carrito">0</span>
  </div>

</body>
<div class="productos">
  <div class="producto">
    <img src="imagenes/Lapiz.jpg.jpeg" alt="Set de lápices">
    <h3>Set de lápices</h3>
    <p>$1.000 CLP</p>
    <button onclick="agregarAlCarrito('Set de lápices')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Cuaderno.jpg.jpeg" alt="Cuaderno universitario">
    <h3>Cuaderno universitario</h3>
    <p>$1.500 CLP</p>
    <button onclick="agregarAlCarrito('Cuaderno universitario')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Mochila.jpg.jpeg" alt="Mochila resistente">
    <h3>Mochila resistente</h3>
    <p>$15.000 CLP</p>
    <button onclick="agregarAlCarrito('Mochila resistente')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Goma.jpg.jpeg" alt="Goma de borrar">
    <h3>Goma de borrar</h3>
    <p>$300 CLP</p>
    <button onclick="agregarAlCarrito('Goma de borrar')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Regla.jpg.jpeg" alt="Regla de 30 cm">
    <h3>Regla 30 cm</h3>
    <p>$700 CLP</p>
    <button onclick="agregarAlCarrito('Regla 30 cm')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Corrector.jpg.jpeg" alt="Corrector líquido">
    <h3>Corrector líquido</h3>
    <p>$1.200 CLP</p>
    <button onclick="agregarAlCarrito('Corrector líquido')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Sacapuntas.jpg.jpeg" alt="Sacapuntas">
    <h3>Sacapuntas</h3>
    <p>$600 CLP</p>
    <button onclick="agregarAlCarrito('Sacapuntas')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Colores.jpg.jpeg" alt="colores de palo">
    <h3>colores de palo</h3>
    <p>$2.500 CLP</p>
    <button onclick="agregarAlCarrito('colores de palo')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Estuche.jpg.jpeg" alt="Estuche escolar">
    <h3>Estuche escolar</h3>
    <p>$3.000 CLP</p>
    <button onclick="agregarAlCarrito('Estuche escolar')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/destacadores.jpg.jpeg" alt="Set de destacadores">
    <h3>Set de destacadores</h3>
    <p>$2.000 CLP</p>
    <button onclick="agregarAlCarrito('Set de resaltadores')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Pegamento.jpg.jpeg" alt="Pega en barra">
    <h3>Pega en barra</h3>
    <p>$800 CLP</p>
    <button onclick="agregarAlCarrito('Pega en barra')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Compas.jpg.jpeg" alt="Compás metálico">
    <h3>Compás metálico</h3>
    <p>$1.800 CLP</p>
    <button onclick="agregarAlCarrito('Compás metálico')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Tijeras.jpg.jpeg" alt="Tijeras escolares">
    <h3>Tijeras escolares</h3>
    <p>$900 CLP</p>
    <button onclick="agregarAlCarrito('Tijeras escolares')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Cartuchera.jpg.jpeg" alt="Cartuchera con cierre">
    <h3>Cartuchera con cierre</h3>
    <p>$3.200 CLP</p>
    <button onclick="agregarAlCarrito('Cartuchera con cierre')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Carpeta.jpg.jpeg" alt="Carpeta basica">
    <h3>Carpeta basica</h3>
    <p>$1.200 CLP</p>
    <button onclick="agregarAlCarrito('Carpeta basica')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/marcador.jpg.jpeg" alt="Marcador permanente">
    <h3>Marcador permanente</h3>
    <p>$2.300 CLP</p>
    <button onclick="agregarAlCarrito('Marcador permanente')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/mina.jpg.jpeg" alt="lapiz mina">
    <h3>lapiz mina</h3>
    <p>$800 CLP</p>
    <button onclick="agregarAlCarrito('lapiz mina')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/block.jpg.jpeg" alt="block de dibujo">
    <h3>block de dibujo</h3>
    <p>$1.500 CLP</p>
    <button onclick="agregarAlCarrito('block de dibujo')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/PapelLustre.jpg.jpeg" alt="Papel lustre">
    <h3>Papel lustre</h3>
    <p>$600 CLP</p>
    <button onclick="agregarAlCarrito('Papel lustre')">Comprar producto</button>
  </div>
  <div class="producto">
    <img src="imagenes/Botella.jpg.jpeg" alt="Botella de plástico">
    <h3>Botella de plástico</h3>
    <p>$1.000 CLP</p>
    <button onclick="agregarAlCarrito('Botella de plástico')">Comprar producto</button>
  </div>
  
  </div> <!-- cierre div productos -->

<!-- MODAL (CUADRO EMERGENTE) -->
<div id="modal" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.5); justify-content:center; align-items:center; z-index:2000;">
  <div style="background:white; padding:20px; border-radius:10px; text-align:center; max-width:300px;">
    <p id="modal-texto" style="margin-bottom:20px;">¿Agregar producto al carrito?</p>
    <button onclick="confirmarAgregar()" style="margin-right:10px;">Agregar al carrito</button>
    <button onclick="cerrarModal()">Cancelar</button>
  </div>
</div>

<!-- Script -->
<script>
  let contador = 0;
  let productoSeleccionado = "";
  const modal = document.getElementById('modal');
  const modalTexto = document.getElementById('modal-texto');

  function agregarAlCarrito(nombreProducto) {
    productoSeleccionado = nombreProducto;
    modalTexto.textContent = `¿Agregar "${nombreProducto}" al carrito?`;
    modal.style.display = 'flex';
  }

  function confirmarAgregar() {
    contador++;
    document.getElementById('contador-carrito').textContent = contador;
    modal.style.display = 'none';
  }

  function cerrarModal() {
    modal.style.display = 'none';
  }
</script>
 </body>
</html>
