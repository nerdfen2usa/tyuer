
git clone https://github.com/username/website-saya.git
cd tyuere
mkdir assets
touch index.html assets/styles.css assets/scripts.js
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Saya</title>
    <link rel="stylesheet" href="assets/styles.css">
</head>
<body>
    <header>
        <h1>Selamat Datang di Website Saya</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="Halaman Utama">
            <h2>Home</h2>
            <p>Ini adalah halaman utama.</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>Informasi tentang website ini.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Kontak kami melalui email: <a href="nuyt@gmail.com">info@example.com</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Website Saya. All rights reserved.</p>
    </footer>
    <script src="assets/scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}
nav ul {
    list-style: none;
    padding: 0;
}
nav ul li {
    display: inline;
    margin: 0 10px;
}
nav ul li a {
    color: #fff;
    text-decoration: none;
}
main {
    padding: 20px;
}
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: absolute;
    bottom: 0;
    width: 100%;
}
document.addEventListener('DOMContentLoaded', () => {
    console.log('Website berhasil dimuat!');
});
git add .
git commit -m "Menambahkan website dasar"
git push origin main
