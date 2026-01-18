#R-govind-general-store-
<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>R Govind General Store</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#f2f2f2;
}
header{
    background:#2e7d32;
    color:white;
    padding:20px;
    text-align:center;
}
nav{
    background:#1b5e20;
    padding:10px;
    text-align:center;
}
nav a{
    color:white;
    text-decoration:none;
    margin:10px;
    font-weight:bold;
}
section{
    background:white;
    margin:15px;
    padding:20px;
    border-radius:10px;
}
h2{ color:#2e7d32; }

input, textarea, button{
    width:100%;
    padding:10px;
    margin-top:10px;
    border-radius:5px;
    border:1px solid #ccc;
}
button{
    background:#25D366;
    color:white;
    font-size:16px;
    border:none;
}

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
}

iframe{
    width:100%;
    height:250px;
    border:0;
    border-radius:10px;
}

footer{
    background:#2e7d32;
    color:white;
    text-align:center;
    padding:15px;
}
</style>

<script>
function sendOrder(){
    var name = document.getElementById("name").value;
    var address = document.getElementById("address").value;
    var order = document.getElementById("order").value;

    var message = "नया ऑर्डर%0Aनाम: " + name + "%0Aपता: " + address + "%0Aसामान: " + order;
    window.open("https://wa.me/918858384761?text=" + message);
}
</script>

</head>

<body>

<header>
<h1>R Govind General Store</h1>
<p>सभी दैनिक जरूरतों का भरोसेमंद स्टोर</p>
</header>

<nav>
<a href="#about">हमारे बारे में</a>
<a href="#order">ऑनलाइन ऑर्डर</a>
<a href="#contact">संपर्क</a>
</nav>

<section id="about">
<h2>हमारे बारे में</h2>
<p>
R Govind General Store पर आपको किराना, बिस्किट, नमकीन, ठंडे पेय,
घरेलू सामान और रोज़मर्रा की सभी चीज़ें उचित दामों पर मिलती हैं।
</p>
</section>

<section id="order">
<h2>🛒 ऑनलाइन ऑर्डर करें</h2>

<input type="text" id="name" placeholder="आपका नाम">
<input type="text" id="address" placeholder="पूरा पता">
<textarea id="order" placeholder="कौन-कौन सा सामान चाहिए"></textarea>

<button onclick="sendOrder()">WhatsApp पर ऑर्डर भेजें</button>
</section>

<section id="contact">
<h2>संपर्क करें</h2>
<p><b>दुकान:</b> R Govind General Store</p>
<p><b>फोन:</b> 8858384761</p>
<p><b>समय:</b> सुबह 7:00 – रात 10:30</p>

<h3>दुकान का स्थान</h3>
<iframe
src="https://www.google.com/maps?q=Chittasari+Sonkar+Basti+Jaunpur+UP+222001&z=17&output=embed">
</iframe>
</section>

<footer>
<p>© 2026 R Govind General Store</p>
</footer>

<a class="whatsapp" href="https://wa.me/918858384761" target="_blank">
WhatsApp
</a>

</body>
</html>
