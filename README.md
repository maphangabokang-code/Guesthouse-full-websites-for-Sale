<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Guesthouse Name</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:#f5f5f5;
color:#333;
}

header{
background:linear-gradient(135deg,#003049,#1d3557);
color:white;
padding:20px;
text-align:center;
}

header h1{
font-size:45px;
}

nav{
background:#00263a;
padding:15px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
font-weight:bold;
}

.hero{
height:90vh;
background:
linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
url('https://images.unsplash.com/photo-1566073771259-6a8506099945');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
color:white;
}

.hero h2{
font-size:60px;
}

.hero p{
font-size:22px;
margin:20px;
}

.btn{
background:#f4a261;
padding:15px 30px;
color:white;
text-decoration:none;
border-radius:30px;
font-weight:bold;
}

section{
padding:70px 10%;
}

.section-title{
text-align:center;
font-size:35px;
margin-bottom:40px;
color:#003049;
}

.rooms{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.room{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
text-align:center;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:15px;
}

.prices{
max-width:700px;
margin:auto;
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
}

.price-item{
display:flex;
justify-content:space-between;
padding:15px;
border-bottom:1px solid #ddd;
}

.contact{
background:#003049;
color:white;
padding:40px;
border-radius:15px;
text-align:center;
}

footer{
background:#00263a;
color:white;
text-align:center;
padding:20px;
}

</style>

</head>

<body>

<header>

<h1>YOUR GUESTHOUSE NAME</h1>

<p>Luxury • Comfort • Relaxation</p>

</header>

<nav>

<a href="#">Home</a>
<a href="#rooms">Rooms</a>
<a href="#gallery">Gallery</a>
<a href="#prices">Prices</a>
<a href="#contact">Contact</a>

</nav>

<section class="hero">

<h2>Welcome To Paradise</h2>

<p>Experience comfort and luxury at affordable prices.</p>

<a href="#contact" class="btn">
Book Your Stay
</a>

</section>

<section id="rooms">

<h2 class="section-title">Our Rooms</h2>

<div class="rooms">

<div class="room">
<h3>Standard Room</h3>
<p>Comfortable room with TV, Wi-Fi and private bathroom.</p>
</div>

<div class="room">
<h3>Deluxe Room</h3>
<p>Spacious room with balcony and luxury amenities.</p>
</div>

<div class="room">
<h3>Family Suite</h3>
<p>Perfect for families and group travellers.</p>
</div>

</div>

</section>

<section id="gallery">

<h2 class="section-title">Gallery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1566073771259-6a8506099945">

<img src="https://images.unsplash.com/photo-1578683010236-d716f9a3f461">

<img src="https://images.unsplash.com/photo-1582719508461-905c673771fd">

<img src="https://images.unsplash.com/photo-1445019980597-93fa8acb246c">

</div>

</section>

<section id="prices">

<h2 class="section-title">Room Prices</h2>

<div class="prices">

<div class="price-item">
<span>Standard Room</span>
<span>R _____ per night</span>
</div>

<div class="price-item">
<span>Deluxe Room</span>
<span>R _____ per night</span>
</div>

<div class="price-item">
<span>Family Suite</span>
<span>R _____ per night</span>
</div>

<div class="price-item">
<span>Breakfast</span>
<span>R _____</span>
</div>

</div>

</section>

<section id="contact">

<div class="contact">

<h2>Contact Us</h2>

<p>📞 YOUR PHONE NUMBER</p>

<p>📧 yourguesthouse@email.com</p>

<p>📍 Your Address Here</p>

<br>

<a href="tel:YOURNUMBER" class="btn">
Call Now
</a>

</div>

</section>

<footer>

<p>© 2026 Your Guesthouse Name. All Rights Reserved.</p>

</footer>

</body>
</html>
