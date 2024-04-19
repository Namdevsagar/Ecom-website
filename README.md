
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Shopping Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #87CEFA;
            color: yellow;
            padding: 20px;
            text-align: center;
        }
		@keyframes colorchange1 {
			0%{color: white;}
			25%{color: black;}
			50%{color: red;}
			75%{color: orange;}
			100%{color: yellow;}
		}
        nav {
            background-color: #0000CD;
            padding: 10px;
            text-align: right;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
		a {
			top-margin: 12px;
		}
        section {
            padding: 20px;
			background-color: #4682B4;
			margin-left: 30px;
			margin-right: none;
			margin-top: 10px;
			margin-bottom: 100px;
        }
        .product {
            
            border-radius: 10px;
            padding: 10px;
            margin-bottom: none;
            display: inline-block;
            width: 30%;
            margin-right: 2%;
			background-color: white;
        }
        .product img {
            width: 100%;
			height: 220px;
			
        }
        .product h3 {
            margin-top: 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1 style="animation-name: colorchange1; animation-duration: 10s; animation-timing-function: infinite; animation-iteration-count: infinite;">Welcome to S.J. Store</h1>
    </header>
    <nav>
		
			<button style="position: left; background-color: grey; color: white; margin-right: 900px;" title="Not available Now">☰</button>
			<input type="search" name="" placeholder="type to text" style="border-radius: 10px; border: 5px; text-align: left;">
			<a href="#"><button class="btn" style="background-color: grey; color: white; border-radius: 10px; text-align: left;" onclick="myfunction()">search</button></a>
		<a href="#" style="text-align: right;">Home</a>
        <a href="#" style="text-align: right;">Products</a>
        <a href="#" style="text-align: right;">About Us</a>
        <a href="#" style="text-align: right;">Contact</a>
		<br>
		
        
		
    </nav>
	<marquee style="color: green; line-height: 2;" class="a"><b>This website have only well Qualified Products and Services.</b> </marquee>
    <section>
        <div class="product">
            <img src="keyboard.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p style="color: #00008B">$299.99</p>
            <button title="Out of Stock" onclick="ab()">Add to Cart</button>
        </div>
        <div class="product">
            <img src="mouse.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p style="color: #00008B">$100.99</p>
            <button title="Out of Stock" onclick="ab()">Add to Cart</button>
        </div>
        <div class="product">
            <img src="cpu.jpg" alt="Product 3">
            <h3>Product 3</h3>
            <p style="color: #00008B">$120.99</p>
            <button title="Out of Stock" onclick="ab()">Add to Cart</button>
        </div>
		<div class="product">
            <img src="webcam.jpg" alt="Product 1">
            <h3>Product 4</h3>
            <p style="color: #00008B">$299.99</p>
            <button title="Out of Stock" onclick="ab()">Add to Cart</button>
        </div>
        <div class="product">
            <img src="scanner.jpg" alt="Product 2">
            <h3>Product 5</h3>
            <p style="color: #00008B">$100.99</p>
            <button title="Out of Stock" onclick="ab()">Add to Cart</button>
        </div>
        <div class="product">
            <img src="speaker.jpg" alt="Product 3">
            <h3>Product 6</h3>
            <p style="color: #00008B">$120.99</p>
            <button title="Out of Stock" onclick="ab()">Add to Cart</button>
        </div>
    </section>
	<script>
		function myfunction()
		{
			alert("Something Happened!");
		}
		function ab()
		{
			alert("ERROR! Try Again Later");
		}
	</script>
    <footer>
        <p>&copy; 2024 My Shopping Website. All rights reserved.</p>
    </footer>
</body>
</html>
