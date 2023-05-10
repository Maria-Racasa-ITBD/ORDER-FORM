<!DOCTYPE html>
<html>
<head>
	<title>ORDER FORM</title> 
	<style>
		body {
			font-family: Arial, sans-serif;
			background-color: gray;
		}
		h1 {
			text-align: center;
			color: #FFC02E;
			margin-top: 30px;
		}
		form {
			max-width: 800px;
			margin: 0 auto;
			background-color: beige;
			padding: 20px;
			border-radius: 5px;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
		}
		label {
			display: block;
			font-size: 18px;
			font-weight: bold;
			margin-bottom: 10px;
			color: #555;
		}
        img{
			width:fit-content:auto;
			height:200px
        }
		input[type="text"],
		select,
		textarea {
			width: 100%;
			padding: 10px;
			font-size: 16px;
			border-radius: 5px;
			border: 1px solid #ccc;
			margin-bottom: 20px;
			box-sizing: border-box;
		}
		input[type="radio"],
		input[type="checkbox"] {
			margin-right: 10px;
		}
		button[type="submit"],
		button[type="reset"] {
			background-color: #FF5733;
			color: #fff;
			padding: 10px 20px;
			font-size: 16px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
			transition: background-color 0.3s ease;
		}
		button[type="submit"]:hover,
		button[type="reset"]:hover {
			background-color: #FF8A66;
		}
	</style>
</head>
<body>
<h1>Pizza Order Form</h1>
	<form action="#" method="post">
		<h2>Customer Information</h2>
		<label for="fullname">Full Name:</label>
		<input type="text" id="fullname" name="fullname" required>

		<label for="address">Complete Address:</label>
		<input type="text" id="address" name="address" required>

		<label for="contact">Contact Number:</label>
		<input type="text" id="contact" name="contact" required>

		<label for="email">Email Address:</label>
		<input type="email" id="email" name="email" required>

		<label for="directions">Directions to the Place:</label>
		<textarea id="directions" name="directions"></textarea>

		<h2>Order Information</h2>
		<h3>Burgers</h3>
        <img src="CABALQUINTO_IMAGES_ITBD/burg.jpeg" alt="Burger">
		<p>Choose your burger:</p>
		<input type="radio" id="single" name="burger" value="single patty" required><img class="Pat" src="CABALQUINTO_IMAGES_ITBD/Single pat Background Removed.png" alt="Burger">
		<label for="single">Single Patty</label>

		<input type="radio" id="double" name="burger" value="double patty"><img class="Pat" src="CABALQUINTO_IMAGES_ITBD/Double Pat Background Removed.png" alt="Burger">
		<label for="double">Double Patty</label>

		<p>Select your toppings:</p>
		<input type="checkbox" id="cheese" name="topping[]" value="cheese"><img class="Pat" src="CABALQUINTO_IMAGES_ITBD/kiso Background Removed.png" alt="Burger">
		<label for="cheese">Cheese</label>

		<input type="checkbox" id="coleslaw" name="topping[]" value="coleslaw"><img class="Pat" src="CABALQUINTO_IMAGES_ITBD/coolslow Background Removed.png" alt="Burger">
		<label for="coleslaw">Coleslaw</label>

		<input type="checkbox" id="tomato" name="topping[]" value="tomato"><img class="Pat" src="CABALQUINTO_IMAGES_ITBD/tomato Background Removed.png" alt="Burger">
		<label for="tomato">Tomato</label>

		<input type="checkbox" id="onion" name="topping[]" value="onion"><img class="Pat" src="CABALQUINTO_IMAGES_ITBD/onion Background Removed.png" alt="Burger">
		<label for="onion">Onion</label>

		<input type="checkbox" id="cucumber" name="topping[]" value="cucumber"><img class="Pat" src="CABALQUINTO_IMAGES_ITBD/cucumber Background Removed.png" alt="Burger">
		<label for="cucumber">Cucumber</label>

		<input type="checkbox" id="bacon" name="topping[]" value="bacon"><img class="Pat" src="CABALQUINTO_IMAGES_ITBD/bacon Background Removed.png" alt="Burger">
		<label for="bacon">Bacon</label>

		<p>Choose your bun:</p>
		<select id="bun" name="bun" required>
			<option value="white bun">White Bun</option>
			<option value="wheat bun">Wheat Bun</option>
			<option value="honey oat">Honey Oat</option>
			<option value="sugar-free">Sugar-free</option>
		</select>

		<label for="burger-quantity">Quantity:</label>
		<input type="number" id="burger-quantity" name="burger-quantity" required>

    <form>
      <label for="sauce">Pasta:</label>
      <select id="sauce" name="sauce">
        <option value="carbonara">Carbonara</option>
        <option value="pesto">Pesto</option>
        <option value="spaghetti">Spaghetti</option>
      </select>
      
      <label for="add-ons">Add-ons:</label>
      <input type="checkbox" id="extra-cheese" name="extra-cheese" value="extra-cheese">
      <label for="extra-cheese">Extra Cheese</label>
      <input type="checkbox" id="extra-sauce" name="extra-sauce" value="extra-sauce">
      <label for="extra-sauce">Extra Sauce</label>
      
      <label for="quantity">Quantity (per box):</label>
      <input type="number" id="quantity" name="quantity" min="1" value="1">
      

		<h2>Fries</h2>
		<label for="size">Size:</label>
		<select id="size" name="size">
			<option value="small">Small</option>
			<option value="medium">Medium</option>
			<option value="large">Large</option>
		</select>
		<label for="flavor">Flavor:</label>
		<select id="flavor" name="flavor">
			<option value="bbq">BBQ</option>
			<option value="cheese">Cheese</option>
			<option value="sour-cream">Sour Cream</option>
		</select>
		<label for="fries-quantity">Quantity:</label>
		<input type="number" id="fries-quantity" name="fries-quantity" min="1" value="1">

		<h2>Drinks</h2>
		<label for="drink-type">Drink Type:</label>
		<select id="drink-type" name="drink-type">
			<option value="soda">Soda</option>
			<option value="juice">Juice</option>
			<option value="water">Water</option>
		</select>
		<label for="drink-size">Size:</label>
		<select id="drink-size" name="drink-size">
			<option value="small">Small</option>
			<option value="medium">Medium</option>
			<option value="large">Large</option>
		</select>
		<label for="drink-quantity">Quantity:</label>
		<input type="number" id="drink-quantity" name="drink-quantity" min="1" value="1">

		<h2>Feedback</h2>
		<label for="feedback">How can we improve the ordering form?</label>
		<textarea id="feedback" name="feedback"></textarea>

		<h2>Delivery</h2>
		<label for="delivery-method">Delivery or Pick-up:</label>
		<input type="radio" id="delivery" name="delivery-method" value="delivery">
		<label for="delivery">Delivery</label>
		<input type="radio" id="pick-up" name="delivery-method" value="pick-up">
		<label for="pick-up">Pick-up</label>
    
    <button type="submit">Submit Order</button>
		<button type="reset">Clear Form</button>
</body>
</html>
