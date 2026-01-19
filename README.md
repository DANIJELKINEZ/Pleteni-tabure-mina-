# Pleteni-tabure-mina-
Pletenitaburemina 
<!DOCTYPE html>
<html lang="sr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pleteni tabure MINA | Jagodina</title>
    <meta name="description" content="Ručno pleteni taburei, sedalice i jastuci. Poručite unikatni nameštaj direktno iz Jagodine.">
    <style>
        :root {
            --primarna: #8d6e63; 
            --akcent: #d32f2f;  
            --pozadina: #fdfaf7;
            --tekst: #2d2d2d;
            --whatsapp: #25d366;
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--pozadina);
            color: var(--tekst);
            line-height: 1.6;
        }

        header {
            background-color: #fff;
            text-align: center;
            padding: 60px 20px;
            border-bottom: 2px solid #eee;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        h1 { color: var(--primarna); margin-bottom: 10px; font-size: 2.5em; text-transform: uppercase; letter-spacing: 2px; }
        .location-tag { color: #777; font-size: 1em; margin-bottom: 20px; font-weight: bold; }

        /* Kartice proizvoda */
        .product-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 30px;
            margin-top: 40px;
        }

        .card {
            background: #fff;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
            text-align: center;
            padding-bottom: 25px;
            transition: transform 0.3s ease;
        }

        .card:hover { transform: translateY(-5px); }

        .card img {
            width: 100%;
            height: 450px;
            object-fit: cover;
        }

        .card h3 { margin: 20px 0 10px; color: var(--primarna); font-size: 1.5em; }
        .price { font-size: 1.6em; font-weight: bold; margin-bottom: 20px; color: #000; }

        /* Dugmići */
        .btn {
            display: inline-block;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: 0.3s;
            margin: 5px;
            border: none;
            cursor: pointer;
        }

        .btn-wa { background-color: var(--whatsapp); color: white; width: 85%; font-size: 1.1em; }
        .btn-wa:hover { background-color: #1ebd59; box-shadow: 0 5px 15px rgba(37, 211, 102, 0.4); }
        
        .btn-google { background-color: var(--primarna); color: white; margin-top: 20px; }

        .contact-box {
            background: #fff;
            padding: 40px;
            border-radius: 20px;
            text-align: center;
            margin: 60px 0;
            border: 1px solid #eee;
        }

        /* Sekcija sa recenzijom (slika poruke) */
        .testimonial-img {
            max-width: 100%;
            border-radius: 15px;
            margin: 20px 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        footer {
            text-align: center;
            padding: 50px;
            font-size: 0.9em;
            color: #777;
            background: #f4efeb;
        }

        @media (min-width: 768px) {
            .product-grid { grid-template-columns: 1fr 1fr; }
        }
    </style>
</head>
<body>

<header>
    <h1>Pleteni tabure MINA</h1>
    <div class="location-tag">📍 Glogovac, Jagodina | 📞 064 126 2704</div>
    <p>Ručno pleteni unikatni komadi koji unose toplinu i luksuz u vaš dom.</p>
</header>

<div class="container">

    <div class="product-grid">
        <div class="card">
            <img src="glavna-slika.jpg" alt="Pleteni tabure bež">
            <h3>Pleteni Tabure - Model L</h3>
            <p>Ručni rad od pamučnog konca, punjenje visoke gustine.</p>
            <div class="price">7.000 RSD</div>
            <a href="https://wa.me/381641262704?text=Zdravo, interesuje me pleteni tabure" class="btn btn-wa">Poruči preko WhatsApp-a</a>
        </div>

        <div class="card">
            <img src="tabure-set.jpg" alt="Set pletenih taburea">
            <h3>Pletene Sedalice i Jastuci</h3>
            <p>Dimenzije i boje po vašoj meri i želji.</p>
            <div class="price">1.200 RSD</div>
            <a href="https://wa.me/381641262704?text=Zdravo, interesuju me pletene sedalice" class="btn btn-wa">Poruči preko WhatsApp-a</a>
        </div>
    </div>

    <div class="contact-box">
        <h3>Utisci naših kupaca</h3>
        <img src="recenzija.jpg" alt="Zadovoljan kupac recenzija" class="testimonial-img">
        <p>Pridružite se stotinama zadovoljnih vlasnika Mina pletenina.</p>
        <a href="https://g.page/r/CWWr6rbfGxfpEBI/review" class="btn btn-google">Ostavi recenziju na Google-u</a>
    </div>

</div>

<footer>
    <p>© 2026 Pleteni tabure MINA. Sva prava zadržana.<br>
    Brza dostava Post Expressom na teritoriji cele Srbije. 🇷🇸</p>
</footer>

</body>
</html>
