# fsd
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Restaurant Menu</h1>
            <nav>
                <ul>
                    <li><a href="#starters">Starters</a></li>
                    <li><a href="#main">Main Course</a></li>
                    <li><a href="#desserts">Desserts</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="starters" class="menu-section">
            <h2>Starters</h2>
            <div class="menu-items">
                <div class="item">
                    <h3>Bruschetta</h3>
                    <p>A crispy toasted bread topped with tomatoes and basil.</p>
                    <span class="price">$5.99</span>
                    <button class="order-btn">Order</button>
                </div>
                <div class="item">
                    <h3>Garlic Bread</h3>
                    <p>Warm garlic buttered bread with herbs.</p>
                    <span class="price">$4.49</span>
                    <button class="order-btn">Order</button>
                </div>
            </div>
        </section>

        <section id="main" class="menu-section">
            <h2>Main Course</h2>
            <div class="menu-items">
                <div class="item">
                    <h3>Spaghetti Bolognese</h3>
                    <p>A classic Italian pasta dish with rich meat sauce.</p>
                    <span class="price">$12.99</span>
                    <button class="order-btn">Order</button>
                </div>
                <div class="item">
                    <h3>Grilled Chicken</h3>
                    <p>Juicy chicken breast grilled to perfection, served with veggies.</p>
                    <span class="price">$14.49</span>
                    <button class="order-btn">Order</button>
                </div>
            </div>
        </section>

        <section id="desserts" class="menu-section">
            <h2>Desserts</h2>
            <div class="menu-items">
                <div class="item">
                    <h3>Chocolate Cake</h3>
                    <p>Rich and moist chocolate cake with a creamy filling.</p>
                    <span class="price">$6.99</span>
                    <button class="order-btn">Order</button>
                </div>
                <div class="item">
                    <h3>Ice Cream</h3>
                    <p>Vanilla, chocolate, and strawberry flavors.</p>
                    <span class="price">$3.99</span>
                    <button class="order-btn">Order</button>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

/* Reset default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.2rem;
}

main {
    padding: 20px;
}

.menu-section {
    margin-bottom: 40px;
}

.menu-section h2 {
    font-size: 2rem;
    color: #444;
    margin-bottom: 10px;
}

.menu-items {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.item {
    background-color: white;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.item h3 {
    font-size: 1.5rem;
    color: #444;
}

.item p {
    font-size: 1rem;
    color: #666;
}

.price {
    font-size: 1.25rem;
    color: #28a745;
    margin-top: 10px;
}

.order-btn {
    background-color: #007bff;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    margin-top: 10px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.order-btn:hover {
    background-color: #0056b3;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}
// JavaScript for order button interaction
document.addEventListener('DOMContentLoaded', function() {
    const orderButtons = document.querySelectorAll('.order-btn');

    orderButtons.forEach(button => {
        button.addEventListener('click', function() {
            alert('Your order has been placed!');
        });
    });
});

