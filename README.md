<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shop Cá Nhân</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f8f8f8;
    }
    header {
      background-color: #2196F3;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    main {
      padding: 1rem;
    }
    .product {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 1rem;
      margin-bottom: 1rem;
    }
    .product img {
      width: 100%;
      max-height: 200px;
      object-fit: cover;
      border-radius: 4px;
    }
    .product h3 {
      margin: 0.5rem 0;
    }
    .price {
      color: #d32f2f;
      font-weight: bold;
    }
    .buy-button {
      background: #4CAF50;
      color: white;
      padding: 0.5rem 1rem;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      margin-top: 0.5rem;
    }
    footer {
      background-color: #eee;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Shop Của Tôi</h1>
    <p>Chuyên bán các sản phẩm chất lượng!</p>
  </header>

  <main>
    <div class="product">
      <img src="https://via.placeholder.com/300x200" alt="Sản phẩm 1">
      <h3>Sản phẩm 1</h3>
      <p class="price">100.000 VNĐ</p>
      <button class="buy-button">Mua ngay</button>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/300x200" alt="Sản phẩm 2">
      <h3>Sản phẩm 2</h3>
      <p class="price">150.000 VNĐ</p>
      <button class="buy-button">Mua ngay</button>
    </div>
  </main>

  <footer>
    &copy; 2025 Shop Cá Nhân - Liên hệ: 0123 456 789
  </footer>
</body>
</html>


