# E-commerceproductpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Product Name</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="product-image">
            <!--<img src="product.jpg" alt="Product Image">!-->
        </section>
        <section class="product-details">
            <h2>Product Name</h2>
            <p class="price">$99.99</p>
            <p class="description">This is a detailed description of the product.</p>
            <button class="cta">Add to Cart</button>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Company</p>
    </footer>
</body>
</html>




styles.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.product-image img {
    width: 100%;
    height: auto;
}

.product-details {
    padding: 1rem;
    text-align: center;
}

.price {
    color: #e74c3c;
    font-size: 1.5rem;
}

.cta {
    background-color: #3498db;
    color: #fff;
    border: none;
    padding: 1rem 2rem;
    cursor: pointer;
    font-size: 1rem;
}

.cta:hover {
    background-color: #2980b9;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
}

@media (min-width: 768px) {
    .product-image, .product-details {
        display: inline-block;
        width: 48%;
        vertical-align: top;
    }

    .product-details {
        text-align: left;
    }
}
