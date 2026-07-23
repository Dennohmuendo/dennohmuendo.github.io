/* MC Dennoh Muendo Official Website */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0f0f0f;
    color:#fff;
    line-height:1.7;
}

/* Header */

header{
    position:fixed;
    top:0;
    width:100%;
    background:#000;
    padding:18px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    z-index:1000;
    box-shadow:0 2px 10px rgba(0,0,0,.4);
}

.logo{
    color:#FFD700;
    font-size:30px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    transition:.3s;
}

nav a:hover{
    color:#FFD700;
}

/* Hero */

.hero{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
    background:linear-gradient(rgba(0,0,0,.75),rgba(0,0,0,.75));
}

.hero h1{
    font-size:60px;
    color:#FFD700;
}

.hero p{
    margin:20px 0;
    font-size:22px;
}

.btn{
    display:inline-block;
    padding:15px 35px;
    background:#FFD700;
    color:black;
    text-decoration:none;
    font-weight:bold;
    border-radius:50px;
    transition:.3s;
}

.btn:hover{
    background:white;
}

/* Sections */

section{
    padding:90px 10%;
}

.title{
    text-align:center;
    font-size:40px;
    margin-bottom:40px;
    color:#FFD700;
}

/* Cards */

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1f1f1f;
    border-radius:15px;
    padding:25px;
    transition:.4s;
}

.card:hover{
    transform:translateY(-8px);
    border:2px solid #FFD700;
}

/* Gallery */

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    height:320px;
    object-fit:cover;
    border-radius:12px;
    transition:.4s;
}

.gallery img:hover{
    transform:scale(1.05);
}

/* Contact */

.contact{
    text-align:center;
}

.contact p{
    margin:12px 0;
    font-size:18px;
}

/* Footer */

footer{
    background:#000;
    text-align:center;
    padding:30px;
    margin-top:60px;
}

/* WhatsApp */

.whatsapp{
    position:fixed;
    right:20px;
    bottom:20px;
    width:60px;
    height:60px;
    border-radius:50%;
    background:#25D366;
    color:white;
    display:flex;
    justify-content:center;
    align-items:center;
    text-decoration:none;
    font-size:30px;
    box-shadow:0 4px 15px rgba(0,0,0,.3);
}

.whatsapp:hover{
    transform:scale(1.1);
}

/* Mobile */

@media(max-width:768px){

header{
    flex-direction:column;
}

nav{
    margin-top:15px;
}

nav a{
    display:block;
    margin:10px 0;
}

.hero h1{
    font-size:40px;
}

.hero p{
    font-size:18px;
}

.title{
    font-size:30px;
}

}# dennohmuendo.github.io
Website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MC Dennoh Muendo | Official Website</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#111;
color:white;
}

header{
position:fixed;
top:0;
width:100%;
background:#000;
padding:15px 40px;
display:flex;
justify-content:space-between;
align-items:center;
z-index:1000;
}

.logo{
font-size:28px;
font-weight:bold;
color:gold;
}

nav a{
margin-left:20px;
color:white;
text-decoration:none;
transition:.3s;
}

nav a:hover{
color:gold;
}

.hero{
height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:20px;
background:linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),url('images/profile1.jpg');
background-size:cover;
background-position:center;
}

.hero h1{
font-size:60px;
color:gold;
}

.hero p{
font-size:22px;
margin:20px 0;
}

.btn{
padding:15px 35px;
background:gold;
color:black;
font-weight:bold;
border-radius:40px;
text-decoration:none;
display:inline-block;
}

section{
padding:80px 10%;
}

.title{
text-align:center;
font-size:40px;
margin-bottom:40px;
color:gold;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:#222;
padding:25px;
border-radius:15px;
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:300px;
object-fit:cover;
border-radius:12px;
}

.contact{
text-align:center;
}

.contact p{
margin:10px 0;
font-size:18px;
}

footer{
background:black;
padding:30px;
text-align:center;
margin-top:40px;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
padding:15px 18px;
border-radius:50%;
font-size:28px;
text-decoration:none;
color:white;
}
</style>
</head>

<body>

<header>

<div class="logo">MC DENNOH</div>

<nav>

<a href="#about">About</a>

<a href="#services">Services</a>

<a href="#gallery">Gallery</a>

<a href="#contact">Contact</a>

</nav>

</header>

<section class="hero">

<div>

<h1>MC DENNOH MUENDO</h1>

<p>Journalist • Event MC • Podcaster • Digital Creator</p>

<a href="#contact" class="btn">Book Me</a>

</div>

</section>

<section id="about">

<h2 class="title">About Me</h2>

<p style="text-align:center;font-size:18px;max-width:900px;margin:auto;">
My name is <b>Dennis Muendo Kyalo</b>, professionally known as <b>MC Dennoh Muendo</b>.
I am a passionate Journalist, Master of Ceremonies, Digital Creator, YouTuber, Podcaster and Script Writer from Nairobi, Kenya.
I love telling stories that educate, inspire and entertain.
</p>

</section>

<section id="services">

<h2 class="title">Services</h2>

<div class="cards">

<div class="card">
<h3>🎤 Event MC</h3>
<p>Corporate events, weddings, concerts and ceremonies.</p>
</div>

<div class="card">
<h3>📰 Journalism</h3>
<p>Interviews, documentaries and news coverage.</p>
</div>

<div class="card">
<h3>🎥 Content Creation</h3>
<p>YouTube, TikTok, Facebook and Instagram content.</p>
</div>

<div class="card">
<h3>🎙 Podcast Hosting</h3>
<p>Professional podcast recording and hosting.</p>
</div>

</div>

</section>

<section id="gallery">

<h2 class="title">Gallery</h2>

<div class="gallery">

<img src="images/photo1.jpg">

<img src="images/photo2.jpg">

<img src="images/photo3.jpg">

<img src="images/photo4.jpg">

<img src="images/photo5.jpg">

<img src="images/photo6.jpg">

</div>

</section>

<section id="contact">

<h2 class="title">Contact Me</h2>

<div class="contact">

<p>📞 0704 429 799</p>

<p>📞 0740 550 769</p>

<p>📧 denniskyalo484@gmail.com</p>

<p>📧 dkyalo432@gmail.com</p>

<p>📍 Nairobi, Kenya</p>

<p>TikTok: @Mlami Wa Ngara (MC Dennoh)</p>

</div>

</section>

<footer>

<h3>MC DENNOH MUENDO</h3>

<p>© 2026 All Rights Reserved</p>

</footer>

<a class="whatsapp" href="https://wa.me/254704429799">💬</a>

</body>
</html>
