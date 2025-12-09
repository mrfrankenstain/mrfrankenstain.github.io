<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sony Al'amri - Portfolio</title>
    <style>
        * {margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif;}
        body {background: #0f0f0f; color: #f5f5f5;}
        header {padding: 60px 20px; text-align: center; background: linear-gradient(135deg, #1e1e1e, #181818);}        
        header h1 {font-size: 48px; font-weight: 700;}
        header p {font-size: 18px; margin-top: 10px; color: #bbbbbb;}
        .section {padding: 60px 20px; max-width: 1000px; margin: auto;}
        .title {font-size: 32px; margin-bottom: 20px; border-left: 6px solid #4fc3f7; padding-left: 10px;}
        .bio {line-height: 1.7; color: #d4d4d4; font-size: 17px;}
        .skills, .experience {margin-top: 20px;}
        .skills ul, .experience ul {list-style: none; padding-left: 0;}
        .skills li, .experience li {padding: 10px 0; border-bottom: 1px solid #333;}
        .experience h3 {font-size: 20px; margin-bottom: 5px;}
        .contact {text-align: center; margin-top: 40px;}
        .contact a {color: #4fc3f7; text-decoration: none; font-size: 18px;}
        .cta {margin-top: 20px; display: inline-block; padding: 12px 22px; background: #4fc3f7; color: #000; font-weight: bold; border-radius: 6px; text-decoration: none; transition: 0.3s;}        
        .cta:hover {background: #81d4fa;}
        footer {text-align: center; padding: 20px; margin-top: 40px; background: #111; color: #666; font-size: 14px;}
    </style>
</head>
<body>

<header>
    <h1>Sony Al'amri</h1>
    <p>Fullstack Developer & Mahasiswa Teknik Informatika</p>
</header>

<section class="section">
    <h2 class="title">Tentang Saya</h2>
    <p class="bio">
        Mahasiswa semester dua Teknik Informatika di Universitas Sangga Buana YPKP Bandung dengan pengalaman dalam
        pengembangan fullstack. Pernah bekerja di CV. Four Vision Media dan PT. Galan Unggul Tekno Sembada, fokus pada
        pembuatan aplikasi web, manajemen basis data, dan pengembangan antarmuka yang responsif.
    </p>
</section>

<section class="section">
    <h2 class="title">Keahlian</h2>
    <div class="skills">
        <ul>
            <li>PHP, HTML, CSS</li>
            <li>Laravel, Bootstrap</li>
            <li>MySQL, PostgreSQL</li>
            <li>Git, Visual Studio Code</li>
            <li>Responsive Web Development</li>
        </ul>
    </div>
</section>

<section class="section">
    <h2 class="title">Pengalaman Kerja</h2>
    <div class="experience">
        <ul>
            <li>
                <h3>PT. Galan Unggul Tekno Sembada (2023 - 2024)</h3>
                Mengembangkan aplikasi web dengan Laravel & PHP, merancang database, dan meningkatkan performa sistem.
            </li>
            <li>
                <h3>CV. Four Vision Media (2022)</h3>
                Membangun aplikasi web dinamis menggunakan Laravel, PHP, dan Bootstrap.
            </li>
        </ul>
    </div>
</section>

<section class="section contact">
    <h2 class="title">Kontak</h2>
    <p>Email: <a href="mailto:sonyalamri20@gmail.com">sonyalamri20@gmail.com</a></p>
    <p>WhatsApp: <a href="https://wa.me/628154061832" target="_blank">+62815-4061-832</a></p>
    <br>
    <a href="https://github.com/mrfrankenstain" class="cta" target="_blank">Kunjungi GitHub Saya</a>
</section>

<footer>
    © 2025 Sony Al'amri — Portfolio Landing Page
</footer>

</body>
</html>
