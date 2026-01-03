<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Urban Exchange – Luxury Resale</title>

<style>
:root{
  --black:#111;
  --gray:#666;
  --light:#f6f6f6;
  --accent:#c9a24d;
}
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial,Helvetica,sans-serif}
body{background:#fff;color:#111}

/* HEADER */
header{border-bottom:1px solid #e5e5e5;position:sticky;top:0;background:#fff;z-index:100}
.nav{max-width:1200px;margin:auto;display:flex;justify-content:space-between;align-items:center;padding:15px}
.logo{font-size:22px;font-weight:bold;letter-spacing:1px}
nav a{margin:0 10px;text-decoration:none;color:#111;font-size:14px}
nav a:hover{color:var(--accent)}

/* HERO */
.hero{
  height:75vh;
  background:url("https://images.unsplash.com/photo-1490481651871-ab68de25d43d?q=80&w=1600") center/cover no-repeat;
  display:flex;align-items:center;justify-content:center;
  color:#fff;text-align:center
}
.hero h1{font-size:48px;margin-bottom:15px}
.hero p{font-size:18px;margin-bottom:25px}
.hero button{
  padding:12px 32px;
  background:#fff;border:none;
  font-size:14px;cursor:pointer
}

/* SECTION */
.section{max-width:1200px;margin:70px auto;padding:0 15px}
.section h2{text-align:center;font-size:30px;margin-bottom:40px}

/* CATEGORIES */
.categories{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px
}
.category{
  height:300px;
  background-size:cover;
  background-position:center;
  display:flex;
  align-items:flex-end;
  padding:20px;
  color:#fff;
  font-size:20px;
  font-weight:bold
}

/* PRODUCTS */
.products{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:25px
}
.product{
  border:1px solid #eee;
  padding:15px;
  text-align:center
}
.product img{
  width:100%;
  height:260px;
  object-fit:cover
}
.product h3{font-size:14px;margin:10px 0}
.product p{color:var(--gray);font-size:13px}
.product span{color:#000;font-weight:bold}

/* INFO */
.info{
  background:var(--light);
  padding:60px 15px;
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:30px;
  text-align:center
}

/* FOOTER */
footer{background:#111;color:#fff;padding:50px 15px}
.footer{
  max-width:1200px;margin:auto;
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:30px
}
footer a{color:#bbb;text-decoration:none;font-size:13px}
footer a:hover{color:#fff}
.copy{text-align:center;margin-top:30px;font-size:12px;color:#aaa}
</style>
</head>

<body>

<header>
  <div class="nav">
    <div class="logo">URBAN EXCHANGE</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Designers</a>
      <a href="#">New Arrivals</a>
      <a href="#">Handbags</a>
      <a href="#">Shoes</a>
      <a href="#">Clothing</a>
      <a href="#">Accessories</a>
    </nav>
  </div>
</header>

<section class="hero">
  <div>
    <h1>Luxury You’ll Love Again</h1>
    <p>Authenticated designer resale</p>
    <button>SHOP NEW ARRIVALS</button>
  </div>
</section>

<section class="section">
  <h2>Shop by Category</h2>
  <div class="categories">
    <div class="category" style="background-image:url('https://images.unsplash.com/photo-1584917865442-de89df76afd3?q=80&w=800')">Handbags</div>
    <div class="category" style="background-image:url('https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?q=80&w=800')">Accessories</div>
    <div class="category" style="background-image:url('https://images.unsplash.com/photo-1593032465175-481ac7f401a0?q=80&w=800')">Shoes</div>
    <div class="category" style="background-image:url('https://images.unsplash.com/photo-1483985988355-763728e1935b?q=80&w=800')">Clothing</div>
  </div>
</section>

<section class="section">
  <h2>New Arrivals</h2>
  <div class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1618354691373-d851c5c3a990?q=80&w=600">
      <h3>Leather Crossbody Bag</h3>
      <p><span>$1,180</span></p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1600180758890-6b94519a8ba6?q=80&w=600">
      <h3>Designer Sneakers</h3>
      <p><span>$690</span></p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1520975916090-3105956dac38?q=80&w=600">
      <h3>Luxury Sunglasses</h3>
      <p><span>$420</span></p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1519744792095-2f2205e87b6f?q=80&w=600">
      <h3>Gold Statement Jewelry</h3>
      <p><span>$350</span></p>
    </div>
  </div>
</section>

<section class="section">
  <h2>Best Sellers</h2>
  <div class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1595341888016-a392ef81b7de?q=80&w=600">
      <h3>Designer Tote Bag</h3>
      <p><span>$1,450</span></p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1542060748-10c28b62716c?q=80&w=600">
      <h3>Luxury Heels</h3>
      <p><span>$820</span></p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1503342217505-b0a15ec3261c?q=80&w=600">
      <h3>Designer Jacket</h3>
      <p><span>$980</span></p>
    </div>
  </div>
</section>

<section class="info">
  <div>
    <h3>100% Authentic</h3>
    <p>Every item verified by luxury experts</p>
  </div>
  <div>
    <h3>Sustainable Fashion</h3>
    <p>Luxury resale that reduces waste</p>
  </div>
  <div>
    <h3>Sell With Us</h3>
    <p>Consign & earn from your closet</p>
  </div>
</section>

<footer>
  <div class="footer">
    <div>
      <h4>Urban Exchange</h4>
      <p style="font-size:13px;color:#bbb">Luxury resale marketplace</p>
    </div>
    <div>
      <h4>Shop</h4>
      <a href="#">New Arrivals</a><br>
      <a href="#">Designers</a><br>
      <a href="#">Handbags</a>
    </div>
    <div>
      <h4>Customer Care</h4>
      <a href="#">Contact</a><br>
      <a href="#">Shipping</a><br>
      <a href="#">Returns</a>
    </div>
    <div>
      <h4>Newsletter</h4>
      <p style="font-size:13px;color:#bbb">Exclusive drops & offers</p>
    </div>
  </div>
  <div class="copy">© 2026 Urban Exchange – Demo Shopping Template</div>
</footer>

</body>
</html>
