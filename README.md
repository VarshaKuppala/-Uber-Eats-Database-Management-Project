# Uber-Eats-Database-Management-Project


PROJECT DESCRIPTION:
Uber Eats is an online food ordering and delivery platform. The guest could choose to order meals that are delivered by couriers using cars, scooters, bikes, or on foot according to their preferences and requirements listed by the hosts of the uber eats system. The guests and the hosts could interact via the uber eats in-app messaging system. The overall process is given a review or a rating for an improved experience. Due to its versatile availability of properties, Uber Eats is a very popular platform to book a stay or an experience.
Entities:

1.	User
2.	Delivery Address
3.	All Categories
4.	Order Item
5.	Order
6.	Payment
7.	Delivery
8.	Delivery Driver
9.	Reviews
10.	Promo Code
 
Data Requirements and Assumptions:
User: The system should store information about users, including their name, email address, phone number, password, and delivery address.

●	One User can have one Delivery Address.

●	One User can place many Orders.

●	One User can write many Reviews.

All Categories: The system should store information about restaurants, including their name, location, cuisine type, menu items, and prices.

●	All Categories can have many Menu Items.

●	All Categories can receive many Orders.

Order: The system should store information about orders, including the date and time of the order, the restaurant and the user who placed the order, the items ordered, and the totalcost of the order.

●	One Order can be placed by one User.

●	One Order can be associated with one catagories.

●	One Order can contain many Items.

●	One Order can have one Payment.

●	One Order can have one Delivery.

Delivery: The system should store information about deliveries, including the date and time of delivery, the delivery address, and the delivery status.

●	One Delivery can be associated with one Order.

●	One Delivery can be made by one Delivery Partner.

Payment: The system should store information about payments, including the payment method, the amount paid, payment Time and the payment status.

●	One Payment can be associated with one Order.

Review: The system should allow users to rate and review restaurants should store this information in the database.

●	One Review can be written by one User.

●	One Review can be associated with one Restaurant
 
Delivery Driver: The system should store information about delivery partners, including their name, Vehicle Number, contact details, and availability.

●	One Delivery Partner can make many Deliveries.

Promo Code: The system should store information about Promo Code including promo codes, discounts, Name and expiration dates.

●	One Promotion can be used by many Users.

●	One Promotion can be associated with many Orders or Users.

Delivery Address: This entity represents the delivery address associated with a user. Each delivery address has a unique ID and can be associated with only one user.

Order Item: This entity represents an item on a restaurant's menu. Each menu item has a unique ID and can be part of many orders.

Assumptions:

User: This entity represents the user who places the order. Each user has a unique ID and can place many orders and write many reviews. Each user can have one delivery address.

Delivery Address: This entity represents the delivery address associated with a user. Each delivery address has a unique ID and can be associated with only one user.

Order Item: This entity represents an item on the menu of a restaurant. Each menu item has a unique ID and can be part of many orders.

Order: This entity represents an order placed by a user. Each order has a unique ID and is associated with one user and one restaurant. Each order can have many items.


ER Diagram:

![image](https://github.com/06Bhavyathadiboina/Uber_Eats-DatabaseManagementProject/assets/129217214/0fc4e1e9-d0f5-4bff-a3be-0a699ee86d11)


Relational Schema:

![image](https://github.com/06Bhavyathadiboina/Uber_Eats-DatabaseManagementProject/assets/129217214/e1f9c769-4807-4153-a03b-ee1eee64cd87)

Final relational schema after normalization:

![image](https://github.com/06Bhavyathadiboina/Uber_Eats-DatabaseManagementProject/assets/129217214/19c1056d-c62c-45df-bd3e-6cb4feae14a6)

