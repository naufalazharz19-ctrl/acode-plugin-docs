<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manajemen Agribisnis Perkebunan Interaktif 🌳💰</title>
    <style>
        /* CSS untuk Gaya Unik */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5fcf5; /* Latar belakang hijau muda/krem */
            color: #333;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .container {
            width: 85%;
            max-width: 1100px;
            margin: 30px auto;
            background-color: #fff;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 50, 0, 0.1);
        }
        header {
            background-color: #2e8b57; /* Hijau Perkebunan */
            color: white;
            padding: 25px;
            text-align: center;
            border-radius: 12px 12px 0 0;
            margin: -25px -25px 20px -25px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-style: italic;
        }
        
        /* Gaya Accordion (Menu Lipat) */
        .accordion-button {
            background-color: #4CAF50; /* Hijau tombol utama */
            color: white;
            cursor: pointer;
            padding: 18px;
            width: 100%;
            border: none;
            text-align: left;
            outline: none;
            font-size: 1.2em;
            transition: 0.4s;
            border-radius: 8px;
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .accordion-button:hover {
            background-color: #3e8e41;
        }
        .accordion-button::after {
            content: '+';
            font-size: 1.5em;
            font-weight: bold;
            transition: transform 0.3s;
        }
        .active-button::after {
            content: '−';
            transform: rotate(180deg);
        }
        .accordion-content {
            padding: 0 18px;
            background-color: white;
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease-out;
            border-left: 3px solid #4CAF50;
            margin-bottom: 15px;
        }
        
        /* Gaya Kartu Contoh (Card Examples) */
        .card-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-around;
            margin-top: 20px;
        }
        .card {
            background-color: #e6ffe6; /* Latar belakang kartu */
            border: 1px solid #c2e0c2;
            padding: 15px;
            border-radius: 8px;
            width: calc(33% - 20px);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
            transition: transform 0.2s;
            text-align: center;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card h3 {
            color: #006400; /* Hijau Gelap */
            margin-top: 0;
        }
        
        /* Gaya Daftar Unik */
        ul.check-list {
            list-style: none;
            padding-left: 0;
        }
        ul.check-list li {
            padding-left: 2em;
            position: relative;
            margin-bottom: 8px;
        }
        ul.check-list li::before {
            content: '✅'; /* Emoji sebagai bullet point unik */
            position: absolute;
            left: 0;
            color: #4CAF50;
        }

        /* Responsiveness */
        @media (max-width: 768px) {
            .card {
                width: 100%; /* Kartu menjadi satu kolom di layar kecil */
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>🚜 Manajemen Agribisnis Tanaman Perkebunan 📊</h1>
            <p>Jalan Menuju Panen Maksimal dan Keuntungan Berkelanjutan</p>
        </header>
        
        <section>
            <h2>Apa Itu Manajemen Agribisnis Perkebunan? 🤔</h2>
            <p>Ini adalah **seni dan ilmu mengelola seluruh rantai kegiatan usaha perkebunan**—mulai dari bibit di tanah (hulu) hingga produk sampai ke tangan konsumen (hilir)—untuk mencapai **keuntungan maksimal dan keberlanjutan** usaha.</p>
            <p>Sistem ini mencakup 3 aspek utama: **Hulu (Input), Budidaya (On-Farm), dan Hilir (Pengolahan & Pemasaran).**</p>
        </section>

        <hr>

        <section>
            <h2>Lima Pilar Manajemen Agribisnis (Interaktif! Klik untuk Membuka) 👆</h2>
            
            <button class="accordion-button">1. Perencanaan (Planning) 🗺️</button>
            <div class="accordion-content">
                <p><strong>Penjelasan:</strong> Menentukan tujuan, strategi, dan alokasi sumber daya. Ini adalah peta jalan Anda.</p>
                <ul class="check-list">
                    <li>**Teknik Unik:** Analisis *SWOT* Perkebunan (Kekuatan, Kelemahan, Peluang, Ancaman).</li>
                    <li>**Contoh:** Memutuskan jenis komoditas (misalnya, Kelapa Sawit atau Kopi) dan membuat Anggaran Biaya Tahunan.</li>
                </ul>
            </div>

            <button class="accordion-button">2. Pengorganisasian (Organizing) 👥</button>
            <div class="accordion-content">
                <p><strong>Penjelasan:</strong> Menyusun struktur, pembagian kerja, dan penentuan wewenang/tanggung jawab tim.</p>
                <ul class="check-list">
                    <li>**Teknik Unik:** Desain Struktur Organisasi Berbasis Blok atau Wilayah untuk mempermudah pengawasan lapangan.</li>
                    <li>**Contoh:** Menunjuk Mandor Tanaman, Staf Keuangan, dan Tim Pemasaran.</li>
                </ul>
            </div>

            <button class="accordion-button">3. Pelaksanaan (Actuating) 🌱</button>
            <div class="accordion-content">
                <p><strong>Penjelasan:</strong> Tahap implementasi di lapangan. Ini adalah inti dari kegiatan budidaya.</p>
                <ul class="check-list">
                    <li>**Teknik Unik:** Penerapan *Good Agricultural Practices* (GAP) seperti penyulaman, pemupukan tepat dosis, dan pengendalian hama terpadu.</li>
                    <li>**Contoh:** Melakukan pemanenan sesuai standar mutu (misalnya, Fraksi Matang pada Kelapa Sawit).</li>
                </ul>
            </div>

            <button class="accordion-button">4. Pengawasan (Controlling) 🔍</button>
            <div class="accordion-content">
                <p><strong>Penjelasan:</strong> Memastikan semua kegiatan berjalan sesuai rencana dan standar. Koreksi jika terjadi penyimpangan.</p>
                <ul class="check-list">
                    <li>**Teknik Unik:** Penggunaan *Drone* untuk monitoring kesehatan tanaman dan tingkat panen secara cepat.</li>
                    <li>**Contoh:** Audit Keuangan dan Audit Mutu Hasil Panen (misalnya, mengukur kadar air Biji Kopi).</li>
                </ul>
            </div>
            
            <button class="accordion-button">5. Pemasaran dan Distribusi (Marketing) 📈</button>
            <div class="accordion-content">
                <p><strong>Penjelasan:</strong> Menghubungkan produk dari kebun ke pasar dan konsumen.</p>
                <ul class="check-list">
                    <li>**Teknik Unik:** Strategi *Niche Market* (misalnya, Kopi Organik Bersertifikat) atau Pemasaran Digital (E-commerce).</li>
                    <li>**Contoh:** Menjual CPO ke pabrik besar dengan kontrak jangka panjang atau menjual Kopi ke kafe-kafe premium.</li>
                </ul>
            </div>
        </section>

        <hr>

        <section>
            <h2>Contoh Implementasi Perkebunan Populer 🌴</h2>
            <p>Manajemen yang baik menghasilkan komoditas berkualitas tinggi.</p>
            <div class="card-container">
                <div class="card">
                    <h3>Kelapa Sawit 🌴</h3>
                    <p>Fokus Manajemen: Efisiensi panen dan ekstraksi CPO, manajemen limbah (POME).</p>
                    <small>Komoditas energi dan pangan utama.</small>
                </div>
                <div class="card">
                    <h3>Karet 💧</h3>
                    <p>Fokus Manajemen: Teknik penyadapan yang tepat agar pohon tidak rusak, dan pengolahan menjadi RSS atau SIR.</p>
                    <small>Komoditas industri vital.</small>
                </div>
                <div class="card">
                    <h3>Kopi ☕</h3>
                    <p>Fokus Manajemen: *Post-harvest handling* (pengolahan pasca panen) seperti metode *full-wash* atau *natural* untuk harga premium.</p>
                    <small>Komoditas *lifestyle* dengan nilai tambah tinggi.</small>
                </div>
            </div>
        </section>

        <footer>
            <p style="text-align: center; margin-top: 30px; color: #555;">&copy; 2025 Edukasi Agribisnis - Belajar Menjadi Manajer Perkebunan Handal.</p>
        </footer>
    </div>

    <script>
        /* JavaScript untuk Fungsi Interaktif Accordion */
        var acc = document.getElementsByClassName("accordion-button");
        var i;

        for (i = 0; i < acc.length; i++) {
          acc[i].addEventListener("click", function() {
            /* Toggle the 'active-button' class */
            this.classList.toggle("active-button");

            /* Tampilkan/Sembunyikan konten */
            var content = this.nextElementSibling;
            if (content.style.maxHeight){
              content.style.maxHeight = null;
            } else {
              /* Atur tinggi konten sesuai isinya */
              content.style.maxHeight = content.scrollHeight + "px";
            } 
          });
        }
    </script>

</body>
</html>
