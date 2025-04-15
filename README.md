# 🛒 MERN E-commerce Website

A fully functional **E-commerce platform** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js), supporting features such as user authentication, product listings, shopping cart, order management, and admin capabilities.

---

## 🚀 Features

- 🔐 **User Authentication**: Register, login, and role-based access (admin & user).
- 🛍️ **Product Management**: Add, update, and delete products with categories.
- 📦 **Order System**: Place orders, view order history, and update status.
- 🗃️ **Category Management**: Admins can create and manage categories.
- 📤 **Image Upload**: Upload product images using the Upload API.
- ⚙️ **RESTful APIs**: Well-structured and scalable API design.
- 🔄 **Frontend + Backend**: Built as a full-stack application with clear separation.

---

## 🧱 Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **State Management**:Redux 
- **Styling**: Tailwind CSS / CSS Modules 
- 
---

## 🛠️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/ritinpaul/MERN-Ecommerce-Website.git
cd MERN-Ecommerce-Website

```

### 2. Install dependencies for backend
```bash
cd backend
npm install
```

### 3. Setup Environment Variables

Create a `.env` file in the `backend/` directory:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

### 4. Start the backend server

```bash
npm run dev
```

The backend server will start at `http://localhost:5000`.

### 5. (Optional) Start the frontend

If you have a `frontend/` folder:

```bash
cd ../frontend
npm install
npm start
```

---


## 🧑‍💻 Author

**Ritinpaul Singh**  
*Full-stack MERN Developer*  
[GitHub](https://github.com/ritinpaul)

---

## 📄 License

This project is licensed under the MIT License.
