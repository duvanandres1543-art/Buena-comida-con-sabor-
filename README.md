<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Fish Thief - Restaurante</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #fdf6e3;
      color: #333;
      text-align: center;
    }
    header {
      background: #2e2e2e;
      color: white;
      padding: 20px;
    }
    header img {
      width: 120px;
      border-radius: 50%;
    }
    h1 {
      margin: 10px 0;
      font-size: 2.5em;
    }
    .menu {
      display: flex;
      justify-content: center;
      gap: 50px;
      padding: 40px;
      flex-wrap: wrap;
    }
    .menu-section {
      background: #fff;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      width: 280px;
    }
    .menu-section h2 {
      border-bottom: 2px solid #ccc;
      padding-bottom: 10px;
      margin-bottom: 15px;
      font-size: 1.5em;
      color: #444;
    }
    .menu-section ul {
      list-style: none;
      padding: 0;
    }
    .menu-section ul li {
      display: flex;
      justify-content: space-between;
      padding: 5px 0;
      border-bottom: 1px dotted #ddd;
    }
    .qr {
      margin: 40px auto;
    }
    footer {
      background: #2e2e2e;
      color: white;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <img src="menu.jpg" alt="Logo Restaurante">
    <h1>The Fish Thief</h1>
    <p>Sabores del mar con un toque especial 🐟</p>
  </header>

  <div class="menu">
    <div class="menu-section">
      <h2>Entrées</h2>
      <ul>
        <li><span>Grilled Salmon</span><span>45.000</span></li>
        <li><span>Fish and Chips</span><span>39.000</span></li>
        <li><span>Shrimp Scampi</span><span>42.000</span></li>
        <li><span>Lobster Tail</span><span>65.000</span></li>
        <li><span>Garlic Butter Prawns</span><span>46.000</span></li>
        <li><span>Mahi-Mahi Fillet</span><span>44.000</span></li>
        <li><span>Crab Cakes</span><span>41.000</span></li>
        <li><span>Mixed Seafood Paella</span><span>55.000</span></li>
        <li><span>Seared Tuna</span><span>48.000</span></li>
        <li><span>Raccoon’s Catch</span><span>50.000</span></li>
      </ul>
    </div>

    <div class="menu-section">
      <h2>Desserts</h2>
      <ul>
        <li><span>Key Lime Pie</span><span>19.000</span></li>
        <li><span>Chocolate Mousse</span><span>16.000</span></li>
        <li><span>Coconut Flan</span><span>15.000</span></li>
        <li><span>Cheesecake Berry</span><span>17.000</span></li>
        <li><span>Mango Sorbet</span><span>14.000</span></li>
        <li><span>Tiramisu</span><span>18.000</span></li>
        <li><span>Passion Fruit Panna Cotta</span><span>16.000</span></li>
        <li><span>Caramel Brownie</span><span>15.000</span></li>
        <li><span>Ice Cream Trio</span><span>14.000</span></li>
        <li><span>Banana Foster</span><span>17.000</span></li>
      </ul>
    </div>

    <div class="menu-section">
      <h2>Bebidas</h2>
      <ul>
        <li><span>Fresh Lemonade</span><span>8.000</span></li>
        <li><span>Iced Tea</span><span>9.000</span></li>
        <li><span>Coconut Water</span><span>10.000</span></li>
        <li><span>Tropical Smoothie</span><span>14.000</span></li>
        <li><span>Colombian Coffee</span><span>7.000</span></li>
        <li><span>Craft Beer</span><span>12.000</span></li>
        <li><span>Red Wine Glass</span><span>20.000</span></li>
      </ul>
    </div>
  </div>

  <div class="qr">
    <h2>Escanea nuestro QR 📲</h2>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=https://tupagina.com" alt="Código QR">
  </div>

  <footer>
    <p>&copy; 2025 The Fish Thief - Todos los derechos reservados</p>
  </footer>
</body>
</html> 