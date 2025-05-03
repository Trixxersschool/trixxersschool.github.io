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
                <option value="flashpaper 7€">Tricks with Flashpaper - 7€</option>
                <option value="smoke - 3€">Producing smoke trick - 3€</option>
            </select><br><br>

            <label for="payment">Payment Option:</label><br>
            <select id="payment" name="payment">
                <option value="bank">Send money via bank transfer</option>
                <option value="post">Send money via postal services</option>
            </select><br><br>

            <label for="Email">Email (Email):</label><br>
            <input type="email" id="email" name="Email" required><br><br>

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

/* Allgemeine Stile */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f9;
    color: #333;
}

/* Überschriften */
h1, h2 {
    text-align: center;
    color: #444;
}

/* Container-Stile */
.div1, .div2, .div3, .div4, .div5 {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

/* Listen */
ul {
    list-style-type: disc;
    margin-left: 20px;
}

/* Formular-Stile */
form {
    display: flex;
    flex-direction: column;
}

label {
    font-weight: bold;
    margin-bottom: 5px;
}

input[type="text"],
input[type="email"],
select,
textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
}

textarea {
    resize: vertical;
    height: 100px;
}

input[type="submit"] {
    background-color: #5cb85c;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
}

input[type="submit"]:hover {
    background-color: #4cae4c;
}

/* Footer */
.div4 {
    text-align: center;
    font-size: 14px;
    color: #666;
}
