 <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>News Blog Shop</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<h1>My News & Shop</h1>
<nav>
<a href="index.html">Home</a>
<a href="blog.html">Blog</a>
<a href="shop.html">Shop</a>
</nav>
</header>

<main>
<h2>Latest News</h2>
<div class="card">
<h3>News Article 1</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. <a href="#">Read more</a></p>
</div>
<div class="card">
<h3>News Article 2</h3>
<p>Vestibulum at eros eu libero laoreet bibendum. <a href="#">Read more</a></p>
</div>
<div class="card">
<h3>News Article 3</h3>
<p>Curabitur nec velit nec urna facilisis scelerisque. <a href="#">Read more</a></p>
</div>
</main>

<footer>
<p>&copy; 2025 My News Blog Shop</p>
</footer>

<script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blog - News Blog Shop</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<h1>My News & Shop</h1>
<nav>
<a href="index.html">Home</a>
<a href="blog.html">Blog</a>
<a href="shop.html">Shop</a>
</nav>
</header>

<main>
<h2>Latest Blog Posts</h2>
<div class="card">
<h3>Blog Post 1</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. <a href="#">Read more</a></p>
</div>
<div class="card">
<h3>Blog Post 2</h3>
<p>Vestibulum at eros eu libero laoreet bibendum. <a href="#">Read more</a></p>
</div>
<div class="card">
<h3>Blog Post 3</h3>
<p>Curabitur nec velit nec urna facilisis scelerisque. <a href="#">Read more</a></p>
</div>
</main>

<footer>
<p>&copy; 2025 My News Blog Shop</p>
</footer>

<script src="script.js"></script>
</body>
</html>let cart = [];

function addToCart(product) {
    cart.push(product);
    alert(product + " added to cart!");
}

function showCart() {
    console.log("Cart Items:", cart);
}* { margin: 0; padding: 0; box-sizing: border-box; }
body { font-family: Arial, sans-serif; background: #f4f4f4; }
header { background: #333; color: white; padding: 1rem; text-align: center; }
header nav a { color: white; margin: 0 1rem; text-decoration: none; }
header nav a:hover { text-decoration: underline; }
main { padding: 2rem; max-width: 1200px; margin: auto; }
.card { background: white; padding: 1rem; margin: 1rem 0; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
button { padding: 0.5rem 1rem; background: #333; color: white; border: none; border-radius: 5px; cursor: pointer; }
button:hover { background: #555; }
footer { background: #333; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
.products { display: grid; grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); gap: 1rem; }

@media (max-width: 768px) {
header nav { display: flex; flex-direction: column; gap: 0.5rem; margin-top: 0.5rem; }
main { padding: 1rem; }
.products { grid-template-columns: 1fr; }
}

@media (max-width: 480px) {
header h1 { font-size: 1.5rem; }
button { width: 100%; padding: 0.7rem; }
.card { padding: 1rem; }
}* { margin: 0; padding: 0; box-sizing: border-box; }
body { font-family: Arial, sans-serif; background: #f4f4f4; }
header { background: #333; color: white; padding: 1rem; text-align: center; }
header nav a { color: white; margin: 0 1rem; text-decoration: none; }
header nav a:hover {
A place where you shop blog and interact. <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>News Blog Shop</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- your content -->
</body>
</html>
