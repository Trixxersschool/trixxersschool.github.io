<html lang="english">
<head>
    <link rel="stylesheet" href="Trixxersstyle.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trixxersschool</title>
</head>
<body>
    <div class="div1">
        <h1>Welcome to the Website of Trixxersschool</h1>
    </div>
    <div class="div2">
        <p>We will teach you magic tricks for a low price. You will become a real trixxer</p>
    </div>
    <div class="div3">
        <h2>Our Tricks</h2>
        <ul>
            <li>Card Trick</li>
            <li>Coin Trick</li>
            <li>Telepathy Trick</li>
            <li>Tricks with Flashpaper</li>
            <li>Producing smoke trick</li>
        </ul>
    </div>
    <div class="div5">
        <h2>Order Tricks</h2>
        <form name="order tricks" action="https://formspree.io/f/xgvkapnw" method="POST">
            <label for="trick">Choose a trick:</label><br>
            <select id="trick" name="trick">
                <option value="card - 5€">Card Trick - 5€</option>
                <option value="coin - 5€">Coin Trick - 5€</option>
                <option value="telepathy - 7€">Telepathy Trick - 7€</option>
                <option value="flashpaper - 7€">Tricks with Flashpaper - 7€</option>
                <option value="smoke - 3€">Producing smoke trick - 3€</option>
            </select><br>
            <label for="Kontakt">Contact:</label><br>
            <input type="text" id="Kontakt" name="Kontakt"><br>
            <label for="payment">Payment Option:</label><br>
            <select id="payment" name="payment">
                <option value="bank">Send money via bank transfer</option>
                <option value="post">Send money via postal services</option>
            </select><br>
            <input type="submit" value="Order">
        </form>
    </div>
    <div class="div4">
        <h2>Contact us</h2>
        <form action="mailto:trixxersschool@gmail.com" method="email" enctype="text/plain">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="Submit">
        </form>
    </div>
</body>
</html>
