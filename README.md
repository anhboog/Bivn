# Bivn
Crytpto 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mua Bán Tiền Ảo</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Chợ Mua Bán Tiền Ảo</h1>
  </header>

  <section id="price">
    <h2>Tỷ giá hiện tại</h2>
    <div>
      <span id="bitcoinPrice">Đang tải...</span>
    </div>
  </section>

  <section id="transaction">
    <h2>Giao dịch Mua/Bán Bitcoin</h2>
    <form id="transactionForm">
      <input type="number" id="amount" placeholder="Số lượng Bitcoin" required>
      <select id="action">
        <option value="buy">Mua</option>
        <option value="sell">Bán</option>
      </select>
      <button type="submit">Thực hiện giao dịch</button>
    </form>
  </section>

  <footer>
    <p>© 2024 Chợ Mua Bán Tiền Ảo</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
