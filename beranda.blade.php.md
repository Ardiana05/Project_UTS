# Project_UTS
Nama Aggota Kelompok: 
1. Firda Wardina (230212028) (Beranda)
2. Ardiana (230212034) (Menu) 
3. Yuliani Irma Waty Ujung (230212039) (Promo) 
4. Indah Mayana Siregar (230212054) (Tentang) 
5. Shifa Nabila (230212086)


<!-- Kerja Kelompok -->

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Makan Yuk! - Penjualan Makanan</title>
    <style>
        body {
            font-family: "Poppins", sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fffaf3;
            color: #333;
            scroll-behavior: smooth;
        }
        header {
            background-color: #d35400;
            color: white;
            text-align: center;
            padding: 25px 10px;
        }
        nav {
            background-color: #e67e22;
            text-align: center;
            padding: 12px;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: 600;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 40px 20px;
            text-align: center;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            color: #d35400;
            margin-bottom: 20px;
        }
        .menu-item, .promo-box, .about-box, .contact-box {
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            padding: 20px;
            margin-bottom: 30px;
        }
        .menu-item img, .promo-box img {
            width: 100%;
            height: 200px;
            border-radius: 10px;
            object-fit: cover;
            margin-bottom: 10px;
        }
        .menu-container, .promo-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .menu-item, .promo-box {
            width: 300px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .menu-item:hover, .promo-box:hover {
            transform: scale(1.03);
            box-shadow: 0 8px 18px rgba(0,0,0,0.2);
        }
        .btn-pesan, .btn-whatsapp {
            display: inline-block;
            padding: 10px 20px;
            border-radius: 8px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .btn-pesan {
            background-color: #d35400;
        }
        .btn-pesan:hover {
            background-color: #e67e22;
        }
        .btn-whatsapp {
            background-color: #25D366;
        }
        .btn-whatsapp:hover {
            background-color: #20b458;
        }
        .about-box img {
            width: 100%;
            border-radius: 12px;
            margin: 20px 0;
        }
        footer {
            background-color: #d35400;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 40px;
        }
        section {
            margin-bottom: 70px;
        }
    </style>
</head>
<body>

    <!-- HEADER -->
    <header>
        <h1>🍴 Makan Yuk!</h1>
        <p>Makanan Lezat, Harga Bersahabat</p>
    </header>

    <!-- NAVIGATION -->
    <nav>
        <a href="#beranda">Beranda</a>
        <a href="#menu">Menu</a>
        <a href="#promo">Promo</a>
        <a href="#tentang">Tentang</a>
        <a href="#kontak">Kontak</a>
    </nav>
    <!-- Firda Wardina -->

    <main>
        <!-- BERANDA -->
        <section id="beranda">
            <h2>Selamat Datang di Makan Yuk!</h2>
            <p>Kami menyajikan berbagai hidangan rumahan yang menggugah selera. Pesan sekarang dan rasakan kelezatannya!</p>
            <img src="{{ asset('assets/img/elements/logo_makanan.png') }}" alt="Makanan Lezat" style="max-width: 100%; border-radius: 15px;">
        </section>

<!-- Ardiana -->

    <!-- MENU MAKANAN -->
        <section id="menu">
            <h2>🍛 Menu Makanan</h3>
            <div class="menu-container">
                <div class="menu-item">
                    <img src="{{ asset('assets/img/elements/nasi goreng.jpeg') }}" alt="Nasi Goreng Spesial"
                    style="width: 170px; height: auto; border-radius: 10px;">
                    <h3>Nasi Goreng Spesial</h3>
                    <p>Harga: Rp25.000</p>
                    <a class="btn-pesan" href="https://wa.me/6281234567890?text=Halo%2C+saya+mau+pesan+Nasi+Goreng+Spesial" target="_blank">Pesan Sekarang</a>
                </div>

                <div class="menu-item">
                    <img src="{{ asset('assets/img/elements/ayam bakar.jpeg') }}" alt="Ayam Bakar"
                    style="width: 170px; height: auto; border-radius: 10px;">
                    <h3>Ayam Bakar</h3>
                    <p>Harga: Rp20.000</p>
                    <a class="btn-pesan" href="https://wa.me/6281234567890?text=Halo%2C+saya+mau+pesan+Ayam+Geprek" target="_blank">Pesan Sekarang</a>
                </div>

                <div class="menu-item">
                    <img src="https://img.freepik.com/free-photo/iced-tea-glass-with-lemon_1203-1746.jpg" alt="Es Teh Manis"
                    style="width: 170px; height: auto; border-radius: 10px;">
                    <h3>Es Teh Manis</h3>
                    <p>Harga: Rp5.000</p>
                    <a class="btn-pesan" href="https://wa.me/6281234567890?text=Halo%2C+saya+mau+pesan+Es+Teh+Manis" target="_blank">Pesan Sekarang</a>
                </div>
            </div>
        </section>
        <!-- Yuliani Irma Waty Ujung -->

        <!-- PROMO & PAKET -->
        <section id="promo">
            <h2>🎁 Promo & Paket Spesial</h2>
            <div class="promo-container">
                <div class="promo-box">
                    <img src="{{ asset('assets/img/elements/nasi goreng es teh.jpg') }}" alt="Paket Hemat 1">
                    <h3>🔥 Paket Hemat 1</h3>
                    <p>Nasi Goreng + Es Teh Manis<br><strong>Rp28.000</strong></p>
                    <a class="btn-pesan" href="https://wa.me/6281234567890?text=Halo%2C+saya+mau+pesan+Paket+Hemat+1" target="_blank">Pesan Sekarang</a>
                </div>

                <div class="promo-box">
                    <img src="{{ asset('assets/img/elements/nasi ayam bakar.jpg') }}" alt="Paket Hemat 2">
                    <h3>🔥 Paket Hemat 2</h3>
                    <p>Ayam Bakar + Nasi + Minum<br><strong>Rp30.000</strong></p>
                    <a class="btn-pesan" href="https://wa.me/6281234567890?text=Halo%2C+saya+mau+pesan+Paket+Hemat+2" target="_blank">Pesan Sekarang</a>
                </div>

                <div class="promo-box">
                    <img src="https://img.freepik.com/free-photo/top-view-fried-noodles-with-vegetables_140725-2037.jpg" alt="Diskon Spesial">
                    <h3>💥 Diskon Spesial</h3>
                    <p>Diskon 10% untuk pembelian di atas Rp100.000</p>
                    <a class="btn-pesan" href="https://wa.me/6281234567890?text=Halo%2C+saya+mau+pesan+dengan+Diskon+10%25" target="_blank">Pesan Sekarang</a>
                </div>
            </div>
        </section>

        
