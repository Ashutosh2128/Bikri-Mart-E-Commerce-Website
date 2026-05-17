# Bikri Mart – React E-Commerce Application

Bikri Mart is a **modern React-based e-commerce web application** that demonstrates real-world shopping cart functionality, global state management, product filtering, authentication flow, and a polished user interface.

The project is built with a focus on **clean architecture, reusable components, and practical business logic**, making it suitable for learning, portfolio showcase, and real-world frontend practice.

---
## Live Demo

**Website:** https://bikri-mart.netlify.app/

**GitHub Repository:** https://github.com/Ashutosh2128/Bikri-Mart-E-Commerce-Website

## Screenshots

### Home Page

<img width="1919" height="913" alt="image" src="https://github.com/user-attachments/assets/a10bb3e0-280c-4088-8985-9c568c49c032" />

### Sign In Page

<img width="1919" height="922" alt="image" src="https://github.com/user-attachments/assets/8ca2839b-51a4-4fca-8424-3aaa4736c275" />

### Explore Product Section

<img width="1911" height="913" alt="image" src="https://github.com/user-attachments/assets/0775cd7e-fcc3-4d57-9f7d-3dc26eeacc4e" />

### Filtering Product Based on Category or Price

<img width="1911" height="896" alt="image" src="https://github.com/user-attachments/assets/b2667e6f-673e-4804-8052-3087001d89c5" />

### Add To Cart Page

<img width="1910" height="908" alt="image" src="https://github.com/user-attachments/assets/847574cc-b010-4901-be2f-909da7187d9f" />


### View Product Details Page

<img width="1910" height="908" alt="image" src="https://github.com/user-attachments/assets/4a31ac75-bff6-4177-9bed-91844f8d16a8" />

### Why Choose Bikri Mart Section

<img width="1906" height="904" alt="image" src="https://github.com/user-attachments/assets/47b2db4e-9776-4c27-aa51-3c9e3b4fb7fb" />


### Contact Us Section

<img width="1913" height="891" alt="image" src="https://github.com/user-attachments/assets/300aade1-f790-42bb-a17f-bbcaeb68dc65" />


### Footer Section 

<img width="1904" height="910" alt="image" src="https://github.com/user-attachments/assets/6fdb5e38-8237-4e0b-93e9-8142778b13c6" />

## Features

### Product Management
- Product listing with **image, name, price, category, and stock**
- Product details page with **description and quantity selector**
- **Stock-aware purchasing** to prevent over-ordering

### Shopping Cart
- Add products to cart
- Increase and decrease product quantity
- Remove items from cart
- **Automatic total price calculation**
- **Per-item subtotal calculation**
- Cart sidebar with smooth animations

### Authentication
- User **Sign Up and Sign In**
- Session persistence using **LocalStorage**
- Per-user cart data handling
- Logout functionality

### Filtering and Navigation
- **Category-based filtering**
- **Price range filtering**
- Responsive product grid
- Smooth routing with **React Router DOM**

### Persistence and Checkout
- Cart data stored in **LocalStorage**
- Checkout functionality with stock update
- Order success confirmation page
- **Toast notifications** for user feedback

---

## Tech Stack

- **Frontend:** ReactJS (Vite)
- **State Management:** React Context API
- **Routing:** React Router DOM
- **Styling:** Tailwind CSS
- **Icons:** React Icons, Font Awesome
- **Notifications:** React Toastify
- **Storage:** Browser LocalStorage

---
## 📁 Project Structure

```bash
src/
│
├── components/
│   ├── AboutBikriMart.jsx
│   ├── ContactSection.jsx
│   ├── EndFooter.jsx
│   ├── Hero.jsx
│   ├── ScrollToTop.jsx
│   ├── Header.jsx
│   ├── Footer.jsx
│   ├── Sidebar.jsx
│   ├── Product.jsx
│   ├── CartItem.jsx
│   ├── CategoryFilter.jsx
│   └── PriceFilter.jsx
│
├── contexts/
│   ├── AuthContext.jsx
│   ├── CartContext.jsx
│   ├── ProductContext.jsx
│   └── SidebarContext.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── ProductDetails.jsx
│   ├── Signin.jsx
│   ├── Signup.jsx
│   └── OrderSuccess.jsx
│
├── App.jsx
├── main.jsx
└── index.css
```
##  Getting Started

###  Clone the Repository
```bash
git clone https://github.com/Ashutosh2128/Bikri-Mart-E-Commerce-Website.git
cd Bikri-Mart-E-Commerce-Website
```

###  Install Dependencies
```bash
npm install
```
###  Run in Development Mode
```bash
npm run dev
```
###  Build for Production 
```bash
npm run build
```
### Preview Production Build
```bash
npm run preview
```
##  Application Flow

- User visits the **Home Page**
- Browses products using **Category** and **Price Filters**
- Opens the **Product Details** page
- Adds items to the **Cart**
- Updates quantity or removes products
- **Signs up** or **Signs in**
- Proceeds to **Checkout**
- Views the **Order Success** confirmation page

---

##  UI & UX Highlights

-  Dark-themed modern interface  
-  Smooth transitions and hover effects  
-  Responsive layout for desktop and mobile  
-  Intuitive cart and checkout experience  
 

---

##  Author

**Ashutosh Prusty**  
Aspiring Developer & React Enthusiast  

 Email: `ashutoshprusty2128@gmail.com`  
🔗 LinkedIn: [Ashutosh Prusty](https://www.linkedin.com/in/ashutosh-prusty-)
