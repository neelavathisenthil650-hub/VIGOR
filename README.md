<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aroma Cafe</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
scroll-behavior:smooth;
}

body{
background:#faf5ef;
color:#333;
}

header{
background:#5c3d2e;
color:white;
padding:20px 10%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
}

header h1{
font-size:30px;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
font-weight:bold;
}

.hero{
height:90vh;
background:url("https://images.unsplash.com/photo-1509042239860-f550ce710b93") center/cover;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
}

.hero div{
background:rgba(0,0,0,.6);
padding:40px;
border-radius:10px;
}

.hero h2{
font-size:50px;
margin-bottom:15px;
}

.hero p{
font-size:20px;
margin-bottom:20px;
}

.btn{
display:inline-block;
padding:12px 30px;
background:#ff9800;
color:white;
text-decoration:none;
border-radius:30px;
}

section{
padding:70px 10%;
}

h2{
text-align:center;
margin-bottom:30px;
font-size:35px;
color:#5c3d2e;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
padding:25px;
border-radius:10px;
box-shadow:0 5px 10px rgba(0,0,0,.1);
text-align:center;
}

.card h3{
margin-bottom:10px;
}

.offer{
background:#ffeb3b;
}

.quality{
background:#8bc34a;
}

.review{
background:#ffe0b2;
}

iframe{
width:100%;
height:350px;
border:none;
border-radius:10px;
}

.whatsapp{
text-align:center;
}

.whatsapp a{
background:#25D366;
color:white;
padding:15px 30px;
text-decoration:none;
border-radius:30px;
font-size:20px;
}

footer{
background:#5c3d2e;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

@media(max-width:768px){

header{
flex-direction:column;
}

nav{
margin-top:15px;
}

.hero h2{
font-size:35px;
}

}
</style>

</head>
<body>

<header>

<h1>Aroma Cafe</h1>

<nav>
<a href="#menu">Menu</a>
<a href="#offers">Offers</a>
<a href="#quality">Quality</a>
<a href="#reviews">Reviews</a>
<a href="#map">Map</a>
<a href="#contact">WhatsApp</a>
</nav>

</header>

<section class="hero">

<div>

<h2>Welcome to Aroma Cafe</h2>

<p>Fresh Coffee • Delicious Food • Cozy Atmosphere</p>

<a href="#menu" class="btn">View Menu</a>

</div>

</section>

<section id="menu">

<h2>Our Menu</h2>

<div class="grid">

<div class="card">
<h3>☕ Cappuccino</h3>
<p>$4.00</p>
</div>

<div class="card">
<h3>🥤 Cold Coffee</h3>
<p>$5.00</p>
</div>

<div class="card">
<h3>🍔 Burger</h3>
<p>$6.00</p>
</div>

<div class="card">
<h3>🥪 Sandwich</h3>
<p>$4.50</p>
</div>

<div class="card">
<h3>🍕 Pizza</h3>
<p>$8.00</p>
</div>

<div class="card">
<h3>🍰 Chocolate Cake</h3>
<p>$3.50</p>
</div>

</div>

</section>

<section id="offers">

<h2>Today's Offers</h2>

<div class="grid">

<div class="card offer">
<h3>Buy 1 Get 1 Coffee</h3>
</div>

<div class="card offer">
<h3>20% Off Sandwich</h3>
</div>

<div class="card offer">
<h3>Free Cake with Family Combo</h3>
</div>

</div>

</section>

<section id="quality">

<h2>Why Choose Us?</h2>

<div class="grid">

<div class="card quality">
<h3>Fresh Ingredients</h3>
</div>

<div class="card quality">
<h3>Premium Coffee Beans</h3>
</div>

<div class="card quality">
<h3>Friendly Staff</h3>
</div>

</div>

</section>

<section id="reviews">

<h2>Customer Reviews</h2>

<div class="grid">

<div class="card review">
⭐⭐⭐⭐⭐
<p>Excellent coffee and amazing service.</p>
</div>

<div class="card review">
⭐⭐⭐⭐⭐
<p>Best cafe near our college.</p>
</div>

<div class="card review">
⭐⭐⭐⭐☆
<p>Cozy place with delicious snacks.</p>
</div>

</div>

</section>

<section id="map">

<h2>Find Us</h2>

<iframe
src="https://maps.google.com/maps?q=coffee%20shop&t=&z=13&ie=UTF8&iwloc=&output=embed">
</iframe>

</section>

<section id="contact" class="whatsapp">

<h2>Contact Us</h2>

<p><strong>Phone:</strong> +91 9876543210</p>

<br>

<a href="https://wa.me/919876543210">
Chat on WhatsApp
</a>

</section>

<footer>

<p>© 2025 Aroma Cafe. All Rights Reserved.</p>

</footer>

</body>
</html>
