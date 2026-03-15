<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Chocolate Room – Vizag</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins;
scroll-behavior:smooth;
}

body{
background:#fff7f0;
color:#3b1f1f;
}

/* NAVBAR */

nav{
position:fixed;
width:100%;
top:0;
background:#3b1f1f;
padding:18px 60px;
display:flex;
justify-content:space-between;
align-items:center;
z-index:1000;
}

nav h2{
color:#ff7a00;
font-family:Playfair Display;
}

nav a{
color:white;
margin-left:25px;
text-decoration:none;
font-weight:500;
}

nav a:hover{
color:#ff7a00;
}

/* HERO */

.hero{
height:100vh;
background:url("https://images.unsplash.com/photo-1509042239860-f550ce710b93") center/cover;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
}

.hero h1{
font-size:70px;
font-family:Playfair Display;
}

.hero p{
margin:20px 0;
font-size:20px;
}

.btn{
background:#ff7a00;
padding:14px 30px;
border-radius:40px;
color:white;
text-decoration:none;
}

/* SECTION */

.section{
padding:100px 10%;
text-align:center;
}

.section h2{
font-size:40px;
margin-bottom:40px;
font-family:Playfair Display;
}

/* MENU */

.menu-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.card{
background:white;
padding:30px;
border-radius:20px;
box-shadow:0 10px 30px rgba(0,0,0,.08);
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
}

.card h3{
margin-bottom:10px;
}

/* GALLERY */

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
border-radius:20px;
height:220px;
object-fit:cover;
}

/* FORM */

form{
max-width:500px;
margin:auto;
display:flex;
flex-direction:column;
gap:15px;
}

input,textarea{
padding:14px;
border-radius:10px;
border:1px solid #ddd;
}

button{
background:#ff7a00;
color:white;
border:none;
padding:14px;
border-radius:30px;
cursor:pointer;
}

/* FOOTER */

footer{
background:#3b1f1f;
color:white;
padding:40px;
text-align:center;
}

</style>
</head>

<body>

<nav>
<h2>🍫 TCR</h2>
<div>
<a href="#menu">Menu</a>
<a href="#gallery">Gallery</a>
<a href="#book">Reserve</a>
</div>
</nav>

<section class="hero">
<div>
<h1>Heaven For Chocolate Lovers</h1>
<p>Premium chocolates • Coffee • Cozy vibes</p>
<a class="btn" href="#menu">Explore Menu</a>
</div>
</section>

<section id="menu" class="section">
<h2>Popular Menu</h2>

<div class="menu-grid">

<div class="card">
<h3>TCR Brownie</h3>
<p>Warm brownie with vanilla ice cream</p>
</div>

<div class="card">
<h3>Hazelnut Hot Chocolate</h3>
<p>Creamy rich chocolate drink</p>
</div>

<div class="card">
<h3>Cappuccino</h3>
<p>Fresh espresso with milk foam</p>
</div>

<div class="card">
<h3>Garlic Bread</h3>
<p>Cheesy toasted garlic bread</p>
</div>

<div class="card">
<h3>Classic Desi Burger</h3>
<p>Juicy patty & signature sauce</p>
</div>

<div class="card">
<h3>Aglio Olio Pasta</h3>
<p>Italian pasta with olive oil & garlic</p>
</div>

</div>
</section>

<section id="gallery" class="section">
<h2>Our Cafe</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1554118811-1e0d58224f24">
<img src="https://images.unsplash.com/photo-1517685352821-92cf88aee5a5">
<img src="https://images.unsplash.com/photo-1521017432531-fbd92d768814">
<img src="https://images.unsplash.com/photo-1442512595331-e89e73853f31">

</div>
</section>

<section id="book" class="section">
<h2>Reserve Table</h2>

<form>
<input type="text" placeholder="Your Name" required>
<input type="tel" placeholder="Phone Number" required>
<input type="date" required>
<textarea placeholder="Message"></textarea>
<button>Book Now</button>
</form>

</section>

<footer>
<p>📍 MVP Colony, Vizag</p>
<p>☎ 08374869966</p>
<p>© 2026 The Chocolate Room</p>
</footer>

</body>
</html>
