<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Кавʼярня «Ранкова»</title>
<style>
{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: "Segoe UI", Arial, sans-serif;
}

body{
    background:#faf7f2;
    color:#3e2f24;
    line-height:1.6;
    text-align: center; / горизонтальне центрування для ВСЬОГО тексту /
}

/ HERO /
.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:linear-gradient(135deg,#1f4d3a,#5b3a29);
    flex-direction: column;
    color:#fff;
}

.hero h1{
    font-size:52px;
    margin-bottom:15px;
}

.hero p{
    font-size:20px;
    max-width:500px;
    margin:0 auto 30px;
}

.hero a{
    padding:12px 30px;
    border-radius:30px;
    background:#d8c3a5;
    color:#3e2f24;
    text-decoration:none;
    font-weight:600;
}

/ SECTIONS /
section{
    padding:60px 20px;
}

section h2{
    font-size:36px;
    margin-bottom:25px;
}

section p{
    max-width:700px;
    margin:0 auto;
}

/ MENU /
.menu-block{
    margin:15px 0;
}

.menu-block ul{
    list-style:none;
}

.menu-block li{
    margin:6px 0;
}

/ GALLERY /
.gallery-grid{
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap:15px;
    max-width:600px;
    margin:0 auto;
}

.gallery-grid img{
    width:100%;
    max-width:120px;
    border-radius:12px;
}

/ CONTACTS /
.contacts{
    background:#f1e6d8;
    padding:40px 20px;
}

/ FOOTER /
footer{
    text-align:center;
    padding:15px;
    background:#3e2f24;
    color:#fff;
}

/ MOBILE */
@media(max-width:600px){
    .hero h1{font-size:34px;}
    section h2{font-size:28px;}
}
</style>
</head>

<body>

<header class="hero">
    <h1>Кавʼярня «Ранкова»</h1>
    <p>Місце, де ранок починається з ароматної кави та затишку</p>
    <a href="#menu">Переглянути меню</a>
</header>

<section>
    <h2>Про нас</h2>
    <p>
        «Ранкова» — це кавʼярня про якість, спокій і теплу атмосферу.
        Ми створили простір, де хочеться зупинитись і насолодитись моментом.
    </p>
</section>

<section id="menu">
    <h2>Меню</h2>

    <div class="menu-block">
        <strong>Кава</strong>
        <ul>
            <li>Еспресо</li>
            <li>Капучино</li>
            <li>Латте</li>
        </ul>
    </div>

    <div class="menu-block">
        <strong>Авторські напої</strong>
        <ul>
            <li>Карамельний латте</li>
            <li>Пряна кава</li>
        </ul>
    </div>

    <div class="menu-block">
        <strong>Десерти</strong>
        <ul>
            <li>Круасан</li>
            <li>Чізкейк</li>
        </ul>
        <em>від 60 грн</em>
    </div>
</section>

<section>
    <h2>Галерея</h2>
    <div class="gallery-grid">
        <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93">
        <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085">
        <img src="https://images.unsplash.com/photo-1511920170033-f8396924c348">
    </div>
</section>

<section class="contacts">
    <h2>Контакти</h2>
    <p>📍 м. Київ, вул. Ранкова, 12</p>
    <p>🕒 8:00 – 20:00</p>
    <p>📞 +38 (000) 123-45-67</p>
    <p>Instagram: @rankova.coffee</p>
</section>

<footer>
    © 2025 Кавʼярня «Ранкова»
</footer>

</body>
</html>
