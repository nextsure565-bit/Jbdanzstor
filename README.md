<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Store Akun FF - Jual Akun Free Fire Murah</title>
    <style>
        /* Desain Tema Gaming Gelap & Premium */
        body {
            background-color: #0d0d11;
            color: #ffffff;
            font-family: 'Segoe UI', Roboto, sans-serif;
            margin: 0;
            padding: 20px;
        }
        .header {
            text-align: center;
            margin-bottom: 40px;
        }
        .header h1 {
            color: #ff6600;
            margin-bottom: 5px;
            text-transform: uppercase;
            text-shadow: 0 0 10px rgba(255, 102, 0, 0.3);
        }
        .header p {
            color: #aaa;
            margin: 0;
        }
        
        /* Grid Pembungkus Kartu Akun */
        .catalog-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        /* Desain Kartu Produk Akun FF */
        .account-card {
            background: linear-gradient(145deg, #181822, #1f1f2e);
            border: 1px solid #2d2d3f;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.5);
            transition: transform 0.3s, border-color 0.3s;
        }
        .account-card:hover {
            transform: translateY(-5px);
            border-color: #ff6600;
        }
        
        /* Gambar / Banner Akun */
        .account-img {
            width: 100%;
            height: 180px;
            background-color: #252535;
            object-fit: cover;
            border-bottom: 2px solid #ff6600;
        }
        
        /* Detail Informasi Akun */
        .account-details {
            padding: 20px;
        }
        .account-title {
            font-size: 18px;
            font-weight: bold;
            margin: 0 0 15px 0;
            color: #fff;
        }
        .spec-list {
            list-style: none;
            padding: 0;
            margin: 0 0 20px 0;
            font-size: 14px;
            color: #ccc;
        }
        .spec-list li {
            margin-bottom: 8px;
            display: flex;
            justify-content: space-between;
        }
        .spec-list span {
            color: #ff9900;
            font-weight: bold;
        }
        
        /* Harga Akun */
        .price-tag {
            font-size: 20px;
            color: #00ffcc;
            font-weight: bold;
            margin-bottom: 15px;
            display: block;
        }
        
        /* Tombol Beli via WhatsApp */
        .btn-buy {
            display: block;
            text-align: center;
            background: linear-gradient(90deg, #ff6600, #ff8800);
            color: #fff;
            text-decoration: none;
            padding: 12px;
            border-radius: 6px;
            font-weight: bold;
            text-transform: uppercase;
            transition: background 0.3s;
        }
        .btn-buy:hover {
            background: linear-gradient(90deg, #ff8800, #ffaa00);
        }
    </style>
</head>
<body>

<div class="header">
    <h1>FF Account Store</h1>
    <p>Tempat jual beli akun Free Fire aman, murah, dan terpercaya</p>
</div>

<div class="catalog-grid">

    <!-- KARTU AKUN 1 -->
    <div class="account-card">
        <!-- Ganti URL gambar di bawah dengan foto ss akun Anda -->
        <img class="account-img" src="https://placeholder.com" alt="SS Akun FF">
        <div class="account-details">
            <div class="account-title">Akun FF Sultan Spesial #01</div>
            <ul class="spec-list">
                <li>Level Akun: <span>Lv 72</span></li>
                <li>Bundle Utama: <span>Naruto & Sakura</span></li>
                <li>Evo Gun: <span>MP40 Predator (Lv 5)</span></li>
                <li>Login Melalui: <span>FB (Data Polos)</span></li>
            </ul>
            <span class="price-tag">Rp 350.000</span>
            <!-- PENTING: Ganti nomor WA & teks pesan di fungsi JavaScript di bawah -->
            <a href="#" class="btn-buy" onclick="beliAkun('Akun Sultan #01', 'Rp 350.000')">Hubungi Penjual</a>
        </div>
    </div>

    <!-- KARTU AKUN 2 -->
    <div class="account-card">
        <img class="account-img" src="https://placeholder.com" alt="SS Akun FF">
        <div class="account-details">
            <div class="account-title">Akun FF Old Gacha #02</div>
            <ul class="spec-list">
                <li>Level Akun: <span>Lv 65</span></li>
                <li>Bundle Utama: <span>Sasuke Uchiha</span></li>
                <li>Evo Gun: <span>AK47 Blue Flame (Lv Max)</span></li>
                <li>Login Melalui: <span>Google (Aman)</span></li>
            </ul>
            <span class="price-tag">Rp 250.000</span>
            <a href="#" class="btn-buy" onclick="beliAkun('Akun Old Gacha #02', 'Rp 250.000')">Hubungi Penjual</a>
        </div>
    </div>

</div>

<script>
    function beliAkun(namaAkun, hargaAkun) {
        // 1. GANTI DENGAN NOMOR WHATSAPP ANDA (Gunakan kode negara, contoh 62812xxx)
        const nomorWA = "6281234567890"; 
        
        // 2. Draft pesan otomatis saat diklik oleh pembeli
        const pesan = `Halo Admin, saya tertarik ingin membeli akun Free Fire berikut:\n\n` +
                      `• Nama Akun: ${namaAkun}\n` +
                      `• Harga: ${hargaAkun}\n\n` +
                      `Apakah akun ini masih tersedia dan bisa dibeli?`;
        
        // 3. Mengarahkan pembeli langsung ke aplikasi WhatsApp
        const urlWhatsApp = `https://whatsapp.com{nomorWA}&text=${encodeURIComponent(pesan)}`;
        window.open(urlWhatsApp, '_blank');
    }
</script>

</body>
</html>

