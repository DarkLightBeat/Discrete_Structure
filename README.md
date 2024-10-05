<h1> Documentation for MSEUF Portal Technology Co. </h1>

<h2> Overview </h2>

The MSEUF Portal Technology Co. is a web-based application that allows users to browse and purchase various technology products. The application consists of two main pages: the main page and the shopping cart page.

<h2> Main Page </h2>

The main page displays a list of categories, each representing a type of technology product. Users can click on a category to view the corresponding products. The page also includes a "View Cart" button that allows users to view their shopping cart.

<h2> Shopping Cart Page </h2>

The shopping cart page displays a list of products added to the cart, along with their prices and a "Remove" button to remove each item. The page also displays the total cost of the items in the cart and includes a "Checkout" button to complete the purchase.

<h1> Code Explanation </h1>

<h2> Main Page </h2>

The main page uses HTML, CSS, and JavaScript to create a responsive and interactive user interface. The CSS styles are used to create a modern and visually appealing design. The JavaScript code is used to add event listeners to the category items, which redirect the user to the corresponding category page when clicked.

<h2> Shopping Cart Page </h2>

The shopping cart page uses HTML, CSS, and JavaScript to create a responsive and interactive user interface. The CSS styles are used to create a modern and visually appealing design. The JavaScript code is used to:


<li> Display the shopping cart items and their prices </li>
<li> Update the total cost of the items in the cart </li>
<li> Remove items from the cart when the "Remove" button is clicked </li>
<li> Clear the cart and redirect the user to the main page when the "Checkout" button is clicked </li>

<h1> Logic of the Code </h1>


<h2> The code uses the following logic: </h2>

<ol> The main page uses JavaScript to add event listeners to the category items, which redirect the user to the corresponding category page when clicked. </ol>
<ol> The shopping cart page uses JavaScript to display the shopping cart items and their prices, update the total cost of the items in the cart, and remove items from the cart when the "Remove" button is clicked. </ol>
<ol> The shopping cart page also uses JavaScript to clear the cart and redirect the user to the main page when the "Checkout" button is clicked. </ol>

<h1> User Interaction </h1>

<h2> Users can interact with the application by: </h2>

<ol> Browsing the categories on the main page and clicking on a category to view the corresponding products </ol>
<ol> Adding products to the shopping cart by clicking on the category item </ol>
<ol> Viewing the shopping cart and removing items by clicking on the "Remove" button </ol>
<ol> Completing the purchase by clicking on the "Checkout" button </ol>

<h1> Running the System </h1>

To run the system, simply open the HTML files in a web browser. The application does not require any command-line interface (CLI) or graphical user interface (GUI) inputs.

<h1> Formula Used </h1>

The application does not use any specific formulas, as it is a simple e-commerce application. However, the total cost of the items in the cart is calculated by summing up the prices of each item.

<h1> Additional Pages </h1>

<p> The application also includes additional pages for each category, which display a list of products and their prices. These pages use the same HTML, CSS, and JavaScript code as the main page and shopping cart page. </p>

<h3> Headsets Page </h3>

The Headsets page displays a list of headsets and their prices. The page includes a "Buy Now" button for each product, which adds the product to the shopping cart when clicked.

<h3> Monitors Page </h3>

The Monitors page displays a list of monitors and their prices. The page includes a "Buy Now" button for each product, which adds the product to the shopping cart when clicked.

<h3> Mouse Page </h3>

The Mouse page displays a list of mice and their prices. The page includes a "Buy Now" button for each product, which adds the product to the shopping cart when clicked.

<h3> Printers Page </h3>

The Printers page displays a list of printers and their prices. The page includes a "Buy Now" button for each product, which adds the product to the shopping cart when clicked.

<h3> Processors Page </h3>

The Processors page displays a list of processors and their prices. The page includes a "Buy Now" button for each product, which adds the product to the shopping cart when clicked.

<h3> Storage Page </h3>

The Storage page displays a list of storage devices and their prices. The page includes a "Buy Now" button for each product, which adds the product to the shopping cart when clicked.

<h2> Adding Products to the Cart </h2>

When a buy-now-button is clicked, the script:

<li> Prevents the default behavior of the button using e.preventDefault(). </li>
<li> Retrieves the product name, price, and image from the button's parent element and attributes. </li>
<li> Checks if the product is already in the cart by searching for an item with the same name in the cart array. If it exists, an alert is displayed, and the function returns. </li>
<li> If the product is not in the cart, it is added to the cart array with its name, price, and image. </li>
<li> The cart array is then stored in local storage using localStorage.setItem. </li>
<li> The cart count is updated by selecting the element with the class cart-count and setting its text content to the length of the cart array. </li>
<li> An alert is displayed to confirm that the product has been added to the cart. </li>

<h2> Displaying the Cart Contents </h2>
The displayCart function is responsible for displaying the contents of the cart, the purpose of this is to:

<li> Retrieves the cart array from local storage using JSON.parse and localStorage.getItem. </li>
<li> Selects the elements with the IDs cart-list and cart-total. </li>
<li> Clears the inner HTML of the cart-list element. </li>
<li> Loops through each item in the cart array and creates a new list item element with the product name and price. </li>
<li> Appends the list item to the cart-list element. </li>
<li> Calculates the total price of the items in the cart and sets the text content of the cart-total element to the total price.

<h2> View Cart Button </h2>
When a view cart button is clicked, It display. </li>

