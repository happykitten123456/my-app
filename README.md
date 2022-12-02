In the Github Repository for this assignment, please include the following in a README file in the root directory of your repository:
1. Describe the goal of the application and value to a user

2. Link to your deployed web application running online
https://happykitten123456.github.io/legging/

3. Explain the organization of your Components, and the props and state related to them

I have 6 components:

Component 1: App. (in App.js) State for this component is product list and cart list. Product list is to show items that matches the criterias. Cart list is to save items that are added to cart.

Component 2: Meun. (in Menu.js) State for this component is size, length, and sortType. Props has a function named "filterFuc" that pass the state to product list. This information will be used by the APP component.

Component 3: ProductItem. (in ProductList.js) Props is the a product in dataset. This component will return a card for an item.

Component 4: ProductList. (in ProductList.js) Props is a list of products in dataset. This component will return a series of items that matches the critera. 

Component 5: CartItem. (in Cart.js) Props is the product that users add to cart (includig title, number of items, and price), an add function, an a remove function. This component is use to update the shopping cart for each item.

Component 6: Cart. (in Cart.js) Props is a list of items in the cart, an add function, and a remove function. This component is use to display the shopping cart, and calculate the total number of items purchased and total prices.

For example:

If you select "Medium-25''-sort by price", filterFuc in Menu.js will pass the state (size, length, sortType) to filterProductList in App.js. filterProductList will select the data that matches these critera and update the ProductList.js. ProductList.js will return all the items and display in the page.

If you press "Add to cart", the product id will be passed to addProductItem in App.js. The information of the selected data will be passed to CartList in App.js. The change in CartList will be notify to component CartItem and Cart. They will calculate the total price and print cart information.

4. Note the usability principles considered for layout and hierarchy


