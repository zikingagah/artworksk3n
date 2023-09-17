<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daftar Produk</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            position: relative;
        }

        h1 {
            margin: 0;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .product {
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px;
            text-align: center;
            background-color: #fff;
            position: relative;
        }

        .product img {
            max-width: 100%;
            height: auto;
        }

        .product h2 {
            font-size: 18px;
            margin: 10px 0;
        }

        .product p {
            font-size: 14px;
        }

        /* Style untuk tombol WhatsApp */
        .whatsapp-button {
            display: block;
            margin-top: 10px;
            background-color: #25d366;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }

        /* Style untuk label "Sold" */
        .sold-label {
            position: absolute;
            top: 10px;
            right: 10px;
            background-color: #ff0000;
            color: #fff;
            padding: 5px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Daftar Produk</h1>
    </header>

    <div class="container">
        <div class="product">
            <span class="sold-label">Sold</span>
            <img src="produk1.jpg" alt="Produk 1">
            <h2>Produk 1</h2>
            <p>Deskripsi produk 1. Lorem ipsum dolor sit amet.</p>
            <p>Harga: $19.99</p>
            <a href="https://wa.me/NOMOR-TELEPON-ANDA?text=Saya%20ingin%20membeli%20Produk%201" target="_blank" class="whatsapp-button">WhatsApp</a>
        </div>

        <div class="product">
            <img src="produk2.jpg" alt="Produk 2">
            <h2>Produk 2</h2>
            <p>Deskripsi produk 2. Lorem ipsum dolor sit amet.</p>
            <p>Harga: $24.99</p>
            <a href="https://wa.me/NOMOR-TELEPON-ANDA?text=Saya%20ingin%20membeli%20Produk%202" target="_blank" class="whatsapp-button">WhatsApp</a>
        </div>

        <!-- Tambahkan produk lainnya di sini -->

    </div>
</body>
</html>
