<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="description"
        content="FaTya Online Shop menjual hijab modern dengan harga terjangkau dan kualitas premium.">
    <title>FaTya Online Shop</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Droid+Arabic+Kufi:wght@400;700&display=swap" rel="stylesheet">

</head>

<body>

    <header class="header">
        <div class="logo" dir="rtl">فتى حجاب</div>
        <nav>
            <ul class="nav-links">
                <li><a href="index.html">Beranda</a></li>
                <li><a href="produk/produk.html">Produk</a></li>
                <li><a href="#contact">Kontak</a></li>
            </ul>
        </nav>
        <div class="search-bar">
            <input type="text" placeholder="Cari produk...">
            <button>Cari</button>
        </div>

    </header>

    <script src="cart.js"></script>
    <main>
        <section class="banner">
            <h1>Promo Terbaik Hari Ini!</h1>
            <button>Belanja Sekarang</button>
        </section>

        <section id="products" class="product-grid">
            <div class="product-card">
                <img src="assets/produk 1.jpeg" alt="Produk 1">
                <h3>Pashmina Ceruty</h3>
                <p>Rp30.000</p>
                <button class="buy-now" onclick="goToCheckout(0)">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="assets/produk 2.jpeg" alt="Produk 2">
                <h3>Bella Square</h3>
                <p>Rp25.000</p>
                <button class="buy-now" onclick="goToCheckout(1)">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="assets/produk 3.jpeg" alt="Produk 3">
                <h3>Pet Jersey Premium</h3>
                <p>Rp25.000</p>
                <button class="buy-now" onclick="goToCheckout(2)">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="assets/produk 4.jpeg" alt="Produk 4">
                <h3>Bergo Hamidah</h3>
                <p>Rp20.000</p>
                <button class="buy-now" onclick="goToCheckout(3)">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="assets/produk 5.jpeg" alt="Produk 5">
                <h3>Pollycoton Square</h3>
                <p>Rp35.000</p>
                <button class="buy-now" onclick="goToCheckout(4)">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="assets/produk 6.jpeg" alt="Produk 6">
                <h3>Paris Classic Premium</h3>
                <p>Rp35.000</p>
                <button class="buy-now" onclick="goToCheckout(5)">Beli Sekarang</button>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>© 2024 Toko Modern. All Rights Reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>

</html>
