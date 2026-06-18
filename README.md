# Pastimes Clothing Store

Pastimes is a web-based platform for buying and selling second-hand fashion items. It integrates customer, seller, and admin functionality into a professional, user-friendly system.

## Main Features

### User Features
- **Register & Login**: Secure account creation and login for customers and sellers.
- **Browse Products**: Explore curated collections of clothing, shoes, accessories, and more.
- **Shopping Cart**: Add, edit, and remove items before checkout.
- **Checkout**: Streamlined purchase flow with order confirmation.
- **View Orders**: Track past purchases and monitor order status.

### Seller Features
- **Seller Registration & Login**: Dedicated portal for sellers.
- **Submit Clothing Requests**: Upload items for admin approval.
- **Seller Dashboard**: Manage listed products and track sales.
- **Inbox Messaging**: Communicate directly with admins and buyers.

###  Admin Features
- **Admin Login**: Secure access for administrators.
- **Manage Orders**: View and update customer orders.
- **Manage Clothing**: Approve or reject seller submissions.
- **Manage Requests**: Handle clothing requests from sellers.
- **Admin Communication**: Send messages to sellers and customers.

---

## UI & Navigation
- **Role-Specific Navigation Bars**: Tailored menus for customers, sellers, and admins.
- **Featured Collections Slider**: Interactive carousel showcasing categories (jackets, dresses, shoes, accessories, etc.).
- **Homepage Slideshow**: Auto-play hero slideshow highlighting fashion styles.
- **Responsive Layout**: Optimized for desktop and mobile devices.
- **Graffiti-Style Headings**: Unique typography for section titles.

---

## Additional Features

###  Delivery Details
- Integrated delivery form during checkout.
- Customers provide address, phone number, city, and postal code.
- Ensures smooth order fulfillment and accurate communication.
- Stored securely in the database for admin and seller reference.

### Clothing Filters
- Dynamic category filter buttons (e.g., Jackets, Dresses, Shoes, Accessories).
- Search bar for quick product lookup.
- Sticky filter bar with hover effects for usability.
- Enhances navigation and improves shopping experience.

---

## Messaging System
- **Inbox**: Sellers receive messages from admins.
- **Message Status**: Unread vs. read messages highlighted.
- **Timestamps**: Messages sorted by sent date.

---

## Technical Stack
- **Frontend**: HTML, CSS, JavaScript (sliders, animations).
- **Backend**: PHP (session management, form handling).
- **Database**: MySQL (user accounts, products, orders, messages).
- **Security**: Password hashing (recommend `password_hash()` for stronger security).

---

## Project Structure
- `index.php` → Homepage with slideshow and featured collections.
- `products.php` → Product listing page with filters.
- `viewCart.php` → Shopping cart.
- `deliveryDetails.php` → Delivery form for checkout.
- `sellerLogin.php` / `sellerRegister.php` → Seller portal.
- `adminLogin.php` → Admin portal.
- `manageOrders.php`, `manageClothing.php`, `manageRequests.php` → Admin management pages.
- `inbox.php` → Seller inbox.
- `css/style.css` → Stylesheet for UI design.
- `config/DBConn.php` → Database connection file

##  Notes
- Customers must create an account to shop or sell.
- Admin approval is required before seller items go live.
- Database export/import can be managed via phpMyAdmin.
  
##  Contact
- Support: **ST10440580@rcconnect.edu.za and ST104405772**
- Rosebank International South Africa
