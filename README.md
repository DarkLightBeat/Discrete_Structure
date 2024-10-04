<h1> MSEUF Portal Technology Co. </h1> 

This is a basic HTML, CSS, and JavaScript for a technology corporation portal. The portal allows users to choose a category and redirects them to the corresponding category page.

<h3> displayCart() Function </h3>

The displayCart() function is responsible for displaying the shopping cart items. 
Here's what it does:

Retrieves the cart data from localStorage using JSON.parse(localStorage.getItem('cart')). If the cart is empty, it defaults to an empty array [].
<br>
Gets references to the cart-list and cart-total elements using document.getElementById.
<br>
Clears the cart-list element's inner HTML.
<br>
Loops through each item in the cart using cart.forEach((item) => { ... }).
<br>
For each item, it creates a new li element with the class cart-item and appends it to the cart-list element.
<br>
Creates an img element with the item's image URL, a p element with the item's name, a p element with the item's price, and a span element with the "Remove" text.
<br>
Adds an event listener to the "Remove" span element to remove the item from the cart when clicked.
<br>
Calculates the total price of the items in the cart and updates the cart-total element's text content.
<br>
<br>
<h3> handleCheckout() Function </h3>

The handleCheckout() function is responsible for handling the checkout functionality. 
Here's what it does:

Clears the cart by setting localStorage to an empty array [].
<br>
Redirects the user to the main page (Combination.html) using window.location.href.
