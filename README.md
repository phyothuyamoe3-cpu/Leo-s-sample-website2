<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Mini Website Shopping</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:'Segoe UI',Tahoma,Geneva,Verdana,sans-serif;
            box-sizing:border-box;
        }
        body{
            background-color:#f9f9f9;
            color:#333;
            line-height:1.6;
        }
        .navbar{
            display:flex;
            align-items: center;
            padding:20px;
            background-color:white;
            justify-content:space-between;

        }
        .logo{
            font-weight:bold;
            font-size:18px;
            margin-left:30px;
        }
        .logo span{
            color:#ff4757;
        }
        .nav_links{
            display:flex;
            gap:20px;
            list-style:none;
        }
        .nav_links a{
            text-decoration:none;
            color:#333;
            font-weight: 500;
        }
        .hero{
            background-color: #eeeeee;
            padding:50px 20px;
            text-align: center;
        }
        .hero h1{
            font-size:40px;
            margin-bottom:10px;
        }
        .btn-main{
            background-color:#333;
            color:white;
            padding:12px 30px;
            border:none;
            cursor:pointer;
            margin-top:20px;
        }
        .section-title{
            margin-top:20px;
            margin-bottom:30px;
            text-align: center;
        }
        .product-grid{
            display:flex;
            gap:30px;
            justify-content:center;
        }
        .card{
            background-color:white;
            width:300px;
            border:1px solid #ddd;
        }
        .card img{
            width:100%;
            height:350px;
        }
        .card-content{
            padding:20px;
            text-align:center;
        }
        .price{
            color:#ff4757;
            font-weight:bold;
            font-size:20px;
            margin-bottom:10px ;
        }
        .btn-add{
            width:100%;
            padding:10px;
            background:none;
            border:2px solid #333;
            font-weight: bold;
            cursor:pointer;
        }
        .btn-add:hover{
            background:#333;
            color:white;
        }
        footer{
            text-align:center;
            padding:40px;
            background:#fff;
            margin-top:50px;
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="logo">
            MINI<span>SHOP</span>
        </div>
        <ul class="nav_links">
            <li><a href="#">Home</a></li>
            <li><a href="#">Shop</a></li>
            <li><a href="#">Cart (0)</a></li>
        </ul>
    </nav>
    <header class="hero">
        <h1>Summer Essentials</h1>
        <p>Quality basics for everyday wear</p>
        <button class="btn-main">Shop Now</button>

    </header>
    <main class="container">
        <h2 class="section-title">Featured Products</h2>
        <div class="product-grid">
            <div class="card">
                <img src="../images/img_5.png">
                <div class="card-content">
                    <h3>Classic White Tee</h3>
                    <p class="price">$25</p>
                    <button class="btn-add">Add to Cart</button>
                </div>
            </div>
            <div class="card">
                <img src="../images/img_6.png">
                <div class="card-content">
                    <h3>Denim T-shirt</h3>
                    <p class="price">$85</p>
                    <button class="btn-add">Add to Cart</button>
                </div>
            </div>
            <div class="card">
                <img src="../images/img_7.png">
                <div class="card-content">
                    <h3>Classic Pale Tee</h3>
                    <p class="price">$25</p>
                    <button class="btn-add">Add to Cart</button>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>&copy; 2026 Simple Shop. All rights reserved.</p>
    </footer>
</body>
</html>
