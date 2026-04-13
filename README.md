<html lang="en">
<head>
<meta charset="UTF-8">
<title>Super Mario Space Race</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: linear-gradient(#5c94fc, #000033);
    color: white;
    overflow-x: hidden;
}

/* HEADER */
header {
    background: red;
    color: yellow;
    text-align: center;
    padding: 20px;
    font-size: 2em;
}

/* NAV */
nav {
    background: brown;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
}

/* SECTIONS */
section {
    background: rgba(255,255,255,0.9);
    color: black;
    margin: 20px;
    padding: 20px;
    border-radius: 10px;
}

/* ⭐ STARS */
.star {
    position: absolute;
    width: 5px;
    height: 5px;
    background: white;
    animation: twinkle 2s infinite alternate;
}

@keyframes twinkle {
    from { opacity: 0.2; }
    to { opacity: 1; }
}

/* 💰 COIN */
.coin {
    position: fixed;
    bottom: 0;
    width: 50px;
    animation: spin 2s linear infinite, floatUp 6s infinite;
}

@keyframes spin {
    from { transform: rotateY(0deg); }
    to { transform: rotateY(360deg); }
}

@keyframes floatUp {
    from { bottom: -60px; }
    to { bottom: 100%; }
}

/* 🍄 MARIO */
.mario {
    position: fixed;
    bottom: 0;
    left: 50px;
    width: 80px;
    animation: jump 1s infinite;
}

@keyframes jump {
    0% { bottom: 0; }
    50% { bottom: 120px; }
    100% { bottom: 0; }
}

/* IMAGES */
.image-box {
    text-align: center;
}

.image-box img {
    width: 300px;
    border-radius: 10px;
}

footer {
    background: red;
    text-align: center;
    padding: 10px;
}
</style>
</head>

<body>

<header>🍄 Super Mario Space Race 🚀</header>

<nav>
<a href="#overview">Overview</a>
<a href="#tensions">Tensions</a>
<a href="#impact">Impact</a>
<a href="#significance">Significance</a>
<a href="#concepts">Concepts</a>
<a href="#images">Images</a>
</nav>

<!-- ⭐ STARS -->
<div class="star" style="top:10%; left:20%;"></div>
<div class="star" style="top:30%; left:70%;"></div>
<div class="star" style="top:50%; left:40%;"></div>
<div class="star" style="top:80%; left:10%;"></div>
<div class="star" style="top:60%; left:90%;"></div>

<!-- 💰 COINS -->
<img class="coin" style="left:20%;" src="https://upload.wikimedia.org/wikipedia/commons/4/4a/Mario_Coin.png">
<img class="coin" style="left:60%; animation-delay:2s;" src="https://upload.wikimedia.org/wikipedia/commons/4/4a/Mario_Coin.png">

<!-- 🍄 MARIO -->
<img class="mario" src="https://upload.wikimedia.org/wikipedia/en/a/a9/MarioNSMBUDeluxe.png">

<section id="overview">
<h2>🚀 What Happened?</h2>
<p>
The Space Race was a Cold War competition between the United States and the Soviet Union.
It began in 1957 with Sputnik.
</p>
<ul>
<li>1957 – Sputnik launched</li>
<li>1961 – Yuri Gagarin in space</li>
<li>1969 – Moon landing</li>
</ul>
</section>

<section id="tensions">
<h2>🔥 Tensions</h2>
<p>
The Space Race increased tensions by creating competition and fear between both nations.
</p>
</section>

<section id="impact">
<h2>🌎 Impact</h2>
<p><b>USA:</b> Advanced technology and won Moon landing.</p>
<p><b>USSR:</b> Early success but later fell behind.</p>
</section>

<section id="significance">
<h2>⭐ Significance</h2>
<p>
It led to major scientific advancements and symbolized Cold War rivalry.
</p>
</section>

<section id="concepts">
<h2>🎯 Concepts</h2>
<ul>
<li>Containment</li>
<li>Expansionism</li>
<li>Brinkmanship</li>
<li>Deterrence</li>
<li>Alignment</li>
</ul>
</section>

<section id="images">
<h2>🖼️ Images</h2>

<div class="image-box">
<img src="https://upload.wikimedia.org/wikipedia/commons/b/be/Sputnik_asm.jpg">
<p>Sputnik – first satellite</p>
</div>

<div class="image-box">
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a1/Aldrin_Apollo_11.jpg">
<p>Moon Landing – U.S. victory</p>
</div>

</section>

<footer>🍄 Mario + History = Power-Up Learning ⭐</footer>

</body>
</html>  show me a preview of this code
