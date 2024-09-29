# ZingMeal 🍽️

## 🎮 Demo
[Live Demo](https://zingmeal.netlify.app/)

---

## 📝 Summary

**ZingMeal** is a full-featured real-time food ordering platform that allows users to sign in as either a customer or a restaurant. The platform provides a rich set of features, including browsing restaurants and food items, cart management, secure payments, order tracking, and restaurant management. Users can also explore the platform via a **trial mode** without needing to create an account.

Key Features:
- **Search functionality** to quickly find restaurants or food items.
- **Responsive design** for a smooth experience on mobile and desktop.
- **Secure payment integration** using Razorpay.
- **Order management**, including the ability to cancel orders within 30 minutes.
- **Restaurant management** for restaurant owners to modify menus and track orders.

---

## 💻 Screenshots

### Landing Page
![Landing Page](https://github.com/user-attachments/assets/136e02b2-7e17-4367-b41f-ff00a918077d)

### Search and Browse
![Search and Browse](https://github.com/user-attachments/assets/73fdc2d7-b049-4973-aebf-4cc490df5fd5)
![Food Items](https://github.com/user-attachments/assets/7da8cc8c-18a9-4ada-b0ab-a05ea979a8a5)

### Restaurant Page
![Restaurant Page](https://github.com/user-attachments/assets/f6343462-9c4b-4a11-b8f9-5480d3c3d4bb)

### Cart Page
![Cart Page](https://github.com/user-attachments/assets/f93867ab-0808-4e6c-bbac-96823129a50f)

### Order Management
![Order Management](https://github.com/user-attachments/assets/3394a518-1761-461d-8c50-3cb8a4f05e6f)

---

## 🎯 Key Features

- **User-Friendly Food Ordering**: Browse and select from a variety of food items from different restaurants.
- **Cart Management**: Add, update, or remove items from the cart, with a smooth checkout experience.
- **Secure Payments**: Integrated with **Razorpay** for online payments, alongside a Cash on Delivery option.
- **Order Management**: Users can track their orders and cancel them within 30 minutes if necessary.
- **Restaurant Management**: Restaurant owners can add/modify menu items, and manage restaurant details and orders.
- **Real-Time Updates**: Handle concurrent orders with real-time data synchronization.
- **Trial Mode**: Explore the full functionality of the platform without the need for sign-up/login.
- **Responsive Design**: Optimized for both mobile and desktop.

---

## 🛠️ Technologies Used

- **Frontend**: React.js, Redux, Context API, Tailwind CSS
- **Backend**: Node.js, Express.js, TypeORM
- **Database**: PostgreSQL
- **Real-time Communication**: WebSocket.io
- **Payment Gateway**: Razorpay
- **Version Control**: Git

---

## 🚀 Getting Started

### Backend Setup

1. Clone the backend repository:
   ```bash
   git clone https://github.com/Anugrahas2001/ZingMeal-Node
2. Navigate into the backend folder:
cd ZingMeal-Node
3. Install the necessary dependencies:
npm install
4. Configure your environment variables: Create a .env file in the root directory with the following:
   PORT=5000
DATABASE_URL=your_postgresql_database_url
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
5. Start the backend server:
   npm run dev
### Frontend Setup

1. Clone the backend repository:
   ```bash
   git clone https:git clone https://github.com/Anugrahas2001/ZingMeal-App
2. Navigate into the backend folder:
cd ZingMeal-App
3. Install the necessary dependencies:
npm install
4. Start the frontend server:
 npm run dev

---
### ⚙️ Features Overview
1. User Authentication:
   - Sign up or sign in as either a customer or restaurant owner.
   - Explore via trial mode without the need to register.
2. Restaurant and Food Item Management:
   - Browse and search for restaurants and food items.
- Filter food items as vegetarian or non-vegetarian.
3. Cart & Orders:
  - Add, remove, or update items in the cart.
  - Choose between Cash on Delivery and Online Payment using Razorpay.
  - Track and manage placed orders.
4. Order Cancellation:
  - Cancel orders within 30 minutes of placing them.
5. Restaurant Owner Panel:
  - Restaurant owners can add/edit food items and manage their orders.
6. Search Functionality:
 - Advanced search options for quickly finding the food items or restaurants you want.
---
### 🛠️ Future Enhancements
- **Ratings and Reviews**: Allow users to rate and review restaurants.
- **Notification System**: Push notifications for order updates.
- **Enhanced Admin Panel**: More tools for restaurant owners to analyze performance.
- **Referral Program**: Rewards for inviting new users.

---
## Enjoy using ZingMeal!🎉
