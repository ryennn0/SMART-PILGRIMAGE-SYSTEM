<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Smart Pilgrimage System</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Segoe UI', sans-serif;
}

body{
    background:#f4f7f9;
    color:#333;
    line-height:1.6;
}

header{
    background:linear-gradient(135deg,#0f4c75,#1b6ca8);
    color:white;
    padding:60px 20px;
    text-align:center;
}

header h1{
    font-size:40px;
    margin-bottom:15px;
}

header p{
    max-width:800px;
    margin:auto;
}

section{
    padding:60px 10%;
}

.section-title{
    text-align:center;
    font-size:28px;
    margin-bottom:40px;
    color:#0f4c75;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:12px;
    box-shadow:0 4px 15px rgba(0,0,0,0.1);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.card h3{
    margin-bottom:15px;
    color:#1b6ca8;
}

.card ul{
    list-style:none;
}

.card ul li{
    padding:8px 0;
}

.lokasi{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.lokasi div{
    background:white;
    padding:20px;
    border-radius:12px;
    text-align:center;
    box-shadow:0 4px 15px rgba(0,0,0,0.1);
}

footer{
    background:#0f4c75;
    color:white;
    text-align:center;
    padding:20px;
}

button{
    padding:10px 20px;
    border:none;
    border-radius:8px;
    background:#1b6ca8;
    color:white;
    cursor:pointer;
    margin-top:10px;
}

button:hover{
    background:#145374;
}
</style>

</head>
<body>

<header>
    <h1>SMART PILGRIMAGE SYSTEM</h1>
    <p>Model Integrasi Kawasan Payung Madinah – Makam K.H. Mbah Hamid – Alun-Alun Kota Pasuruan dalam satu ekosistem digital terintegrasi.</p>
</header>

<section>
    <h2 class="section-title">Smart Information</h2>
    <div class="grid">
        <div class="card">
            <h3>QR Sejarah & Audio Guide</h3>
            <ul>
                <li>Scan QR untuk informasi sejarah</li>
                <li>Audio guide multibahasa</li>
                <li>Informasi tokoh & budaya</li>
            </ul>
        </div>
        <div class="card">
            <h3>Digital Storytelling</h3>
            <ul>
                <li>Konten interaktif</li>
                <li>Video dokumentasi</li>
                <li>Narasi sejarah digital</li>
            </ul>
        </div>
        <div class="card">
            <h3>Virtual Tour</h3>
            <ul>
                <li>360° View lokasi</li>
                <li>Preview sebelum kunjungan</li>
                <li>Akses via website & mobile</li>
            </ul>
        </div>
    </div>
</section>

<section>
    <h2 class="section-title">Smart Crowd Management</h2>
    <div class="grid">
        <div class="card">
            <h3>Monitoring Keramaian</h3>
            <p>Dashboard monitoring real-time jumlah pengunjung.</p>
        </div>
        <div class="card">
            <h3>Jadwal & Event Ziarah</h3>
            <p>Informasi jadwal acara keagamaan dan event khusus.</p>
        </div>
        <div class="card">
            <h3>Panduan Rute & Navigasi</h3>
            <p>Petunjuk rute terbaik menuju lokasi wisata religi.</p>
        </div>
    </div>
</section>

<section>
    <h2 class="section-title">Smart UMKM Integration</h2>
    <div class="grid">
        <div class="card">
            <h3>E-Katalog Pedagang</h3>
            <p>Daftar produk UMKM lokal sekitar kawasan wisata.</p>
        </div>
        <div class="card">
            <h3>Sistem E-Payment</h3>
            <p>Pembayaran non-tunai terintegrasi.</p>
        </div>
        <div class="card">
            <h3>Promosi UMKM Wisata</h3>
            <p>Promosi produk unggulan lokal secara digital.</p>
        </div>
    </div>
</section>

<section>
    <h2 class="section-title">Smart Feedback & Governance</h2>
    <div class="grid">
        <div class="card">
            <h3>Layanan Aspirasi Digital</h3>
            <p>Pengunjung dapat mengirim saran & laporan.</p>
            <button onclick="kirimAspirasi()">Kirim Aspirasi</button>
        </div>
        <div class="card">
            <h3>Dashboard Pengelola</h3>
            <p>Monitoring data kunjungan dan laporan.</p>
        </div>
        <div class="card">
            <h3>Transparansi & Kolaborasi</h3>
            <p>Publikasi data dan kerja sama stakeholder.</p>
        </div>
    </div>
</section>

<section>
    <h2 class="section-title">Koridor Wisata Religi Kota Pasuruan</h2>
    <div class="lokasi">
        <div>
            <h3>Payung Madinah</h3>
            <p>Kawasan wisata religi dengan ikon payung raksasa.</p>
        </div>
        <div>
            <h3>Makam K.H. Mbah Hamid</h3>
            <p>Pusat ziarah religi dan sejarah spiritual Kota Pasuruan.</p>
        </div>
        <div>
            <h3>Alun-Alun Kota Pasuruan</h3>
            <p>Pusat aktivitas masyarakat dan ruang terbuka publik.</p>
        </div>
    </div>
</section>

<footer>
    <p>© 2026 Smart Pilgrimage System | Kota Pasuruan</p>
</footer>

<script>
function kirimAspirasi(){
    alert("Terima kasih atas aspirasi Anda. Sistem akan segera memproses laporan.");
}
</script>

</body>
</html>
