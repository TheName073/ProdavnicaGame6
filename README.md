<!DOCTYPE html>
<html lang="bs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prodavnica Igara</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #6a0dad;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #6a0dad;
            padding: 10px 20px;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-around;
        }
        nav ul li {
            position: relative;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            display: block;
        }
        nav ul li:hover > ul {
            display: block;
        }
        nav ul li ul {
            display: none;
            position: absolute;
            background-color: white;
            color: #6a0dad;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        nav ul li ul li {
            margin: 5px 0;
        }
        nav ul li ul li a {
            color: #6a0dad;
        }
        .product {
            padding: 20px;
            margin: 10px auto;
            max-width: 800px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .product h3 {
            margin: 0 0 10px;
        }
        .product p {
            margin: 5px 0;
        }
        .pay-options {
            margin-top: 15px;
        }
        .pay-options a {
            margin: 0 5px;
            padding: 10px 15px;
            background-color: #6a0dad;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .pay-options a:hover {
            background-color: #8e44ad;
        }
    </style>
</head>
<body>
    <header>
        <h1>Prodavnica Igara</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Početna</a></li>
            <li>
                <a href="#">Igre</a>
                <ul>
                    <li><a href="#">Kategorija 1</a></li>
                    <li><a href="#">Kategorija 2</a></li>
                    <li><a href="#">Kategorija 3</a></li>
                </ul>
            </li>
            <li><a href="#">Kontakt</a></li>
        </ul>
    </nav>
    <main>
        <section id="products">
            <!-- Igra 1 -->
            <div class="product">
                <h3>Igra 1</h3>
                <p>Opis igre.</p>
                <div class="pay-options">
                    <a href="#">PayPal</a>
                    <a href="#">Binance</a>
                    <a href="#">Xbon</a>
                </div>
            </div>
            <!-- Ostale igre... -->
        </section>
    </main>
</body>
</html>
