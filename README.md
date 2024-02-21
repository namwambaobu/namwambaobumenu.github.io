<!DOCTYPE html>
<html lang ="en">
<head>
	<meta charset="UTF-8">
	<!--For the styling of the page to look similar on mobile as it does on a desktop or laptop, you need to add a meta element with a special content attribute.

Add the following within the head element:

<meta name="viewport" content="width=device-width, initial-scale=1.0" />-->

	<meta name="viewport" content="width=device-width, initial-scale=1.0" />

	<title>Cafe Menu</title>
	<link rel="stylesheet" href="menu.css">
<!--You now have three type selectors with the exact same styling. You can add the same group of styles to many elements by creating a list of selectors. Each selector is separated with commas like this:

selector1, selector2 {
  property: value;
}
Delete the three existing type selectors and replace them with one selector list that centers the text for the h1, h2, and p elements.-->
</head>
<body>
	<!--The div element is used mainly for design layout purposes unlike the other content elements you have used so far. Add a div element inside the body element and then move all the other elements inside the new div.
    Inside the opening div tag, add the id attribute with a value of menu.-->
	<div class ="menu">
    <main>
		<h1>CAMPER CAFE</h1>
		<p class="start">Est. 2020</p>
		<hr>
		<section>
			<h2>Coffee</h2>
			 <img src="https://cdn.freecodecamp.org/curriculum/css-cafe/coffee.jpg" alt="coffee icon">
			<article class="item">
				<p class="flavor">French Vanilla</p><p class="price">$3.00</p>
			</article>
            <article class="item">
            	<p class="flavor">Caramel Macchiato</p><p class="price">$3.75</p>
            </article>
            <article class="item">
            	<p class="flavor">Pumpkin Spice</p><p class="price">$3.50</p>
            </article>
            <article class="item">
            	<p class="flavor">Hazelnut</p><p class="price">$4.00</p>
            </article>
            <article class="item">
            	<p class="flavor">Mocha</p><p class="price">$4.50</p>
            </article>
            
		</section>
		<section>
			<h2>Desserts</h2>
			<img src="https://cdn.freecodecamp.org/curriculum/css-cafe/pie.jpg" alt="pie icon">
			<article class="item">
				<p class="dessert">Donut</p><p class="price">$1.50</p></article>
				<article>
				<article class="item"><p class="dessert">Cherry pie</p><p class="price">$2.75</p></article>
				<article class="item"><p class="dessert">Cheesecake</p><p class="price">$3.00</p></article>
				<article class="item"><p class="dessert">Cinnamon Roll</p><p class="price">$2.50</p></article>
		</section>
	</main>
	<hr class="bottom-line">
	<footer>
		 <p> <a href="https://www.freecodecamp.org">Visit our website</a></p>
		   <p class="address">123 Free Code Camp Drive</p>
	</footer>
</div>
</body>
</html>
