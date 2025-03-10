<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Supermarket Billing System</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Supermarket Billing System</h1>

        <!-- Product List -->
        <div class="products">
            <div class="product" data-name="Apple" data-price="20">
                <p>Apple - ₹20</p>
                <button onclick="addToCart('Apple', 20)">Add</button>
            </div>
            <div class="product" data-name="Milk" data-price="30">
                <p>Milk - ₹30</p>
                <button onclick="addToCart('Milk', 30)">Add</button>
            </div>
            <div class="product" data-name="Bread" data-price="40">
                <p>Bread - ₹40</p>
                <button onclick="addToCart('Bread', 40)">Add</button>
            </div>
        </div>

        <!-- Shopping Cart -->
        <div class="cart">
            <h2>Cart</h2>
            <ul id="cart-items"></ul>
            <p>Total: $<span id="total">0</span></p>
            <button onclick="checkout()">Checkout</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: 
    text-align: center;
    margin: 20px;
}

.container {
    background: white;
    padding: 20px;
    width: 50%;
    margin: auto;
    box-shadow: 0px 0px 10px gray;
    border-radius: 8px;
}

h2 {
    color: 
}

.billing-form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

input {
    padding: 8px;
    margin: 5px;
    width: 80%;
    border: 1px solid 
    border-radius: 4px;
}

button {
    background: green;
    color: white;
    border: none;
    padding: 10px;
    width: 50%;
    margin-top: 10px;
    cursor: pointer;
    border-radius: 4px;
}

button:hover {
    background: darkgreen;
}

table {
    width: 100%;
    margin-top: 20px;
    border-collapse: collapse;
}

th, td {
    border: 1px solid 
    padding: 10px;
    text-align: center;
}

th {
    background: 
    color: white;
}

h3 {
    color: 
    margin-top: 20px;
}
