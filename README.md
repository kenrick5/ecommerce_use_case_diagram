UML Assignment

UML use Case Diagram for a Software Application

1. Description of the system:

The e-commerce system is a digital platform designed to facilitate online transactions between customers and administrators. It allows customers to browse products, add items to their cart, manage accounts, and complete purchases with integrated payment and order tracking features. Administrators manage inventory, process orders, and oversee the platform's operations through a dedicated backend. The system provides seamless integration with payment gateways and ensures secure data handling to enhance user experiences and business efficiency.

2. Actors and responsibilities

	. Customer responsibilities:
Customers are the primary users of the e-commerce system. Their responsibilities typically involve:

Browsing: Customers explore the product catalog, searching or filtering items based on preferences.

Purchasing: They add products to the cart, proceed to checkout, and make payments through the integrated payment gateway.

Account Management: Customers update personal details, view order history, and save items for future purchases.

Order Tracking: After placing an order, they interact with the system to track its delivery status.

	. Administrator responsibilities:
Administrators manage and maintain the system to ensure seamless operations. Their interactions include product Management: Adding, updating, or removing products in the catalog to keep inventory current.


3.
. Browse Products
Purpose: This use case allows customers to explore the product catalog.

Process:
Customers search for items by categories, filters (e.g., price range, brand), or keywords.
They can view product details such as descriptions, prices, images, and reviews.
The system retrieves and displays relevant results from the inventory database.

. Add to Cart
Purpose: Enables customers to select items for potential purchase.
Process: After browsing, the customer adds desired items to the shopping cart.
The system updates the cart to reflect the selected items, their quantity, and subtotal.
Customers can view, modify, or remove items in the cart.

. Manage Inventory
Purpose: Allows administrators to maintain the product database to ensure accurate stock levels and product availability.
Process: Admins can add new products, update details (e.g., price, description), or remove unavailable items.
The system validates changes and updates the inventory.
Automatic alerts may notify admins of low stock or out-of-stock items.

. Log In
Purpose: Authenticates users (customers or admins) to access specific features of the system.
Process: Users enter credentials (e.g., username and password).
The system verifies the credentials against stored data.
If authenticated, the system grants access to the user's account or admin dashboard.

. Complete Checkout
Purpose: Finalizes the purchase process by allowing customers to pay and confirm orders.
Process: Customers review items in the cart and provide shipping information.
They select a payment method (e.g., credit card, PayPal) and confirm the order.
The system processes the payment through a gateway and generates an order confirmation.
