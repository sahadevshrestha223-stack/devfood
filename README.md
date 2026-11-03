<!DOCTYPE html>
<html lang="ne">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dev Foods & Organic</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f5f5f5;
}

header{
background:#ff6b00;
padding:15px 50px;
display:flex;
justify-content:space-between;
align-items:center;
color:white;
}

.logo{
font-size:28px;
font-weight:bold;
}

.menu a{
color:white;
text-decoration:none;
margin-left:20px;
}

.hero{
background:linear-gradient(rgba(0,0,0,.4),rgba(0,0,0,.4)),
url('9d1feaa7-f94d-4232-b242-b33fea81c270.png');
background-size:cover;
background-position:center;
height:500px;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
color:white;
text-align:center;
}

.hero h1{
font-size:55px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
margin-bottom:20px;
}

.search{
width:80%;
max-width:700px;
padding:15px;
border:none;
border-radius:30px;
font-size:18px;
}

.categories{
padding:50px 20px;
text-align:center;
}

.categories h2{
margin-bottom:30px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 3px 10px rgba(0,0,0,.1);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card h3{
padding:15px;
}

.card p{
padding:0 15px 15px;
}

.btn{
display:inline-block;
background:#25D366;
color:white;
padding:12px 25px;
margin-bottom:20px;
text-decoration:none;
border-radius:8px;
}

footer{
background:#222;
color:white;
text-align:center;
padding:30px;
margin-top:40px;
}
</style>

</head>
<body>

<header>
<div class="logo">Dev Foods</div>

<nav class="menu">
<a href="#">Home</a>
<a href="#">Products</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">
<h1>पुरानो स्वाद, शुद्ध परम्परा</h1>
<p>सातु, कुकीज र अर्गानिक खाद्य सामग्री</p>

<input class="search" type="text"
placeholder="उत्पादन खोज्नुहोस्...">
</section>

<section class="categories">

<h2>हाम्रा लोकप्रिय उत्पादनहरू</h2>

<div class="grid">

<div class="card">
<img src="9d1feaa7-f94d-4232-b242-b33fea81c270.png">
<h3>Dev Satu</h3>
<p>घ्यू मिसाएर खाने परम्परागत सातु</p>
<a href="#" class="btn">Order Now</a>
</div>

<div class="card">
<img src="watermarked_img_3341172175323745100.jpg">
<h3>Cookies</h3>
<p>पुरानो स्वादका स्वादिष्ट Cookies</p>
<a href="#" class="btn">Order Now</a>
</div>

</div>

</section>

<footer>
<h3>Dev Foods & Organic</h3>
<p>WhatsApp: 9849638583</p>
<p>devfood.com.np</p>
</footer>

</body>
</html>
