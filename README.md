# PostCreater

## Description

PostCreater ek simple aur powerful web application hai jo users ko posts create, view, aur manage karne ki facility deta hai. Yeh project beginners ke liye web development concepts samajhne ke liye perfect hai, saath hi professionals ke liye bhi ek scalable base provide karta hai.

## Tech Stack Used

- **Node.js** (Backend runtime)
- **Express.js** (Web framework)
- **MongoDB** (Database)
- **Mongoose** (MongoDB ODM)
- **EJS** (Templating engine)
- **HTML/CSS** (Frontend structure & styling)
- **bcrypt** (Password hashing)
- **jsonwebtoken** (Authentication)
- **cookie-parser** (Cookie management)

## Features

- User registration and login with secure password hashing
- JWT-based authentication and session management
- Create, view, edit and delete.
- Like/unlike posts functionality
- User profile page with all posts
- Middleware for route protection

## Installation Guide

Follow these steps to set up and run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/postCreater.git
   cd postCreater
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   - Agar aap MongoDB Atlas ya local MongoDB use kar rahe hain, toh `.env` file banayein aur apna connection string add karein:
     ```env
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     ```
   - (Aapke code me abhi hardcoded secret hai, production ke liye env variables use karna recommended hai)

4. **Start the application**
   ```bash
   npm start
   ```
   - By default, the app runs on [http://localhost:3000](http://localhost:3000)

5. **Open in browser**
   - Visit [http://localhost:3000](http://localhost:3000) to use the app

---

 Happy coding!
