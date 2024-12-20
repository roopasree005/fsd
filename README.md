<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Information</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f7cac9, #92a8d1);
            color: #333;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
        }
        .menu-buttons {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }
        .menu-buttons button {
            padding: 15px;
            background: #4caf50;
            border: none;
            color: white;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .menu-buttons button:hover {
            background: #45a049;
        }
        footer {
            margin-top: 20px;
            text-align: center;
            background: #333;
            color: white;
            padding: 10px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>5-STAR HOTEL!</h1>
        <img src="https://www.jaypeehotels.com/blog/wp-content/uploads/2020/09/5-Star-Hotel-1-1024x602.jpg" alt="">
        <h1>About Our Hotel</h1>
    </header>
    <div class="container">
        <p>Welcome to our hotel, a place where luxury meets comfort. We are committed to providing an exceptional experience for our guests with top-notch facilities and outstanding services. Our team is dedicated to ensuring your stay is memorable.
        Enjoy the ambiance  with tasty foods.</p>

        <div class="menu-buttons">
            <button onclick="location.href='starters.html'">Starters</button>
            <button onclick="location.href='main-course.html'">Main Course</button>
            <button onclick="location.href='desserts.html'">Desserts</button>
        </div>
    </div>
    <footer>
        <p>Hotel Address: 5-Star Hotel, Near Dayananda sagar university,<br>
            Harohalli,Ramanagar District-562112</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>5-Star Hotel Menu</title>
    <style>
        /* Global styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        /* Body styles */
        body {
            background-color: #3E2723; /* Deep brown */
            color: #FAFAFA; /* Light text */
            line-height: 1.6;
        }

        /* Header */
        header {
            background-color: #5D4037; /* Chocolate brown */
            color: #FFD54F; /* Golden yellow */
            text-align: center;
            padding: 2rem 1rem;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px #000;
        }

        header img {
            margin: 10px 0;
            max-width: 100%;
            height: auto;
        }

        /* Menu Section */
        section.menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2rem 1rem;
        }

        .menu-item {
            background-color: #FFF8E1;
            border: 1px solid #E0E0E0;
            border-radius: 10px;
            overflow: hidden;
            width: 300px;
            margin: 1rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }

        .menu-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .menu-item .content {
            padding: 1rem;
            text-align: center;
        }

        .menu-item h3 {
            font-size: 1.8rem;
            color: #D84315;
            margin-bottom: 0.5rem;
        }

        .menu-item p {
            font-size: 1rem;
            color: #5D4037;
        }

        .menu-item .price {
            font-size: 1.4rem;
            color: #FF7043;
            font-weight: bold;
        }

        /* Footer */
        footer {
            background-color: #5D4037;
            color: #FFD54F;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        footer p {
            font-size: 1rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            section.menu {
                flex-direction: column;
                align-items: center;
            }

            .menu-item {
                width: 90%;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>5-Star Hotel Menu</h1>
        <img src="https://media-cdn.grubhub.com/image/upload/d_search:browse-images:default.jpg/w_1200,q_auto,fl_lossy,dpr_auto,c_fill,f_auto,h_800,g_auto/eqxisltrvlwau19towzj">
        <h1>STARTERS</h1>
    </header>

    <h1>VEG STARTERS</h1>
    <section class="menu">
        <div class="menu-item">
            <img src="https://rainbowplantlife.com/wp-content/uploads/2022/02/Gobi-Manchurian-cover-photo-on-white-tile-1-of-1.jpg" alt="Gobi Manchurian">
            <div class="content">
                <h3>Gobi Manchurian</h3>
                <p>An Indo-Chinese appetizer and this version will blow your mind!</p>
                <p class="price">₹190</p>
                <button class="add-to-cart" onclick="addToCart('Gobi Manchurian', 190)">Add to Cart</button>
            </div>
        </div>
        <div class="menu-item">
            <img src="https://www.spiceindiaonline.com/files/images/Chilli%20Gobi.jpg.preview.JPG" alt="Gobi Chilli">
            <div class="content">
                <h3>Gobi Chilli</h3>
                <p>A spicy starter or appetizer recipe adapted from Chinese cuisine and seasoning techniques.</p>
                <p class="price">₹200</p>
                <button class="add-to-cart" onclick="addToCart('Gobi Chilli', 200)">Add to Cart</button>
            </div>
        </div>
        <div class="menu-item">
            <img src="https://img.freepik.com/premium-photo/mushroom-manchurian-dried-black-bowl-dark-background-indo-chinese-dish-with-fried-mushrooms-peppe_908985-33517.jpg" alt="Mushroom Manchurian">
            <div class="content">
                <h3>Mushroom Manchurian</h3>
                <p>Mushroom Manchurian is a tasty saucy dish made by marinating mushroom with spice powders & cooking it with sauces, tomato & onions.</p>
                <p class="price">₹310</p>
                <button class="add-to-cart" onclick="addToCart('Mushroom Manchurian', 310)">Add to Cart</button>
            </div>
        </div>
        <div class="menu-item">
            <img src="https://1.bp.blogspot.com/-_QHI8lgj5n8/XuJ7chjrXYI/AAAAAAAAKQ0/tQuNDYLDYQ4YIhji0IVat-y7iLuutnVGwCLcBGAsYHQ/s1600/Chilli%2BMushroom%2BDry.JPG" alt="Mushroom Chilli">
            
            <div class="content">
                <h3>Mushroom Chilli</h3>
                <p>Chili Mushroom is a popular Indo-Chinese dish, often served as an appetizer or snack.</p>
                <p class="price">₹300</p>
                <button class="add-to-cart" onclick="addToCart('Mushroom chilli', 300)">Add to Cart</button>
            </div>
        </div>
        <div class="menu-item">
            <img src="https://cdn2.foodviva.com/static-content/food-images/chinese-recipes/baby-corn-manchurian/baby-corn-manchurian.jpg" alt="Baby Corn Manchurian">
            <div class="content">
                <h3>Baby Corn Manchurian</h3>
                <p>Baby Corn Manchurian is crispy crunchy fried baby corn, tossed in an extremely flavorful spicy, sweet and tangy Manchurian sauce.</p>
                <p class="price">₹200</p>
                <button class="add-to-cart" onclick="addToCart('Baby Corn Manchurian', 200)">Add to Cart</button>
            </div>
        </div>
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-YI7VapSILTgOdqapVOLwVpErcXwrK2NY7Q&s" alt="Baby Corn Chilli ">
                <div class="content">
                    <h3>Baby Corn Chilli </h3>
                    <p>An ideal appetiser or a party starter recipe made with tender baby corns in a chilli sauce.</p>
                    <p class="price">₹250</p>
                    <button class="add-to-cart" onclick="addToCart('Baby Corn Chilli ', 250)">Add to Cart</button>
                </div>
        </div>
        <div class="menu-item">
            <img src="https://vaya.in/recipes/wp-content/uploads/2018/03/Paneer-Manchurian.jpg" alt="Paneer Manchurian">
            <div class="content">
                <h3>Paneer Manchurian</h3>
                <p>Crisp fried paneer tossed in Manchurian sauce.</p>
                <p class="price">₹280</p>
                <button class="add-to-cart" onclick="addToCart('Paneer Manchurian', 280)">Add to Cart</button>
            </div>
    </div>
    <div class="menu-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsY-Hux2hgO2-wedeBDsyMEIOw_WsJIrxYs9H-b3Phbn-q0g-34FeZc3AiyQ2iPAiGQaI&usqp=CAU" alt="Paneer Chilli ">
        <div class="content">
            <h3>Paneer Chilli</h3>
            <p> It's a great appetizer or side dish and is loved for its perfect balance of flavors—spicy, tangy, and slightly sweet.</p>
            <p class="price">₹310</p>
            <button class="add-to-cart" onclick="addToCart('Paneer Chilli', 310)">Add to Cart</button>
        </div>
    </div>
    </div>
    </section>
    
    <h1>EGG STARTERS</h1>
    <section class="menu">
    <div class="menu-item">
        <img src="https://www.sweetashoney.co/wp-content/uploads/Omelette-2.jpg" alt="Egg Omlet">
        <div class="content">
            <h3>Paneer Chilli</h3>
            <p>An egg dish that's folded in half and filled with cheese, meat, or vegetables. </p>
            <p class="price">₹90</p>
            <button class="add-to-cart" onclick="addToCart('Paneer Chilli', 90)">Add to Cart</button>
        </div>
    </div>
    <div class="menu-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgpDPizX6nGLyzXnHWHrHm6J38ac1u0mGgYw&s" alt="Egg Bhurgi ">
        <div class="content">
            <h3>Egg Bhurgi</h3>
            <p>A popular and flavorful dish in Indian cuisine. It is made by scrambling eggs with a variety of spices and vegetables.</p>
            <p class="price">₹100</p>
            <button class="add-to-cart" onclick="addToCart('Egg Bhurgi', 100)">Add to Cart</button>
        </div>
    </div>
    <div class="menu-item">
        <img src="https://c.ndtvimg.com/2021-01/rlten3n8_manchurian_625x300_27_January_21.jpg?im=FaceCrop,algorithm=dnn,width=1200,height=886" alt="Egg Manchurian">
        <div class="content">
            <h3>Egg Manchurian</h3>
            <p>A perfect fusion dish with crispy eggs in a flavorful, aromatic sauce.</p>
            <p class="price">₹110</p>
            <button class="add-to-cart" onclick="addToCart('Egg Manchurian', 110)">Add to Cart</button>
        </div>
    </div>
    <div class="menu-item">
        <img src="https://static.toiimg.com/thumb/88273871.cms?imgsize=164852&width=800&height=800" alt="Egg Chilli">
        <div class="content">
            <h3>Egg Chilli</h3>
            <p> An excellent combination of heat, flavor, and a slight sweetness from the sauce.</p>
            <p class="price">₹120</p>
            <button class="add-to-cart" onclick="addToCart('Egg Chilli', 120)">Add to Cart</button>
        </div>
    </div>
    <div class="menu-item">
        <img src="https://www.hyderabadiruchulu.com/wp-content/uploads/2017/12/01-3.png" alt="Egg Pepper Dry">
        <div class="content">
            <h3>Egg Pepper Dry</h3>
            <p>A dry, tangy, and mildly spicy dish that pairs well with rice, chapati, or naan.</p>
            <p class="price">₹150</p>
            <button class="add-to-cart" onclick="addToCart('Egg Pepper Dry', 150)">Add to Cart</button>
        </div>
    </div>
    <div class="menu-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQUYTq22eZBPTgVLxrcl84Zdff_RAYzKHL4EAYWe2ygiw5ou-TqJzT_1kOWJW6jiAqmOh4&usqp=CAU" alt="Egg 65">
        <div class="content">
            <h3>Egg 65</h3>
            <p>Made with boiled eggs that are marinated in a flavorful mix of spices and then deep-fried to a golden crisp.</p>
            <p class="price">₹200</p>
            <button class="add-to-cart" onclick="addToCart('Egg 65', 200)">Add to Cart</button>
        </div>
    </div>
    </section>
    
    <h1>NON-VEG STARTERS</h1>
    <h2>TANDOORI STARTERS</h2>
    <section class="menu">
        <div class="menu-item">
            <img src="https://onestophalal.com/cdn/shop/articles/air_fryer_chicken_tandoori-1694242200588_1200x.jpg?v=1694242335" alt="Tandoori Chicken">
            <div class="content">
                <h3>Tandoori Chicken</h3>
                <p>Chicken is marinated in a mixture of yogurt and spices, then traditionally cooked in a tandoor (clay oven) for that smoky flavor.</p>
                <p class="price">₹550</p>
                <button class="add-to-cart" onclick="addToCart('Tandoori Chicken', 550)">Add to Cart</button>
            </div>
        </div>
    
        <div class="menu-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcToMozkkZv6pQonP3nn1BlXT2uLTWJxeshxYA&s" alt="Grill Chicken">
            <div class="content">
                <h3>Grill Chicken</h3>
                <p>Grilled Chicken is a versatile and flavorful dish that is easy to prepare and can be customized with various marinades and seasonings.</p>
                <p class="price">₹650</p>
                <button class="add-to-cart" onclick="addToCart('Grill Chicken', 650)">Add to Cart</button>
            </div>
        </div>
    
        <div class="menu-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRXhyH3-6Ip55q9u_Ym5fanwGiZxY0i-f2Fzw&s" alt="Alfham Chicken">
            <div class="content">
                <h3>Alfam Chicken</h3>
                <p>a flavorful and delicious dish that is typically known for its rich and aromatic marinade, followed by grilling or roasting.</p>
                <p class="price">₹590</p>
                <button class="add-to-cart" onclick="addToCart('Alfam Chicken', 590)">Add to Cart</button>
            </div>
        </div>
    
        <div class="menu-item">
            <img src="https://s23209.pcdn.co/wp-content/uploads/2016/07/BBQ-Chicken-BreastsIMG_0057edit.jpg" alt="BBQ Chicken">
            
            <div class="content">
                <h3>BBQ Chicken</h3>
                <p>A popular and flavorful dish that's enjoyed worldwide, especially for grilling enthusiasts.</p>
                <p class="price">₹580</p>
                <button class="add-to-cart" onclick="addToCart('BBQ Chicken', 580)">Add to Cart</button>
            </div>
        </div>
        </section>
    
    <h2>CHICKEN STARTERS</h2>
    <section class="menu">
    <div class="menu-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT_Qft3XRx1GrlwYz_duOf7-TGVrkfuKlzq4Q&s" alt="Chicken Kabab">
        <div class="content">
            <h3>Chicken Kabab</h3>
            <p>Chicken Kabab is a popular grilled or roasted dish that is packed with flavor from aromatic spices and marinades.</p>
            <p class="price">₹600</p>
            <button class="add-to-cart" onclick="addToCart('Chicken Kabab', 600)">Add to Cart</button>
        </div>
    </div>
    <div class="menu-item">
        <img src="https://purendesi.in/wp-content/uploads/2024/05/Chicken-Lollipop-Recipe.jpg" alt="Chicken Lollipop">
        <div class="content">
            <h3>Chicken Lollipop</h3>
            <p>a popular appetizer or snack made from chicken wings. The meat is separated from the bone, giving it a "lollipop" appearance, and then it's marinated in flavorful spices before being deep-fried or baked.</p>
            <p class="price">₹550</p>
            <button class="add-to-cart" onclick="addToCart('Chicken Lollipop', 550)">Add to Cart</button>
        </div>
    </div>
    <div class="menu-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ1NlO4ZltVro0CDRCfeAZJAFF-SPk5dfGvzw&s" alt="Dragon Chicken">
        <div class="content">
            <h3>Dragon Chicken</h3>
            <p>A popular Indo-Chinese dish known for its crispy chicken chunks coated in a spicy, sweet, and tangy sauce with a hint of smokiness. </p>
            <p class="price">₹560</p>
            <button class="add-to-cart" onclick="addToCart('Dragon Chicken', 560)">Add to Cart</button>
        </div>
    </div>
    <div class="menu-item">
        <img src="https://www.thetakeiteasychef.com/wp-content/uploads/2017/01/Garlic-Chicken-Thumbnail.jpg" alt="Garlic Chicken">
        <div class="content">
            <h3>Garlic Chicken</h3>
            <p>A flavorful and aromatic dish made with tender chicken pieces cooked in a savory garlic sauce. </p>
            <p class="price">₹550</p>
            <button class="add-to-cart" onclick="addToCart('Garlic Chicken', 550)">Add to Cart</button>
        </div>
    </div>
    
    </section>
    <h2>MUTTON STARTERS</h2>
    <section class="menu">
        <div class="menu-item">
            <img src="https://i.ytimg.com/vi/CNcGBT5Zrhc/hq720.jpg?sqp=-oaymwEhCK4FEIIDSFryq4qpAxMIARUAAAAAGAElAADIQj0AgKJD&rs=AOn4CLDbJNiKuhvQbrjmf6xFf-IqbXvWVQ" alt="Mutton Fry">
            <div class="content">
                <h3>Mutton Fry</h3>
                <p>A delicious and flavorful dish made with tender pieces of mutton cooked with aromatic spices, herbs, and a mix of seasonings. </p>
                <p class="price">₹620</p>
                <button class="add-to-cart" onclick="addToCart('Mutton Fry', 620)">Add to Cart</button>
            </div>
        </div>
        <div class="menu-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVkFnC25uGLC0IGYQKgMU5Lh1Ety2NgVLvbg&s" alt="Mutton Chilli">
            <div class="content">
                <h3>Mutton Chilli</h3>
                <p>A flavorful and spicy dish that combines tender pieces of mutton with a tangy, spicy sauce made from green chilies, soy sauce, and various spices.</p>
                <p class="price">₹700</p>
                <button class="add-to-cart" onclick="addToCart('Mutton Chilli', 700)">Add to Cart</button>
            </div>
        </div>
        <div class="menu-item">
            <img src="https://i.ytimg.com/vi/5TFYwaYlswk/maxresdefault.jpg" alt="Mutton Manchurian">
            <div class="content">
                <h3>Mutton Manchurian</h3>
                <p>A popular Indo-Chinese dish made with tender mutton pieces cooked in a rich, flavorful sauce with soy sauce, vinegar, and a blend of spices. </p>
                <p class="price">₹690</p>
                <button class="add-to-cart" onclick="addToCart('Mutton Manchurian', 690)">Add to Cart</button>
            </div>
        </div>
        <div class="menu-item">
            <img src="https://i.ytimg.com/vi/jrypYo58hNA/maxresdefault.jpg" alt="Mutton 65">
            <div class="content">
                <h3>Mutton 65</h3>
                <p>A flavorful and spicy Indian appetizer made with tender mutton pieces marinated in a spicy and tangy mixture, then deep-fried until crispy. </p>
                <p class="price">₹620</p>
                <button class="add-to-cart" onclick="addToCart('Mutton 65', 620)">Add to Cart</button>
            </div>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2024 5-Star Hotel | All Rights Reserved</p>
    </footer>
    

    <h1>Your Cart</h1>
    <section id="cart-section">
        <ul id="cart-list"></ul>
        <p id="cart-total">Total: ₹0</p>
    </section>

    <footer>
        <p>&copy; 2024 5-Star Hotel | All Rights Reserved</p>
    </footer>

<script>
     let cart = [];

// Function to add item to the cart
function addToCart(itemName, itemPrice) {
    // Create an object for the item
    const item = {
        name: itemName,
        price: itemPrice
    };

    // Add item to the cart
    cart.push(item);
    updateCart();
}

// Function to update the cart display
function updateCart() {
    const cartList = document.getElementById('cart-list');
    const cartTotal = document.getElementById('cart-total');

    // Clear the current list
    cartList.innerHTML = '';

    // Add each item to the cart display
    cart.forEach((item, index) => {
        const listItem = document.createElement('li');
        listItem.textContent =` ${item.name} - ₹${item.price}`;
        cartList.appendChild(listItem);
    });

    // Calculate total price
    const totalPrice = cart.reduce((total, item) => total + item.price, 0);

    // Update total price
    cartTotal.textContent = Total: ₹${totalPrice};
}

// Event listener for all "Add to Cart" buttons
document.querySelectorAll('.add-to-cart').forEach((button) => {
    button.addEventListener('click', function () {
        const itemName = this.parentElement.querySelector('h3').textContent;  // Get item name
        const itemPrice = parseInt(this.parentElement.querySelector('.price').textContent.replace('₹', ''));  // Get item price
        
        // Call addToCart function with the correct parameters
        addToCart(itemName, itemPrice);
    });
});
</script>
</body>
</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>5-Star Hotel Menu</title>
    <style>
        /* Global styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        /* Body styles */
        body {
            background-color: #3E2723; /* Deep brown */
            color: #FAFAFA; /* Light text */
            line-height: 1.6;
        }

        /* Header */
        header {
            background-color: #5D4037; /* Chocolate brown */
            color: #FFD54F; /* Golden yellow */
            text-align: center;
            padding: 2rem 1rem;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px #000;
        }

        header p {
            font-size: 1.5rem;
        }

        /* Menu Section */
        section.menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2rem 1rem;
        }

        .menu-item {
            background-color: #FFF8E1; /* Light cream */
            border: 1px solid #E0E0E0;
            border-radius: 10px;
            overflow: hidden;
            width: 300px;
            margin: 1rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }

        .menu-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .menu-item .content {
            padding: 1rem;
            text-align: center;
        }

        .menu-item h3 {
            font-size: 1.8rem;
            color: #D84315; /* Burnt orange */
            margin-bottom: 0.5rem;
        }

        .menu-item p {
            font-size: 1rem;
            color: #5D4037; /* Chocolate brown */
        }

        .menu-item .price {
            font-size: 1.4rem;
            color: #FF7043; /* Coral orange */
            font-weight: bold;
        }

        .menu-item .currency {
            color: #1B5E20; /* Forest green */
        }

        /* Footer */
        footer {
            background-color: #5D4037;
            color: #FFD54F;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        footer p {
            font-size: 1rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            section.menu {
                flex-direction: column;
                align-items: center;
            }

            .menu-item {
                width: 90%;
            }
        }
        h1{color:aqua;font-style: italic;text-align: center;}
    </style>
</head>
<body>

<header>
    <h1>MAIN COURSE</h1>
    <img src="https://th.bing.com/th/id/R.a4523098a29319ae4d3a97af9052879c?rik=HK0yU0YyfrW1gA&riu=http%3a%2f%2fjfwonline.com%2fwp-content%2fuploads%2f2016%2f05%2fIndia-Food-JFW-magazine.jpg&ehk=2fep2BJUHns4HRELbvFgE6avYlEW1Vwo7XEn4fef2gY%3d&risl=&pid=ImgRaw&r=0">
</header>
    <h1>ROTI's</h1>
     <section class="menu">
           <div class="menu-item">
        <img src="https://th.bing.com/th/id/OIP.F4zlym5pP97puGQ0IspdjgHaFj?rs=1&pid=ImgDetMain" alt="Tandoori Roti">
        <div class="content">
            <h3>Tandoori Roti</h3>
            <p>Soft and extremely thin Tandoori roti!.</p>
            <p class="price">₹35</p>
            <button class="add-to-cart" onclick="addToCart('Tandoori Roti', 35)">Add to Cart</button>
        </div>
    </div>
    <div class="menu-item">
        <img src="https://i1.wp.com/www.cookingfromheart.com/wp-content/uploads/2016/07/CH_DSC_0050_5.jpg?resize=602%2C800" alt="Rumali Roti">
        <div class="content">
            <h3>Rumali Roti</h3>
            <p>Soft and extremely thin Rumali roti!.</p>
            <p class="price">₹55</p>
            <button class="add-to-cart" onclick="addToCart('Rumali Roti',55)">Add to Cart</button>
        </div>
    </div>
           <div class="menu-item">
        <img src="https://www.cookingclassy.com/wp-content/uploads/2021/01/naan-30.jpg" alt="Naan">
        <div class="content">
            <h3>Naan</h3>
            <p>Super Soft and crispy Naan!.</p>
            <p class="price">₹65</p>
            <button class="add-to-cart" onclick="addToCart('Naan', 65)">Add to Cart</button>
        </div>
    </div>
          <div class="menu-item">
        <img src="https://th.bing.com/th/id/OIP.Qd3JNdcUCVbRYxrfyQzvCgAAAA?rs=1&pid=ImgDetMain" alt="Garlic Naan">
        <div class="content">
            <h3>Garlic Naan</h3>
            <p>Super Soft and crispy Garlic Naan!.</p>
            <p class="price">₹75</p>
            <button class="add-to-cart" onclick="addToCart('Naan', 75)">Add to Cart</button>
        </div>
    </div>
     </section>
<h1>VEG COURSE</h1>
    <section class="menu">
    <div class="menu-item">
        <img src="https://th.bing.com/th/id/R.5ecb9c2a7805690feef3e9273a63139f?rik=Q%2bSfcEGskJ6HRA&riu=http%3a%2f%2fyourcookingpal.com%2fwp-content%2fuploads%2f2016%2f09%2fPaneer-tikkafinal.jpg&ehk=8jvZuuw6YV371YoSB6jZgzSYw4%2b2mvneb8YuDywwef0%3d&risl=&pid=ImgRaw&r=0" alt="Paneer Tikka">
        <div class="content">
            <h3>Paneer Tikka</h3>
            <p>Grilled cottage cheese marinated in spices and yogurt.</p>
            <p class="price">₹150</p>
            <button class="add-to-cart" onclick="addToCart('Paneer Tikka', 150)">Add to Cart</button>
        </div>
    </div>
          <div class="menu-item">
            <img src="https://www.archanaskitchen.com/images/archanaskitchen/Indian_Vegetables_Dry/Mixed_Kadai_Vegetable_Sabzi_North_Indian_Recipe-20.jpg" alt="Veg sabji masala">
            <div class="content">
                <h3>Veg sabji</h3>
                <p>Tasty Veg sabji!.</p>
                <p class="price">₹110</p>
                <button class="add-to-cart" onclick="addToCart('Veg sabji',110)">Add to Cart</button>
            </div>
         </div>
         <div class="menu-item">
            <img src="https://i0.wp.com/vegecravings.com/wp-content/uploads/2016/08/kadai-paneer-gravy-recipe-step-by-step-instructions.jpg?w=1612&quality=65&strip=all&ssl=1" alt="Butter Paneer masala">
            <div class="content">
                <h3>Paneer khadai</h3>
                <p>Tasty Paneer khadai!.</p>
                <p class="price">₹120</p>
                <button class="add-to-cart"onclick="addToCart('Paneer khadai', 120)">Add to Cart</button>
            </div>
         </div>
          <div class="menu-item">
            <img src="https://i.pinimg.com/originals/19/1c/4e/191c4eff8c397430a92e09878145cc4a.jpg" alt="Butter Paneer masala">
            <div class="content">
                <h3>Paneer Butter masala</h3>
                <p>Tasty Paneer butter masala!.</p>
                <p class="price">₹150</p>
                <button class="add-to-cart"onclick="addToCart('Paneer Butter masala', 150)">Add to Cart</button>
            </div>
         </div>
        
        <div class="menu-item">
            <img src="https://as1.ftcdn.net/v2/jpg/02/42/44/44/1000_F_242444417_sAqtlOz7kvdQGhDqCVsRMIfLixMDNmw5.jpg" alt="Paneer Fried Rice ">
            <div class="content">
                <h3>Paneer Fried Rice</h3>
                <p>Schezwan paneer fried rice with Szechuan sauce and cottage cheese cubes.</p>
                <p class="price">₹180</p>
                <button class="add-to-cart" onclick="addToCart('Paneer Fried Rice', 180)">Add to Cart</button>
            </div>
    </div>
       <div class="menu-item">
        <img src="https://th.bing.com/th/id/OIP.Wiw3y-pnb0KqoPH3rngKnAHaGd?rs=1&pid=ImgDetMain" alt="Veg Biriyani ">
        <div class="content">
            <h3>Veg Biriyani</h3>
            <p>Delicious mouth watering Veg Biriyani!.</p>
            <p class="price">₹200</p>
            <button class="add-to-cart"onclick="addToCart('Veg Biriyani', 200)">Add to Cart</button>
        </div>
    </div>
                <div class="menu-item">
            <img src="https://spicecravings.com/wp-content/uploads/2017/09/IMG_3134-copy-e1579798948176.jpg" alt="Paneer Fried Rice ">
            <div class="content">
                <h3>Paneer biriyani</h3>
                <p>Yummy Paneer biriyani with veggies and spices.</p>
                <p class="price">₹280</p>
                <button class="add-to-cart"onclick="addToCart('Paneer biriyani', 280)">Add to Cart</button>
            </div>
    </div>
    </section>
    <h1>NON-VEG COURSE</h1>
    <section class="menu">
     <div class="menu-item">
    <img src="https://th.bing.com/th/id/OIP._es8WRlqhIaEyjV2KqMYRwHaEK?rs=1&pid=ImgDetMain" alt=" ">
    <div class="content">
        <h3>Egg budji</h3>
        <p>One pot delicious Egg budji made Eggs, spices & herbs.</p>
        <p class="price">₹150</p>
        <button class="add-to-cart"onclick="addToCart('Egg budji', 150)">Add to Cart</button>
    </div>
</div>
        <div class="menu-item">
    <img src="https://www.hyderabadiruchulu.com/wp-content/uploads/2019/06/Egg-Gravy-CurryThumbnail.jpg" alt=" ">
    <div class="content">
        <h3>Egg gravy</h3>
        <p>One pot delicious Egg gravy made Eggs, spices & herbs.</p>
        <p class="price">₹180</p>
        <button class="add-to-cart"onclick="addToCart('Egg gravy', 180)">Add to Cart</button>
    </div>
</div>
    <div class="menu-item">
    <img src="https://www.licious.in/blog/wp-content/uploads/2020/10/butter-chicken--750x750.jpg" alt=" ">
    <div class="content">
        <h3>Butter chicken</h3>
        <p>One pot delicious Butter chicken made fresh chicken, spices & herbs.</p>
        <p class="price">₹210</p>
        <button class="add-to-cart"onclick="addToCart('Butter chicken', 210)">Add to Cart</button>
    </div>
</div>
        <div class="menu-item">
    <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2020/02/instant-pot-egg-biryani.jpg" alt="Egg Dum Biryani ">
    <div class="content">
        <h3>Egg Dum Biryani</h3>
        <p>One pot delicious egg biryani made with basmati rice, boiled eggs, spices & herbs.</p>
        <p class="price">₹350</p>
        <button class="add-to-cart"onclick="addToCart('Egg Dum Biriyani', 350)">Add to Cart</button>
    </div>
</div>
        <div class="menu-item">
        <img src="https://masalaandchai.com/wp-content/uploads/2022/03/Butter-Chicken.jpg" alt="">
        <div class="content">
            <h3>Butter Chicken</h3>
            <p>Delicious creamy chicken cooked in a buttery tomato gravy.</p>
            <p class="price">₹450</p>
            <button class="add-to-cart"onclick="addToCart('Butter Chicken', 450)">Add to Cart</button>
        </div>
    </div>
          <div class="menu-item">
        <img src="https://vismaifood.com/storage/app/uploads/public/980/eb9/ed6/thumb__700_0_0_0_auto.jpg" alt="Mutton Dum Biryani ">
        <div class="content">
            <h3>Mutton Dum Biryani</h3>
            <p>Hyderabad Bawarchi Style Mutton Dum Biryani.</p>
            <p class="price">₹500</p>
            <button class="add-to-cart"onclick="addToCart('Mutton Dum Biriyani', 500)">Add to Cart</button>
        </div>
</div>



</section>
    <h2>Your Cart</h2>
<section id="cart-section">
    <ul id="cart-list">
        <!-- Cart items will appear here -->
    </ul>
    <p id="cart-total">Total: ₹0</p>
</section>
<footer>
    <p>&copy; 2024 5-Star Hotel | All Rights Reserved</p>
</footer>
<script>
// Cart array to store added items
let cart = [];

// Function to add item to the cart
function addToCart(itemName, itemPrice) {
    // Create an object for the item
    const item = {
        name: itemName,
        price: itemPrice
    };

    // Add item to the cart
    cart.push(item);
    updateCart();
}

// Function to update the cart display
function updateCart() {
    const cartList = document.getElementById('cart-list');
    const cartTotal = document.getElementById('cart-total');

    // Clear the current list
    cartList.innerHTML = '';

    // Add each item to the cart display
    cart.forEach((item, index) => {
        const listItem = document.createElement('li');
        listItem.textContent =` ${item.name} - ₹${item.price}`;
        cartList.appendChild(listItem);
    });

    // Calculate total price
    const totalPrice = cart.reduce((total, item) => total + item.price, 0);

    // Update total price
    cartTotal.textContent = Total: ₹${totalPrice};
}

// Event listener for all "Add to Cart" buttons
document.querySelectorAll('.add-to-cart').forEach((button) => {
    button.addEventListener('click', function () {
        const itemName = this.parentElement.querySelector('h3').textContent;  // Get item name
        const itemPrice = parseInt(this.parentElement.querySelector('.price').textContent.replace('₹', ''));  // Get item price
        
        // Call addToCart function with the correct parameters
        addToCart(itemName, itemPrice);
    });
});
</script>

</body>
</html>

<footer>
    <p>&copy; 2024 5-Star Hotel | All Rights Reserved</p>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>5-Star Hotel Menu</title>
    <style>
        /* Global styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        /* Body styles */
        body {
            background-color: #3E2723; /* Deep brown */
            color: #FAFAFA; /* Light text */
            line-height: 1.6;
        }

        /* Header */
        header {
            background-color: #5D4037; /* Chocolate brown */
            color: #FFD54F; /* Golden yellow */
            text-align: center;
            padding: 2rem 1rem;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px #000;
        }

        header p {
            font-size: 1.5rem;
        }

        /* Menu Section */
        section.menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2rem 1rem;
        }

        .menu-item {
            background-color: #FFF8E1; /* Light cream */
            border: 1px solid #E0E0E0;
            border-radius: 10px;
            overflow: hidden;
            width: 300px;
            margin: 1rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }

        .menu-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .menu-item .content {
            padding: 1rem;
            text-align: center;
        }

        .menu-item h3 {
            font-size: 1.8rem;
            color: #D84315; /* Burnt orange */
            margin-bottom: 0.5rem;
        }

        .menu-item p {
            font-size: 1rem;
            color: #5D4037; /* Chocolate brown */
        }

        .menu-item .price {
            font-size: 1.4rem;
            color: #FF7043; /* Coral orange */
            font-weight: bold;
        }

        .menu-item .currency {
            color: #1B5E20; /* Forest green */
        }

        /* Footer */
        footer {
            background-color: #5D4037;
            color: #FFD54F;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        footer p {
            font-size: 1rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            section.menu {
                flex-direction: column;
                align-items: center;
            }

            .menu-item {
                width: 90%;
            }
        }

        h1 {
            color: aqua;
            font-style: italic;
            text-align: center;
        }

        h2 {
            color: aqua;
            font-style: italic;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    <h1>5-Star Hotel Menu</h1>
    <img src="https://static.wixstatic.com/media/d081cc_dd69781c4fe740dcb382d1593f2d250f~mv2.jpg/v1/fill/w_900,h_600,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/d081cc_dd69781c4fe740dcb382d1593f2d250f~mv2.jpg" alt="Hotel Image">
    <h1>DESERTS</h1><br>
</header>

<section class="menu">
    <div class="menu-item">
        <img src="https://i.pinimg.com/736x/93/68/3b/93683ba80c7c95d1e83bed37a31cfcbe.jpg" alt="Chocolate Cake">
        <div class="content">
            <h3>Chocolate Cake</h3>
            <p>A rich and indulgent chocolate cake topped with ganache.</p>
            <p class="price">₹250</p>
            <button class="add-to-cart" onclick="addToCart('Chocolate Cake', 250)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://www.ainsley-harriott.com/app/uploads/2020/09/Tiramisu-IMG_9011-TX1-818x1024.jpg" alt="Tiramisu">
        <div class="content">
            <h3>Tiramisu</h3>
            <p>Classic Italian dessert with coffee-soaked layers and mascarpone cream.</p>
            <p class="price">₹300</p>
            <button class="add-to-cart" onclick="addToCart('Tiramisu', 300)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://www.cookingclassy.com/wp-content/uploads/2019/11/cheesecake-8.jpg" alt="Cheesecake">
        <div class="content">
            <h3>Cheesecake</h3>
            <p>Delicious cheesecake with a graham cracker crust and a creamy filling.</p>
            <p class="price">₹350</p>
            <button class="add-to-cart" onclick="addToCart('Cheesecake', 350)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://imhungryforthat.com/wp-content/uploads/2021/01/Best-Easy-Vegan-Apple-Pie-Recipe.jpg" alt="Apple Pie">
        <div class="content">
            <h3>Apple Pie</h3>
            <p>Classic apple pie with a buttery, flaky crust.</p>
            <p class="price">₹180</p>
            <button class="add-to-cart" onclick="addToCart('Apple Pie', 180)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://www.thecountrycook.net/wp-content/uploads/2021/03/1st-image-HOMEMADE-VANILLA-PUDDING-1455x2048.jpg" alt="Vanilla Pudding">
        <div class="content">
            <h3>Vanilla Pudding</h3>
            <p>A silky smooth vanilla pudding topped with whipped cream.</p>
            <p class="price">₹160</p>
            <button class="add-to-cart" onclick="addToCart('Vanilla Pudding', 160)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://lilluna.com/wp-content/uploads/2012/04/frosted-brownies-resize-9.jpg" alt="Brownie">
        <div class="content">
            <h3>Brownie</h3>
            <p>Rich and fudgy brownie with a soft center.</p>
            <p class="price">₹220</p>
            <button class="add-to-cart" onclick="addToCart('Brownie', 220)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://lovefoodfeed.com/wp-content/uploads/2023/01/Macarons-px-1200-01-1-1024x1024.jpg" alt="Macaron">
        <div class="content">
            <h3>Macaron</h3>
            <p>Delicate and colorful French macarons with a creamy filling.</p>
            <p class="price">₹150</p>
            <button class="add-to-cart" onclick="addToCart('Macaron', 150)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://www.cucinabyelena.com/wp-content/uploads/2023/06/Panna-Cotta-28-1.jpg" alt="Panna Cotta">
        <div class="content">
            <h3>Panna Cotta</h3>
            <p>A creamy Italian dessert with a vanilla flavor and a sweet berry sauce.</p>
            <p class="price">₹270</p>
            <button class="add-to-cart" onclick="addToCart('Panna Cotta', 270)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://th.bing.com/th/id/OIP.JDu5W1pALSp_WwXDU9EO0AHaHu?w=959&h=1000&rs=1&pid=ImgDetMain" alt="Ice Cream">
        <div class="content">
            <h3>Ice Cream</h3>
            <p>Refreshing ice cream in chocolate, vanilla, and strawberry flavors.</p>
            <p class="price">₹120</p>
            <button class="add-to-cart" onclick="addToCart('Ice Cream', 120)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://www.janespatisserie.com/wp-content/uploads/2015/07/img_2521.jpg" alt="Lemon Meringue Pie">
        <div class="content">
            <h3>Lemon Meringue Pie</h3>
            <p>A zesty lemon filling topped with a toasted meringue.</p>
            <p class="price">₹220</p>
            <button class="add-to-cart" onclick="addToCart('Lemon Meringue Pie', 220)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://www.recipetineats.com/wp-content/uploads/2016/09/Creme-Brulee_7.jpg" alt="Creme Brulee">
        <div class="content">
            <h3>Creme Brulee</h3>
            <p>A custard dessert with a rich vanilla flavor and a crispy caramelized sugar top.</p>
            <p class="price">₹350</p>
            <button class="add-to-cart" onclick="addToCart('Creme Brulee', 350)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://th.bing.com/th/id/OIP.ePhzZTEnX6Vs0jOmUI753QAAAA?w=360&h=450&rs=1&pid=ImgDetMain" alt="Carrot Cake">
        <div class="content">
            <h3>Carrot Cake</h3>
            <p>A moist cake made with fresh carrots and cream cheese frosting.</p>
            <p class="price">₹200</p>
            <button class="add-to-cart" onclick="addToCart('Carrot Cake', 200)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://4h.no/getfile.php/1353034-1596020562/Prosjektplattformen/Oppdrag/Bilder/Helse/cupcakes-1.jpg%20(optimized_original).jpg" alt="Cupcakes">
        <div class="content">
            <h3>Cupcakes</h3>
            <p>Delicious cupcakes topped with buttercream frosting.</p>
            <p class="price">₹150</p>
            <button class="add-to-cart" onclick="addToCart('Cupcakes', 150)">Add to Cart</button>
        </div>
    </div>

    <div class="menu-item">
        <img src="https://celebratingsweets.com/wp-content/uploads/2018/06/Strawberry-Shortcake-Cake-1-1.jpg" alt="Strawberry Shortcake">
        <div class="content">
            <h3>Strawberry Shortcake</h3>
            <p>A dessert with layers of light sponge, fresh strawberries, and whipped cream.</p>
            <p class="price">₹210</p>
            <button class="add-to-cart" onclick="addToCart('Strawberry Shortcake', 210)">Add to Cart</button>
        </div>
    </div>
</section>



<h2>Your Cart</h2>
<section id="cart-section">
    <ul id="cart-list">
        <!-- Cart items will appear here -->
    </ul>
    <p id="cart-total">Total: ₹0</p>
</section>

<footer>
    <p>&copy; 2024 5-Star Hotel | All Rights Reserved</p>
</footer>

<script>
    let cart = [];

// Function to add item to the cart
function addToCart(itemName, itemPrice) {
    // Create an object for the item
    const item = {
        name: itemName,
        price: itemPrice
    };

    // Add item to the cart
    cart.push(item);
    updateCart();
}

// Function to update the cart display
function updateCart() {
    const cartList = document.getElementById('cart-list');
    const cartTotal = document.getElementById('cart-total');

    // Clear the current list
    cartList.innerHTML = '';

    // Add each item to the cart display
    cart.forEach((item, index) => {
        const listItem = document.createElement('li');
        listItem.textContent =` ${item.name} - ₹${item.price}`;
        cartList.appendChild(listItem);
    });

    // Calculate total price
    const totalPrice = cart.reduce((total, item) => total + item.price, 0);

    // Update total price
    cartTotal.textContent = Total: ₹${totalPrice};
}

// Event listener for all "Add to Cart" buttons
document.querySelectorAll('.add-to-cart').forEach((button) => {
    button.addEventListener('click', function () {
        const itemName = this.parentElement.querySelector('h3').textContent;  // Get item name
        const itemPrice = parseInt(this.parentElement.querySelector('.price').textContent.replace('₹', ''));  // Get item price
        
        // Call addToCart function with the correct parameters
        addToCart(itemName, itemPrice);
    });
});
</script>

</body>
</html>

