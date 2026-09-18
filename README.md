# 🛒 E-Commerce Website

A web-based E-Commerce Website developed to provide a simple, secure, and user-friendly online shopping experience. The application includes separate Customer, Seller, and Admin modules with product management, shopping cart, wishlist, order management, stock management, payment integration, and authentication.

## 📌 Features

### 👤 Customer
- Customer Signup & Login
- Customer Dashboard
- Browse and Search Products
- Category-wise Product Filtering
- Product Details
- Add to Wishlist ❤️
- Add to Cart 🛒
- Update Cart Quantity
- Checkout and Place Orders
- View and Track Orders
- Customer Profile
- Logout

### 👨‍💼 Seller
- Seller Signup & Login
- Seller Dashboard
- Add Products
- Edit and Delete Products
- Manage Product Categories
- Manage Price and Quantity / Stock
- View Customer Orders
- View Payment Status
- Logout

### 🛡️ Admin
- Admin Login
- Admin Dashboard
- Manage Customers
- Manage Sellers
- Manage Products
- View Orders
- View Payments

## 🏷️ Product Categories

Electronics | Fashion | Home | Beauty | Books | Other

## 🛠️ Technologies Used

**Frontend:** HTML5, CSS3, JavaScript

**Backend & Database:** Supabase, PostgreSQL, Supabase Authentication

**Payment:** Razorpay Test Mode

## 🗄️ Database

The project uses a single Supabase project with a PostgreSQL database containing multiple tables:

`profiles` | `products` | `wishlist` | `cart_items` | `addresses` | `orders` | `order_items` | `payments`

## 🔐 Authentication

Supabase Authentication is used for customer and seller registration, login, and session management. User roles are managed through the `profiles` table.

## 🔄 Application Flow

**Customer:** Signup → Login → Dashboard → Browse Products → Search / Category Filter → Wishlist / Cart → Checkout → Payment → Order

**Seller:** Signup → Login → Dashboard → Add / Manage Products → Update Stock → View Orders → Payment Status

**Admin:** Login → Dashboard → Manage Customers → Manage Sellers → Manage Products → View Orders → View Payments

## 📁 Project Structure

```text
E-Commerce-Website/
│
├── index.html
├── style.css
│
├── customer-signup.html
├── customer-login.html
├── customer-dashboard.html
├── customer-profile.html
├── customer-orders.html
├── products.html
├── cart.html
├── wishlist.html
├── orders.html
│
├── seller-signup.html
├── seller-login.html
├── seller-dashboard.html
├── add-product.html
├── manage-products.html
├── payment.html
│
├── admin-login.html
├── admin-dashboard.html
├── admin-customers.html
├── admin-sellers.html
├── admin-products.html
├── admin-orders.html
├── admin-payments.html
│
└── README.md