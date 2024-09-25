<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Ropa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .product {
            border: 1px solid #ddd;
            background: #fff;
            padding: 10px;
            margin: 10px;
            float: left;
            width: calc(33.333% - 20px);
            box-sizing: border-box;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Tienda de Ropa</h1>
</header>

<div class="container">
    <h2>Nuestros Productos</h2>
    
    <div class="product">
        <img src="ruta/a/tu-imagen1.jpg" alt="Producto 1">
        <h3>Producto 1</h3>
        <p>Descripción del producto 1.</p>
        <p>Precio: $20</p>
        <button>Comprar</button>
    </div>

    <div class="product">
        <img src="ruta/a/tu-imagen2.jpg" alt="Producto 2">
        <h3>Producto 2</h3>
        <p>Descripción del producto 2.</p>
        <p>Precio: $25</p>
        <button>Comprar</button>
    </div>

    <div class="product">
        <img src="ruta/a/tu-imagen3.jpg" alt="Producto 3">
        <h3>Producto 3</h3>
        <p>Descripción del producto 3.</p>
        <p>Precio: $30</p>
        <button>Comprar</button>
    </div>
</div>

<footer>
    <p>&copy; 2024 Tienda de Ropa. Todos los derechos reservados.</p>
</footer>

</body>
</html>
