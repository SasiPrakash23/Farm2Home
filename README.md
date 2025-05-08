
# 🌾 Farm2Home

**Farm2Home** is a full-stack e-commerce platform developed using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). It connects farmers directly with consumers, eliminating intermediaries in the sale of vegetables, fruits, and other farm products.

## 📋 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Database Setup](#database-setup)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

### For Customers:

- Browse a wide range of farm products
- Add items to cart, modify quantities, or remove items
- Secure checkout process
- Multiple payment options
- Provide feedback on purchases
- View order history and status

### For Farmers:

- Secure login system
- Personalized dashboard to manage products and orders
- Add, edit, or remove product listings
- Update delivery status for orders
- View earnings and sales statistics

## 🛠️ Technologies Used

- **Frontend**:
  - React.js
  - HTML5
  - CSS3
  - Bootstrap 4

- **Backend**:
  - Node.js
  - Express.js

- **Database**:
  - MongoDB
  - Mongoose

- **Version Control**:
  - Git

## 🚀 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SasiPrakash23/Farm2Home.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Farm2Home
   ```

3. **Install backend dependencies**:
   ```bash
   cd server
   npm install
   ```

4. **Install frontend dependencies**:
   ```bash
   cd ../client
   npm install
   ```

## 📖 Usage

1. **Start the backend server**:
   ```bash
   cd server
   npm start
   ```

2. **Start the frontend development server**:
   ```bash
   cd ../client
   npm start
   ```

3. **Access the application**:
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5000/api`

## 🗄️ Database Setup

1. **Ensure MongoDB is installed and running** on your local machine or use a cloud-based MongoDB service.

2. **Configure environment variables**:
   - Create a `.env` file in the `server` directory with the following content:
     ```env
     MONGO_URI=your_mongodb_connection_string
     PORT=5000
     ```

3. **Seed the database (optional)**:
   - If you have seed data, run the seeding script:
     ```bash
     cd server
     npm run seed
     ```

## 🤝 Contributing

Contributions are welcome! To contribute:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Commit your changes**:
   ```bash
   git commit -m "Add Your Feature"
   ```
4. **Push to your forked repository**:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Create a Pull Request**.

Please ensure your code adheres to the project's coding standards and includes appropriate documentation.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
