<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Notre histoire ❤️</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    background: #08070b;
    color: #f8edf1;
    font-family: Georgia, serif;
    overflow-x: hidden;
}

header {
    padding: 22px 10px;
    text-align: center;
    color: #e5c27a;
    letter-spacing: 4px;
    font-size: 15px;
    background: #100d14;
    border-bottom: 1px solid #62462c;
}

.hero {
    min-height: 90vh;
    padding: 80px 22px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    background:
        radial-gradient(circle at top, #63263c 0%, transparent 55%),
        linear-gradient(145deg, #100b13, #24101e, #09070c);
}

.hero .eyebrow {
    color: #e5c27a;
    letter-spacing: 5px;
    font-size: 12px;
    margin-bottom: 25px;
}

.heart {
    font-size: 45px;
    color: #ff668a;
    animation: heartbeat 1.3s infinite;
    margin-bottom: 20px;
}

.hero h1 {
    font-size: clamp(38px, 9vw, 60px);
    line-height: 1.25;
    color: #f0cf89;
    text-shadow: 0 0 30px #d9a85b55;
    margin-bottom: 25px;
}

.hero p {
    max-width: 520px;
    color: #eadce4;
    font-size: 18px;
    line-height: 2;
}

button {
    border: none;
    background: linear-gradient(135deg, #f0d18c, #b98742);
    color: #160d12;
    padding: 15px 27px;
    border-radius: 30px;
    font-size: 15px;
    font-weight: bold;
    margin-top: 25px;
    cursor: pointer;
    transition: .3s;
}

button:active {
    transform: scale(.95);
}

.section {
    max-width: 760px;
    padding: 70px 22px;
    margin: auto;
    text-align: center;
}

.section h2 {
    color: #e7c47d;
    font-size: 30px;
    margin-bottom: 20px;
}

.subtitle {
    color: #cbbbc5;
    font-size: 16px;
    line-height: 1.9;
    margin-bottom: 28px;
}

.card {
    background: linear-gradient(145deg, #211722, #110f16);
    border: 1px solid #725335;
    border-radius: 20px;
    padding: 30px 23px;
    margin-top: 23px;
    color: #f2e8ee;
    font-size: 17px;
    line-height: 2;
    box-shadow: 0 12px 35px #0008;
}

.gold {
    color: #e9c77e;
}

.music-box {
    background: linear-gradient(145deg, #281523, #120e17);
    padding: 24px 16px;
    border-radius: 22px;
    border: 1px solid #a17a45;
    box-shadow: 0 0 35px #a36b3820;
}

.music-box iframe {
    width: 100%;
    height: 220px;
    border: none;
    border-radius: 12px;
}

.counter {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
    margin-top: 25px;
}

.counter div {
    background: #20151f;
    border: 1px solid #75532f;
    border-radius: 15px;
    padding: 18px 20px;
    min-width: 85px;
}

.counter strong {
    display: block;
    color: #f0cb7d;
    font-size: 28px;
}

.counter span {
    color: #d7c3cf;
    font-size: 12px;
}

.envelope {
    background: #19131c;
    border: 1px solid #725335;
    border-radius: 15px;
    margin: 18px 0;
    text-align: left;
    overflow: hidden;
}

.envelope summary {
    padding: 22px;
    color: #e8c47b;
    font-size: 17px;
    cursor: pointer;
    list-style: none;
}

.envelope summary::after {
    content: "＋";
    float: right;
}

.envelope[open] summary::after {
    content: "−";
}

.envelope p {
    padding: 5px 22px 25px;
    color: #eee1e9;
    font-size: 16px;
    line-height: 2;
}

.gift {
    font-size: 90px;
    cursor: pointer;
    display: inline-block;
    margin: 25px;
    transition: .4s;
}

.gift:active {
    transform: scale(1.2) rotate(-10deg);
}

#giftMessage {
    display: none;
}

.final {
    background: linear-gradient(145deg, #321725, #100d14);
    border-top: 1px solid #725335;
    border-bottom: 1px solid #725335;
    max-width: none;
}

.final .card {
    max-width: 600px;
    margin: 25px auto;
}

footer {
    background: #100d14;
    color: #d8b66f;
    text-align: center;
    padding: 35px 15px;
    line-height: 2;
    letter-spacing: 2px;
}

.floating {
    position: fixed;
    bottom: -30px;
    color: #ff668a;
    pointer-events: none;
    animation: floatUp 7s linear forwards;
    z-index: 10;
}

.sparkle {
    position: fixed;
    pointer-events: none;
    animation: sparkle .9s forwards;
    z-index: 100;
}

@keyframes heartbeat {
    50% { transform: scale(1.25); }
}

@keyframes floatUp {
    to {
        transform: translateY(-110vh) rotate(360deg);
        opacity: 0;
    }
}

@keyframes sparkle {
    to {
        transform: translateY(-50px) scale(0);
        opacity: 0;
    }
}

@media(max-width: 450px) {
    .section {
        padding: 55px 17px;
    }

    .card {
        padding: 24px 18px;
    }
}
</style>
</head>

<body>

<header>
    OUR LOVE STORY ❤️
</header>

<section class="hero">

    <div class="heart">♥</div>

    <p class="eyebrow">UNE HISTOIRE • DEUX CŒURS</p>

    <h1>Notre petit univers</h1>

    <p>
        Certaines histoires commencent simplement,
        mais deviennent peu à peu une partie
        précieuse de notre vie.

        Aujourd'hui, j'ai créé ce petit monde
        pour célébrer la nôtre.
    </p>

    <button onclick="document.getElementById('music').scrollIntoView()">
        Entrer dans notre univers ✨
    </button>

</section>

<section class="section">

    <h2>Cinq mois de nous ❤️</h2>

    <p class="subtitle">
        Depuis le 10 juillet 2026,
        une belle histoire continue de s'écrire.
    </p>

    <div class="card">
        Cinq mois de souvenirs, de sourires,
        de découvertes et de moments précieux.

        <br><br>

        Ce n'est peut-être que le début,
        mais chaque jour donne une nouvelle
        page à notre histoire.

        <br><br>

        <span class="gold">
            Joyeux cinq mois, mon amour. ❤️
        </span>
    </div>

    <div class="counter">
        <div>
            <strong id="days">000</strong>
            <span>JOURS</span>
        </div>

        <div>
            <strong id="hours">00</strong>
            <span>HEURES</span>
        </div>

        <div>
            <strong id="minutes">00</strong>
            <span>MINUTES</span>
        </div>

        <div>
            <strong id="seconds">00</strong>
            <span>SECONDES</span>
        </div>
    </div>

</section>

<section class="section" id="music">

    <h2>Notre chanson 🎶</h2>

    <p class="subtitle">
        Une mélodie pour accompagner
        ce petit moment rien qu'à nous.
    </p>

    <div class="music-box">

        <iframe
            src="https://www.youtube.com/embed/lYlpjHCJACU"
            title="Notre chanson d'amour"
            allow="autoplay; encrypted-media; picture-in-picture"
            allowfullscreen>
        </iframe>

    </div>

    <p class="subtitle" style="margin-top:20px">
        Ferme les yeux un instant,
        écoute et profite de ce moment. ❤️
    </p>

</section>

<section class="section">

    <h2>Des lettres pour toi 💌</h2>

    <p class="subtitle">
        Chaque enveloppe cache quelques mots
        que j'aimerais te laisser découvrir.
    </p>

    <details class="envelope">
        <summary>💌 Première lettre — Une pensée</summary>
        <p>
            Il y a des personnes qui arrivent
            dans notre vie et qui changent
            doucement notre façon de voir les choses.

            Tu fais partie de ces personnes.
            Même à distance, une simple pensée
            de toi peut illuminer ma journée.
        </p>
    </details>

    <details class="envelope">
        <summary>❤️ Deuxième lettre — Ce que tu représentes</summary>
        <p>
            Tu représentes une présence précieuse,
            une douceur et une raison de sourire.

            Je ne veux jamais considérer
            les petits moments comme acquis,
            car ce sont souvent eux qui rendent
            une histoire inoubliable.
        </p>
    </details>

    <details class="envelope">
        <summary>🌹 Troisième lettre — Mon souhait</summary>
        <p>
            Je souhaite que notre histoire
            grandisse avec le respect,
            la confiance, la patience
            et la compréhension.

            Je veux que nous apprenions
            toujours à mieux nous aimer.
        </p>
    </details>

    <details class="envelope">
        <summary>💍 Quatrième lettre — Pour demain</summary>
        <p>
            Je ne connais pas encore tous
            les chemins que la vie nous réserve.

            Mais j'espère que nous continuerons
            à avancer ensemble, à construire
            nos rêves et à créer des souvenirs
            dont nous serons fiers.
        </p>
    </details>

</section>

<section class="section">

    <h2>Une petite surprise 🎁</h2>

    <p class="subtitle">
        Il y a quelque chose qui t'attend.
        Touche le cadeau pour le découvrir.
    </p>

    <div class="gift" onclick="openGift()">🎁</div>

    <div class="card" id="giftMessage">

        <h2>Surprise, Manmi ! ❤️</h2>

        Si je pouvais t'offrir quelque chose
        aujourd'hui, ce serait la possibilité
        de voir à quel point tu es précieuse.

        <br><br>

        Je te souhaite de toujours garder
        cette belle lumière qui te caractérise.

        <br><br>

        Merci pour ces cinq mois.
        Ce petit univers est une façon
        de te dire que tu comptes énormément
        pour moi.

        <br><br>

        <span class="gold">
            Je t'aime, mon amour. ❤️
        </span>

    </div>

</section>

<section class="section final">

    <h2>À toi, Manmi ❤️</h2>

    <div class="card">

        Cinq mois se sont écoulés,
        et j'espère que beaucoup d'autres
        belles pages nous attendent.

        <br><br>

        Je ne te promets pas une histoire parfaite.
        Je veux une histoire sincère,
        dans laquelle nous saurons nous écouter,
        nous respecter et nous choisir chaque jour.

        <br><br>

        Merci d'être une partie
        de mon histoire.

        <br><br>

        <span class="gold">
            Joyeux cinq mois, mon amour.
        </span>

        <h2 style="margin-top:30px">
            Ton Papi ❤️
        </h2>

    </div>

</section>

<footer>
    CRÉÉ AVEC AMOUR ❤️

    <br>

    10 JUILLET — 10 NOVEMBRE 2026

    <br>

    OUR LOVE STORY
</footer>

<script>

const startDate = new Date(2026, 6, 10, 0, 0, 0);

function updateCounter() {

    const now = new Date();

    let difference = now - startDate;

    if (difference < 0) difference = 0;

    const seconds = Math.floor(difference / 1000);

    document.getElementById("days").textContent =
        Math.floor(seconds / 86400);

    document.getElementById("hours").textContent =
        Math.floor((seconds % 86400) / 3600);

    document.getElementById("minutes").textContent =
        Math.floor((seconds % 3600) / 60);

    document.getElementById("seconds").textContent =
        seconds % 60;
}

updateCounter();
setInterval(updateCounter, 1000);

function openGift() {

    const message = document.getElementById("giftMessage");

    message.style.display = "block";

    message.scrollIntoView({
        behavior: "smooth",
        block: "center"
    });

    createSparkles();
}

function createSparkles() {

    for (let i = 0; i < 20; i++) {

        const sparkle = document.createElement("span");

        sparkle.className = "sparkle";

        sparkle.textContent = "✨";

        sparkle.style.left = Math.random() * 100 + "vw";

        sparkle.style.top = Math.random() * 100 + "vh";

        document.body.appendChild(sparkle);

        setTimeout(() => sparkle.remove(), 1000);
    }
}

document.addEventListener("click", function(e) {

    if (e.target.closest("button") ||
        e.target.closest(".gift")) {
        createSparkles();
    }

});

setInterval(function() {

    const heart = document.createElement("div");

    heart.className = "floating";

    heart.textContent = Math.random() > 0.5 ? "♥" : "♡";

    heart.style.left = Math.random() * 100 + "vw";

    heart.style.fontSize = (15 + Math.random() * 20) + "px";

    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 7000);

}, 1000);

</script>

</body>
</html>
