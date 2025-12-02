desvende-sua-estrada/
│
├── index.html
├── baralho.html
├── carta-dia.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
└── img/
    ├── floral-bg.jpg
    └── cartas/ (caso queira adicionar imagens reais depois)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desvende Sua Estrada</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

<header>
    <h1>Desvende Sua Estrada</h1>
    <nav>
        <a href="index.html">Início</a>
        <a href="baralho.html">Baralho Cigano</a>
        <a href="carta-dia.html">Carta do Dia</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-text">
        <h2>DESVENDE SUA ESTRADA</h2>
        <p>Os símbolos revelam caminhos. Você escolhe seguir.</p>
        <a class="btn" href="baralho.html">Explorar o Baralho Cigano</a>
    </div>
</section>

<section class="sobre">
    <h3>A Jornada</h3>
    <p>
        O Baralho Cigano é um conjunto simbólico capaz de inspirar reflexões profundas.
        Aqui você encontra interpretações poéticas e simbólicas para orientar sua estrada interior.
    </p>
</section>

<footer>
    <p>© 2025 — Desvende Sua Estrada</p>
</footer>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baralho Cigano</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

<header>
    <h1>Desvende Sua Estrada</h1>
    <nav>
        <a href="index.html">Início</a>
        <a href="baralho.html" class="ativo">Baralho Cigano</a>
        <a href="carta-dia.html">Carta do Dia</a>
    </nav>
</header>

<section class="cartas-section">
    <h2>O Baralho Cigano</h2>

    <div class="grid">

        <div class="carta">
            <h4>1. O Cavaleiro</h4>
            <p>Movimento, avanço, chegada de notícias.</p>
        </div>

        <div class="carta">
            <h4>2. O Trevo</h4>
            <p>Pequenas oportunidades e sorte súbita.</p>
        </div>

        <div class="carta">
            <h4>3. O Navio</h4>
            <p>Viagens, transições, expansão.</p>
        </div>

        <div class="carta">
            <h4>4. A Casa</h4>
            <p>Estabilidade, lar, estrutura emocional.</p>
        </div>

        <div class="carta">
            <h4>22. Os Caminhos</h4>
            <p>Escolhas, novas direções.</p>
        </div>

        <div class="carta">
            <h4>33. A Chave</h4>
            <p>Abertura, solução, resposta que se revela.</p>
        </div>

        <div class="carta">
            <h4>24. O Coração</h4>
            <p>Amor, sinceridade, verdade emocional.</p>
        </div>

        <div class="carta">
            <h4>30. Os Lírios</h4>
            <p>Harmonia, pureza, calma interior.</p>
        </div>

        <div class="carta">
            <h4>31. O Sol</h4>
            <p>Força, brilho, realização.</p>
        </div>
        
    </div>
</section>

<footer>
    <p>© 2025 — Desvende Sua Estrada</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carta do Dia</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

<header>
    <h1>Desvende Sua Estrada</h1>
    <nav>
        <a href="index.html">Início</a>
        <a href="baralho.html">Baralho Cigano</a>
        <a href="carta-dia.html" class="ativo">Carta do Dia</a>
    </nav>
</header>

<section class="carta-dia">
    <h2>Carta do Dia</h2>
    <p>Clique no botão e permita que uma carta simbólica ilumine sua estrada.</p>

    <button class="btn" onclick="revelarCarta()">Revelar Carta</button>

    <div id="resultado"></div>
</section>

<footer>
    <p>© 2025 — Desvende Sua Estrada</p>
</footer>

<script src="js/script.js"></script>
</body>
</html>
/* Fundo Floral */
body {
    margin: 0;
    background: black url("https://i.imgur.com/aVv9yx2.jpeg") no-repeat center/cover;
    font-family: "Cinzel", serif;
    color: white;
}

/* Header */
header {
    text-align: center;
    padding: 25px;
    border-bottom: 2px solid #d4af37;
    background: rgba(0,0,0,0.85);
}

header h1 {
    color: #d4af37;
    margin: 0;
    font-size: 40px;
}

nav a {
    color: #d4af37;
    margin: 0 20px;
    text-decoration: none;
    font-size: 18px;
}

nav a:hover, nav a.ativo {
    color: #8A0E1B;
}

/* Hero */
.hero {
    height: 70vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: rgba(0,0,0,0.65);
    text-align: center;
}

.hero-text h2 {
    font-size: 55px;
    color: #d4af37;
}

.btn {
    background: #8A0E1B;
    color: #d4af37;
    padding: 12px 25px;
    border: 2px solid #d4af37;
    font-size: 20px;
    text-decoration: none;
    display: inline-block;
    margin-top: 20px;
}

.btn:hover {
    background: #d4af37;
    color: black;
}

/* Cartas */
.cartas-section {
    padding: 50px 0;
    background: rgba(0,0,0,0.7);
    text-align: center;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    padding: 20px;
}

.carta {
    background: black;
    border: 2px solid #d4af37;
    padding: 20px;
    color: #d4af37;
    border-radius: 10px;
}

/* Carta do Dia */function revelarCarta() {
    const cartas = [
        "O Cavaleiro — movimento e avanços.",
        "O Trevo — pequenas oportunidades.",
        "O Navio — mudanças e jornadas.",
        "A Casa — segurança e estabilidade.",
        "Os Caminhos — escolhas e novas direções.",
        "A Chave — solução e abertura.",
        "O Coração — amor e sinceridade.",
        "Os Lírios — paz e pureza.",
        "O Sol — força e brilho."
    ];

    const sorteio = cartas[Math.floor(Math.random() * cartas.length)];
    document.getElementById("resultado").innerHTML = sorteio;
}

.carta-dia {
    padding: 50px;
    text-align: center;
    background: rgba(0,0,0,0.7);
}

#resultado {
    color: #d4af37;
    font-size: 26px;
    margin-top: 25px;
}

/* Footer */
footer {
    background: black;
    border-top: 2px solid #d4af37;
    text-align: center;
    padding: 15px;
}

</body>
</html>
