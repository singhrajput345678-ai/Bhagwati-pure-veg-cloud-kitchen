<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Bhagwati Kitchen | Pure Veg Cloud Kitchen</title>

<!-- APP ICON / FAVICON -->
<link rel="icon" type="image/png" href="logo.png">

<style>
body{
    margin:0;
    font-family:'Segoe UI', Arial, sans-serif;
    background:#fffdf8;
    color:#333;
}

/* HEADER */
header{
    background:linear-gradient(135deg,#1b5e20,#43a047);
    color:white;
    text-align:center;
    padding:45px 15px;
}

.logo{
    width:120px;
    margin-bottom:15px;
}

header h1{
    margin:0;
    font-size:36px;
}

header p{
    margin-top:10px;
    font-size:16px;
}

/* SECTIONS */
section{
    padding:40px 15px;
    max-width:1100px;
    margin:auto;
}

h2{
    text-align:center;
    color:#1b5e20;
    margin-bottom:25px;
}

/* MENU */
.menu-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.menu-card{
    background:white;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 4px 12px rgba(0,0,0,0.1);
}

.menu-card img{
    width:100%;
    height:160px;
    object-fit:cover;
}

.menu-card div{
    padding:15px;
}

.menu-card h3{
    margin:0;
    color:#2e7d32;
}

.price{
    font-weight:bold;
    margin-top:6px;
}

/* BUTTONS */
.buttons{
    text-align:center;
}

.btn{
    display:inline-block;
    margin:10px;
    padding:15px 28px;
    color:white;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
}

.whatsapp{background:#25D366;}
.zomato{background:#e23744;}
.swiggy{background:#fc8019;}
.pdf{background:#555;}

/* REVIEWS */
.reviews{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.review{
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 3px 8px rgba(0,0,0,0.08);
}

/* MAP */
.map iframe{
    width:100%;
    height:300px;
    border:0;
    border-radius:12px;
}

/* FOOTER */
footer{
    background:#f1f1f1;
    text-align:center;
    padding:15px;
    font-size:14px;
}
</style>
</head>

<body>

<header>
    <img src="logo.png" alt="Bhagwati Kitchen Logo" class="logo">
    <h1>Bhagwati Kitchen</h1>
    <p>Pure Veg • Home Style Food • Cloud Kitchen</p>
</header>

<section>
    <h2>About Us</h2>
    <p style="text-align:center;max-width:750px;margin:auto;">
        Bhagwati Kitchen offers hygienic, freshly cooked pure vegetarian
        meals with authentic home-style taste. Quality & cleanliness
        are our top priority.
    </p>
</section>

<section>
    <h2>Our Menu</h2>
    <div class="menu-grid">

        <div class="menu-card">
            <img src="https://source.unsplash.com/400x300/?veg-thali">
            <div>
                <h3>Veg Thali</h3>
                <p class="price">₹120</p>
            </div>
        </div>

        <div class="menu-card">
            <img src="https://source.unsplash.com/400x300/?paneer">
            <div>
                <h3>Paneer Butter Masala</h3>
                <p class="price">₹180</p>
            </div>
