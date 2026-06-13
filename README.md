# poweerrangerszentrale
Getränkekarte und Spendenlink
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>⚡ Powerrangerszentrale ⚡</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: Arial, sans-serif;
    color:white;
    background:linear-gradient(-45deg,#ff0000,#0055ff,#00b140,#ffd700,#ff69b4);
    background-size:400% 400%;
    animation:gradient 12s ease infinite;
    min-height:100vh;
}

@keyframes gradient{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

.container{
    max-width:900px;
    margin:auto;
    padding:20px;
}

.hero{
    text-align:center;
    background:rgba(0,0,0,.8);
    border:4px solid gold;
    border-radius:20px;
    padding:30px;
    box-shadow:0 0 25px gold;
    margin-bottom:20px;
}

.hero h1{
    font-size:3rem;
    text-transform:uppercase;
    margin-bottom:10px;
}

.hero p{
    font-size:1.2rem;
}

.card{
    background:rgba(0,0,0,.82);
    border-radius:20px;
    padding:25px;
    margin-bottom:20px;
    border:2px solid rgba(255,255,255,.3);
}

.card h2{
    color:gold;
    margin-bottom:15px;
}

ul{
    list-style:none;
}

li{
    padding:10px;
    margin-bottom:6px;
    background:rgba(255,255,255,.08);
    border-radius:10px;
}

.rangers{
    display:flex;
    justify-content:center;
    gap:10px;
    margin:20px 0;
    flex-wrap:wrap;
}

.ranger{
    width:50px;
    height:50px;
    border-radius:50%;
    border:3px solid white;
}

.red{background:red;}
.blue{background:#0055ff;}
.green{background:#00b140;}
.yellow{background:#ffd700;}
.pink{background:#ff69b4;}

.donate{
    text-align:center;
}

.paypal-btn{
    display:inline-block;
    margin-top:15px;
    padding:15px 25px;
    background:#0070ba;
    color:white;
    text-decoration:none;
    border-radius:10px;
    font-size:18px;
    font-weight:bold;
}

.paypal-btn:hover{
    transform:scale(1.05);
}

.qr-box{
    margin:20px auto;
    max-width:250px;
    background:white;
    color:black;
    padding:20px;
    border-radius:15px;
}

.footer{
    text-align:center;
    padding:20px;
    font-weight:bold;
}
</style>
</head>

<body>

<div class="container">

<div class="hero">
    <h1>⚡ POWERRANGERSZENTRALE ⚡</h1>
    <p>IT'S MORPHIN TIME!</p>

    <div class="rangers">
        <div class="ranger red"></div>
        <div class="ranger blue"></div>
        <div class="ranger green"></div>
        <div class="ranger yellow"></div>
        <div class="ranger pink"></div>
    </div>
</div>

<div class="card">
    <h2>🥤 Softdrinks & Energy</h2>
    <ul>
        <li>Cola</li>
        <li>Sprite</li>
        <li>Fanta</li>
        <li>Cola Vanille</li>
        <li>Fassbrause Zitrone</li>
        <li>Fassbrause Apfel</li>
        <li>Monster White Zero</li>
        <li>Monster Grün</li>
        <li>Red Bull Grün</li>
        <li>Red Bull Sugarfree</li>
    </ul>
</div>

<div class="card">
    <h2>💧 Wasser</h2>
    <ul>
        <li>Brita Wasser Still</li>
        <li>Brita Wasser Still (gekühlt)</li>
        <li>Brita Wasser Sprudel</li>
    </ul>
</div>

<div class="card donate">
    <h2>❤️ Freiwillige Spende</h2>

    <p>
        Wenn euch der Abend gefällt und ihr die
        Powerrangerszentrale unterstützen möchtet,
        freuen wir uns über eine kleine Spende.
    </p>

    <a class="paypal-btn"
       href="https://paypal.me/JenAu6797"
       target="_blank">
       💙 Mit PayPal spenden
    </a>

    <div class="qr-box">
        <strong>QR-Code hier einfügen</strong><br><br>
        Nutze einen QR-Code für:<br>
        https://paypal.me/JenAu6797
    </div>
</div>

<div class="footer">
    ⚡ Möge die Ranger-Power mit eurem Durst sein! 🍻 ⚡
</div>

</div>

</body>
</html>
