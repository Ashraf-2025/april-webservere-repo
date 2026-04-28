.<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>E-Commerce Website</title>
<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}
body{
    background:#f5f5f5;
}
header{
    background:#222;
    color:white;
    padding:15px;
    text-align:center;
}
nav{
    background:#444;
    padding:10px;
    text-align:center;
}
nav a{
    color:white;
    text-decoration:none;
    margin:15px;
}
.container{
    width:90%;
    margin:auto;
    padding:20px;
}
.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}
.card{
    background:white;
    padding:15px;
    border-radius:10px;
    box-shadow:0 4px 8px rgba(0,0,0,0.1);
    text-align:center;
}
.card img{
    width:100%;
    height:200px;
    object-fit:cover;
    border-radius:10px;
}
.card h3{
    margin:10px 0;
}
.card p{
    color:green;
    font-size:18px;
}
button{
    background:#28a745;
    color:white;
    border:none;
    padding:10px 15px;
    border-radius:5px;
    cursor:pointer;
}
button:hover{
    background:#218838;
}
footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:20px;
}
</style>
</head>
<body>

<header>
    <h1>My E-Commerce Store</h1>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Cart</a>
    <a href="#">Contact</a>
</nav>

<div class="container">
    <h2>Featured Products</h2>
    <br>
    <div class="products">

        <div class="card">
            <img src="https://via.placeholder.com/250" alt="Product">
            <h3>Smart Watch</h3>
            <p>₹2,999</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250" alt="Product">
            <h3>Wireless Headphones</h3>
            <p>₹1,499</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250" alt="Product">
            <h3>Running Shoes</h3>
            <p>₹3,499</p>
            <button>Add to Cart</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250" alt="Product">
            <h3>Backpack</h3>
            <p>₹999</p>
            <button>Add to Cart</button>
        </div>

    </div>
</div>

<footer>
    <p>© 2026 My E-Commerce Store | All Rights Reserved</p>
</footer>

</body>
</html>
