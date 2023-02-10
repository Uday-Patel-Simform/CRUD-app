# CRUD-app

Created a Product Management system where product contains following attributes.
ProductId
ProductName
Image
Price
Description

This application allow user to create new product, update existing product and user is able to filter product by product id and able to sort it by productId, Product Name and Price.Used localStorage for storing product.

index.html file contains navigation bar and an app component which is updated as the URL changes, all the HEML inside app component is loaded dynamically based on URL.

component folder contains home and form component's html, form is dynamically configured to eork as add product or edit product form.

app.js file holds al the logic for functions like:
rendering pages dynamically,
Adding ptoduct to the local storage(Create),
Displayig products on home page (Read),
Updating product in local storage (Update),
Deleting products from the local storage (Delet)

style.css has CSS for styling and mobile frendly behaviour.
