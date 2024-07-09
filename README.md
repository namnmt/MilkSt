# MilkSt
Data build Milkst
### Topic and Content:
The topic of this document is the Milk E-commerce project, which aims to develop an online platform for customers to purchase milk and related products, sellers to manage their inventory and sales, and administrators to oversee the entire platform.

### Content:
1. **Purpose**: To define the functional and non-functional requirements for the Milk E-commerce website. This document will serve as a guide for developers, testers, and stakeholders throughout the development process.
2. **Scope**: The development and testing of the features described in this SRS, including:
    - Functional testing for all user roles (Customer, Seller, Admin).
    - Compatibility with modern web browsers.
    - Integration with external payment gateways and shipping carriers.

### Major Features (Epics):
1. **Browse Products**: Customers can search and filter products by category, brand, price, etc.
2. **Add to Cart**: Customers can add products to their shopping cart.
3. **Checkout**: Customers complete their purchase by providing shipping and payment information.
4. **View Order History**: Customers can view their past orders and track their current orders.
5. **Write Reviews**: Customers can write reviews for products they have purchased.
6. **Manage Account**: Customers can update their personal information, change their password, and view their order history.
7. **Manage Inventory**: Sellers can add, update, and delete products from their inventory.
8. **Process Orders**: Sellers can view and process new orders, update order status, and generate shipping labels.
9. **Manage Reviews**: Sellers can view and respond to customer reviews.
10. **View Sales Reports**: Sellers can view their sales data, including revenue, units sold, and top-selling products.
11. **Manage Users**: Admins can add, update, and delete user accounts (customers and sellers).
12. **Manage Products**: Admins can add, update, and delete products from the entire site.
13. **Manage Categories**: Admins can add, update, and delete product categories.
14. **View Site Analytics**: Admins can view site traffic data, conversion rates, and other key metrics.

### Applied Technologies:
1. **User Interface**:
   - Responsive web design for customers, sellers, and admins.
   - Mobile-friendly design for optimal viewing on different devices.
   - User-friendly navigation for easy browsing and product discovery.
   - Interactive elements like product carousels, image zoom, and customer views.
2. **Hardware Interfaces**:
   - The system will primarily be accessed through standard computer hardware (desktops, laptops) and mobile devices (smartphones, tablets).
3. **Software Interfaces**:
   - **Email Notifications**: Order confirmations, shipping updates, and delivery notifications for customers; new order notifications and customer inquiries for sellers; system alerts and reports for admins.
   - **SMS Notifications (Optional)**: Order updates and promotional messages for customers.
   - **Live Chat (Optional)**: Real-time chat support for customers and sellers.
4. **Security Requirements**:
   - User data should be encrypted and protected from unauthorized access.
   - Payment transactions should be secure and compliant with industry standards.

**Member report**
Member	User story
Phạm Việt Hàn	US03, US04
Nguyễn Mai Thành Nam	US05, US06
Nguyễn Minh Đức	US07, US08
Đặng Đường An	US01, US02

User story report
ID	User story name	Description	Issue type	Epic	Sprint
US01	As a customer, I want to login	The customer needs to enter phone number and otp to login	Story	Manage Account	Sprint1
US02	As a customer, I want to update my personal information, such as my name and email address, so that my account details are current.	Customers need to easily update their name, email, and other personal info to keep their account details accurate.	Story	Manage Account	Sprint1
US03	As a store manager, I want to edit product details, such as descriptions and prices, so that the information is accurate and up-to-date.	Store managers need to update product descriptions and prices to ensure accuracy for customers.	Story	Manage Products	Sprint1
US04	As a store manager, I want to upload images for products so that customers can see what they are purchasing.	Store manager upload product images for better customer visualization.	Story	Manage Products	Sprint1
US05	As a store manager, I want to categorize products correctly so that they are easy for customers to find.	Store manager improve product categorization for customer browsing ease.	Story	Manage Products	Sprint1
US06	As a customer, I want to enter my shipping information during checkout so that my order can be delivered to the correct address.	Customer enters shipping address during checkout and ensures order arrives at the right location.	Story	Checkout	Sprint1
US07	As a customer, I want to choose my preferred payment method during checkout so that I can pay in a way that is convenient for me.	Customer wants to pick their own payment option at checkout for a smooth and convenient buying experience.	Story	Checkout	Sprint1
US08	As a customer, I want to review my order details before finalizing the purchase so that I can ensure everything is correct.	Customer wants to see a summary of their shopping cart items (including any customizations) before checkout to confirm accuracy.	Story	Checkout	Sprint1

