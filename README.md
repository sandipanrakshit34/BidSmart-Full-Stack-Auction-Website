# 🏷️ BidSmart: Full-Stack Auction Website

A fully functional, responsive **auction web application** built with **React.js**, **Node.js (Express)**, and **MongoDB**. Designed for seamless bidding experiences, it allows users to post products, bid in real-time, and view live auction updates.

---

## 📌 Table of Contents

- [🧠 About the Project](#-about-the-project)
- [💡 Problem Statement](#-problem-statement)
- [✅ Features](#-features)
- [🛠️ Technologies Used](#-technologies-used)
- [🚀 Setup Instructions](#-setup-instructions)
- [📸 Screenshots](#-screenshots)
- [✨ Unique Points](#-unique-points)
- [📬 Contact](#-contact)

---

## 🧠 About the Project

**BidSphere** is a modern auction platform where:
- Sellers can post products for bidding.
- Users can bid in real-time.
- Live countdown timers show time left on each product.
- Winning bids are automatically processed after the timer ends.
- Everything is powered by real-time updates and secure backend logic.

---

## 💡 Problem Statement

Traditional auction processes lack digital flexibility and real-time interaction. This project addresses:
- Real-time auction and bidding system
- Product listing by users
- Automatic bid closing after timer ends
- Secure and scalable backend logic

---

## ✅ Features

### 🔐 User Authentication
<div align="center">
  <table>
    <tr>
      <td>
        <img src="Assets/display1.png" alt="Login Page 1" width="600" height="400"/>
      </td>
      <td>
        <img src="Assets/display2.png" alt="Login Page 2" width="600" height="400"/>
      </td>
    </tr>
  </table>
</div>

- Register/Login with hashed password (bcrypt)
- JWT-based session management
- Role-based routing (seller vs bidder)

### 🛒 Product Listing (Sellers)
<div align="center">
  <table>
    <tr>
      <td>
        <img src="Assets/display3.png" alt="" width="600" height="400"/>
      </td>
      <td>
        <img src="Assets/display6.png" alt="" width="600" height="400"/>
      </td>
    </tr>
  </table>
</div>

   - Post products with image, title, description, and starting price
   - Set auction duration using a live timer
   - Products get listed publicly in real-time

### ⏱️ Live Auction & Real-Time Bidding

<div align="center">
  <table>
    <tr>
      <td>
        <img src="Assets/display4.png" alt="" width="600" height="400"/>
      </td>
      <td>
        <img src="Assets/display5.png" alt="" width="600" height="400"/>
      </td>
    </tr>
  </table>
</div>

- View products available for bidding
- Place a bid higher than current bid
- Timer countdown shown on each card
- Highest bidder wins after countdown ends

### 🧾 Bid History
- View bid history for each product
- Admin/seller access to all bids
- Track bidder name, amount, and time

### 🧰 Admin Panel (Optional)
- Remove users/products
- Moderate inappropriate listings

---

## 🛠️ Technologies Used

### 🔹 Frontend:
- React.js
- Tailwind CSS / Bootstrap (based on your UI stack)
- Axios
- React Router

### 🔹 Backend:
- Node.js
- Express.js
- MongoDB with Mongoose

### 🔹 Database:
- MongoDB (no manual schema setup needed)
- Programmatically creates collections & documents

### 🔹 Authentication:
- JWT (JSON Web Tokens)
- bcrypt for password hashing

### 🔹 Real-Time:
- setInterval for countdown timers
- WebSocket / polling (optional if real-time updates enabled)

---

## 🚀 Setup Instructions

### 🔧 Backend Setup

1. Clone the repo and navigate to the backend folder:
   ```bash
   git clone https://github.com/yourusername/auction-site
   cd auction-site/backend
