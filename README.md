<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Munendr Yadav Digital Marketing Institute</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
</head>
<body>

<header>
    <h1>Munendr Yadav Digital Marketing Institute</h1>
    <p>3 दिन की Free Digital Marketing Class 🎓</p>
</header>

<section class="courses">
    <h2>आप क्या सीखेंगे?</h2>
    <ul>
        <li>✅ Facebook Ads चलाना</li>
        <li>✅ Instagram Growth बढ़ाना</li>
        <li>✅ Affiliate Marketing से कमाई करना</li>
    </ul>
</section>

<section class="offer">
    <h2>🎁 Free Offer!</h2>
    <p>सीखें Digital Marketing के रहस्य — बिल्कुल Free (3 दिन की Demo Class)</p>
    <p><b>सीट सीमित हैं, तुरंत रजिस्टर करें!</b></p>
</section>

<section class="contact">
    <h2>हमसे संपर्क करें</h2>
    <form class="contact-form" onsubmit="sendMessage(event)">
        <input type="text" id="name" placeholder="आपका नाम" required>
        <input type="email" id="email" placeholder="आपका ईमेल" required>
        <textarea id="message" rows="4" placeholder="अपना संदेश लिखें..." required></textarea>
        <button type="submit">भेजें</button>
    </form>
    <p id="response-message"></p>
</section>

<footer>
    <p>📞 Call / WhatsApp: <a href="https://wa.me/917505743286" target="_blank">7505743286</a></p>
    <p><a href="https://www.facebook.com" target="_blank">हमारे Facebook पेज पर जाएं</a></p>
    <p>© 2025 Munendr Yadav Digital Marketing Institute</p>
</footer>

</body>
</html># Ram-body {
    font-family: "Poppins", sans-serif;
    margin: 0;
    background-color: #fffbea;
    color: #333;
}

header {
    background: linear-gradient(90deg, #ff0000, #00ff00, #ffff00);
    text-align: center;
    padding: 20px;
    color: white;
}

header h1 {
    font-size: 24px;
    margin-bottom: 10px;
}

.courses, .offer, .contact {
    padding: 20px;
    text-align: center;
}

.courses ul {
    list-style: none;
    padding: 0;
}

.courses li {
    font-size: 18px;
    margin: 8px 0;
}

.offer {
    background-color: #fffae6;
    border: 2px solid #ffcc00;
    border-radius: 10px;
    margin: 20px;
    padding: 15px;
}

.contact-form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: auto;
}

.contact-form input, .contact-form textarea {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #bbb;
    border-radius: 8px;
    font-size: 16px;
}

.contact-form button {
    background-color: #ff0000;
    color: white;
    padding: 12px;
    font-size: 18px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: 0.3s;
}

.contact-form button:hover {
    background-color: #00b300;
}

footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
}

footer a {
    color: #00ff00;
    text-decoration: none;
}function sendMessage(event) {
    event.preventDefault();

    const name = document.getElementById("name").value;
    document.getElementById("response-message").innerText =
        `धन्यवाद ${name}! आपका संदेश सफलतापूर्वक भेज दिया गया है।`;

    document.querySelector(".contact-form").reset();
}
हम 3दिन फ्री में डिजिटल मार्केटिंग सिखाते हैं जिसमे मे सिखाया जाता है कि कैसे वेबसाइट बनाई जाती हैं और कोडिंग और सॉफ्टवेयर दोनो तरह की वेबसाइट 
