<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Info9 - Belajar Itu Petualangan Seru!</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&family=Inter:wght@400&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Inter', sans-serif;
    background: #f4f7ff;
}

header {
    background: #0066FF;
    color: white;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-family: 'Poppins', sans-serif;
    font-size: 24px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-weight: bold;
}

.hero {
    text-align: center;
    padding: 60px 20px;
}

.hero h1 {
    font-family: 'Poppins', sans-serif;
    font-size: 36px;
    color: #0066FF;
}

.hero p {
    font-size: 18px;
}

.button-primary {
    background: #FF9F1C;
    color: white;
    padding: 12px 25px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: bold;
    display: inline-block;
    margin-top: 20px;
}

.section {
    padding: 40px;
}

.card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    padding: 25px;
    border-radius: 20px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.05);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-8px);
}

.card h3 {
    color: #0066FF;
}

.footer {
    background: #0066FF;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}
</style>
</head>

<body>

<header>
<div class="logo">Info9 🚀</div>
<nav>
<a href="#">Beranda</a>
<a href="#">Materi</a>
<a href="#">Galeri</a>
<a href="#">Tentang Bolang</a>
</nav>
</header>

<section class="hero">
<h1>Belajar Itu Petualangan Seru!</h1>
<p>Halo Sobat Tekno! Aku Bolang 🤖 Siap menjelajah dunia digital?</p>
<a href="#" class="button-primary">Jelajah Sekarang</a>
</section>

<section class="section">
<h2>✨ Petualangan Seru Bulan Ini</h2>
<div class="card-grid">
<div class="card">
<h3>🧠 Bab 2</h3>
<p>Adu Otak: Berpikir Komputasional</p>
</div>

<div class="card">
<h3>🤖 Bab 7</h3>
<p>Bikin Game & Coding Seru</p>
</div>

<div class="card">
<h3>📊 Bab 6</h3>
<p>Detektif Data</p>
</div>

<div class="card">
<h3>📘 Rangkuman</h3>
<p>Semua Bab</p>
</div>
</div>
</section>

<section class="section">
<h2>🔥 Karya Siswa Terbaru</h2>
<div class="card-grid">
<div class="card">Game Scratch Kelas 9A</div>
<div class="card">Poster Keamanan Digital</div>
<div class="card">Robot Line Follower</div>
<div class="card">Vlog Teknologi</div>
</div>
</section>

<div class="footer">
© 2026 Info9 - Informatika Kelas 9 bersama Bu Raisa
</div>

</body>
</html>
