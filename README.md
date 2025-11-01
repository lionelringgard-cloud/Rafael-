# Rafael-
Website toko roti

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lionel Bakery</title>
  <style>
    * {
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    body {
      margin: 0;
      background-color: #fffaf2;
      color: #222;
    }
    header {
      text-align: center;
      padding: 20px;
    }
    header img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
    }
    h1 {
      margin: 10px 0;
      font-size: 24px;
    }
    .search-box {
      display: flex;
      justify-content: center;
      margin-bottom: 15px;
    }
    .search-box input {
      width: 80%;
      padding: 8px 12px;
      border: 2px solid #ddd;
      border-radius: 20px;
      font-size: 14px;
    }
    .banner {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 24px;
    }
    .banner .label {
      background-color: #e53935;
      color: white;
      padding: 6px 12px;
      border-radius: 4px;
      font-weight: bold;
    }
    .banner .discount {
      background-color: #fff;
      border: 2px dashed #3f51b5;
      color: #3f51b5;
      padding: 6px 12px;
      border-radius: 8px;
      font-weight: bold;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 16px;
      padding: 20px;
    }
    .product {
      background-color: #ffa500;;
      border-radius: 10px;
      padding: 10px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    .product img {
      width: 100%;
      height: 100px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product h3 {
      margin: 8px 0 4px;
      color: Red;
      font-size: 15px;
    }
    .product p {
      font-size: 13px;
      margin: 0 0 6px;
    }
    .price {
      font-weight: bold;
      margin-bottom: 8px;
    }
    .buttons {
      display: flex;
      justify-content: center;
      gap: 6px;
    }
    button {
      padding: 6px 8px;
      border: none;
      border-radius: 4px;
      font-weight: bold;
      cursor: pointer;
      font-size: 12px;
    }
    .buy {
      background-color: #283593;
      color: white;
    }
    .cart {
      background-color: #4dd0e1;
      color: #000;
    }
    footer {
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      background-color: #ffeb3b;
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 10px 0;
      border-top: 2px solid #f0c000;
    }
    footer img {
      width: 30px;
    }
  </style>
</head>
<body>
  <header>
    <img src="Lionel Shop Logo.jpg" alt="Logo Lionel Bakery">
    <h1>Lionel Bakery</h1>
    <div class="search-box">
      <input type="text" placeholder="Cari roti...">
    </div>
  </header>  
  <div class="banner">
    <div class="label">Roti Baguette</div>
    <div class="discount">DISKON 50%</div>
  </div>  <section class="products">
    <div class="product">
      <img src="Roti Baguette.jpg" alt="Roti Baguette">
      <h3>Roti Baguette</h3>
      <p style="color: white;">Roti dengan kualitas tinggi</p>
      <div class="price">Rp.20.000 (promo)</div>
      <div class="buttons">
        <button class="buy">Beli Sekarang</button>
        <button class="cart">Tambah Keranjang</button>
      </div>
    </div><div class="product">
  <img src="Roti gembong gedhe.jpg" alt="Roti gembong gedhe">
  <h3>Roti Gembong Gedhe</h3>
  <p style="color: white;">Roti dengan panggangan sempurna</p>
  <div class="price">Rp.18.000</div>
  <div class="buttons">
    <button class="buy">Beli Sekarang</button>
    <button class="cart">Tambah Keranjang</button>
  </div>
</div>

<div class="product">
  <img src="Roti bakar.jpg" alt="Roti Bakar">
  <h3>Roti Bakar</h3>
  <p style="color: white;">Roti dengan susu manis</p>
  <div class="price">Rp.15.000</div>
  <div class="buttons">
    <button class="buy">Beli Sekarang</button>
    <button class="cart">Tambah Keranjang</button>
  </div>
</div>

<div class="product">
  <img src="Roti buaya.jpg" alt="Roti Buaya">
  <h3>Roti Buaya</h3>
  <p style="color: white;">Roti dengan bentuk yang imut</p>
  <div class="price">Rp.55.000</div>
  <div class="buttons">
    <button class="buy">Beli Sekarang</button>
    <button class="cart">Tambah Keranjang</button>
  </div>
</div>
<br/><br>

  </section>  
  <footer>
    <img src="Rumah.jpeg" alt="Home">
    <img src="images.png" alt="Mail">
    <img src="Stick man_1.png" alt="User">
  </footer>
</body>
</html>
