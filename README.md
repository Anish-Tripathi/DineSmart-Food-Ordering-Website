# DineSmart - Food Ordering & Restaurant Management Web App

## Description
DineSmart is a full-stack restaurant management web application built using the MERN stack (MongoDB, Express, React, and Node.js). It allows users to browse menus, add dishes to the cart, place orders, track past orders, and manage their profile. The project also includes additional features like personalized dish recommendations, budget-based order filtering, and real-time booking of restaurant seats for specific time slots. DineSmart aims to simplify the food ordering process, provide tailored dining experiences, and enhance customer interaction.

---

## Features
- **Dynamic Menu System**: Browse restaurant menus categorized into sections (e.g., starters, main course, biryani, desserts).
- **Search and Filter**: Filter dishes based on categories like veg/non-veg, rice, dal, etc.
- **Cart Management**: Add/remove items, adjust quantities, and view total prices in real-time.
- **Order Tracking**: View all past orders with detailed billing information.
- **Login/Signup**: Secure authentication with bcrypt for password hashing; validation for new users.
- **User Recommendations**: Suggest dishes based on previous orders.
- **Dietary Preferences**: Filter dishes based on preferences like fasting, low-carb, etc.
- **Friend Referrals**: Get dish recommendations from friends' order history.
- **Budget Filtering**: Suggests dishes based on user budget.
- **Seat Booking**: Book seats at restaurants for specific time slots.
- **Nutrient Value Display**: View detailed nutrient information for each dish.
- **Restaurant Tips & Review**: Leave reviews for dishes/restaurants and tip delivery personnel.
- **Comparative Menu Feature**: Compare dishes across or within restaurants.
- **Nutritional & Historical Info**: Displays facts and nutritional info about dishes.
- **Responsive Design**: Fully responsive design for desktop and mobile platforms.

---

## Future Additions
- **Advanced Recommendation Algorithms**: For more personalized dining suggestions.
- **Live Order Status**: Real-time order tracking system.
- **Payment Gateway** Integrate via Stripe or Razorpay for secure payments.
  

---

## Tech Stack

### Frontend:
- React.js (JavaScript)
- HTML5, CSS3
- Axios for HTTP requests
- React Context API for state management

### Backend:
- Node.js with Express.js
- MongoDB with Mongoose for database interaction
- JWT for authentication and authorization
- Bcrypt for password hashing
- Nodemailer for email notifications

### Database:
- MongoDB (NoSQL)

### APIs:
- OpenRouteService API (for geolocation and seat booking)
---

## Installation Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/DineSmart.git

2. **Install dependencies for both backend and frontend**:
   cd DineSmart/backend
   npm install
   cd ../frontend
   npm install
3. **Set up environment variables**:
   Create a .env file in the backend directory with necessary API keys, database URIs, and JWT secrets.
4.**Start the development server:**
   npm run server
   npm start
5.**Visit http://localhost:3000 to access the app.**

This README file contains all the necessary sections, formatted in a clean and structured manner, with all the features, tech stack, and usage clearly outlined.
