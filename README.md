# E-Commerce Web Application (MERN)

## Project Overview

This is a **Full-Stack E-Commerce Web Application** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). The project implements core e-commerce functionalities for both **Users** and **Admin**, with authentication and role-based access control.

The application is developed as per the given assignment requirements and focuses on clean API design, authentication using JWT, and basic frontend integration.

---

## Tech Stack

### Frontend

* React.js (Vite)
* JavaScript (ES6)
* Fetch API
* Basic CSS

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JSON Web Tokens (JWT)
* bcryptjs

### Tools

* Postman (API testing)
* MongoDB Compass
* VS Code

---

## Features Implemented

### User Features ✅

1. **View list of products**
2. **View product details**
3. **User registration & login (JWT based)**
4. **Place an order**

### Admin Features ✅

1. **Admin login (role-based)**
2. **Add new products (protected route)**
3. **View all orders**

---

## Authentication & Authorization

* JWT-based authentication
* Tokens are generated on login
* Protected routes using middleware
* Admin-only routes enforced using role checks

---

## API Endpoints

### Auth

* `POST /api/auth/register` – Register user/admin
* `POST /api/auth/login` – Login and receive JWT

### Products

* `GET /api/products` – Get all products (public)
* `POST /api/products` – Add product (admin only)

### Orders

* `POST /api/orders` – Place order
* `GET /api/orders` – View all orders (admin)

---

## Project Structure

```
E-Commerce Web
│
├── Backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── server.js
│   └── .env
│
├── frontend
│   ├── src
│   │   ├── pages
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
```

---

## How to Run the Project

### Backend

```bash
cd Backend
npm install
npx nodemon server.js
```

Server runs on: `http://localhost:8080`

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on: `http://localhost:5173`

---

## Testing

* All APIs tested using **Postman**
* Auth, Products, and Orders APIs verified (GET & POST)

---

## Current Status

* Backend APIs complete and tested
* Authentication working
* Admin product creation working
* Orders creation and retrieval working
* Frontend login page setup started

---

## Future Enhancements (Optional)

* Cart UI
* Order history for users
* Admin dashboard UI
* Better UI/UX styling

---

## Submission Notes

* Project meets all required features as per assignment
* Focused on correctness, authentication, and API design
* Frontend kept minimal as per scope

---

## Author

**Swapnaja Paikrao**

B.Tech Computer Science

---

✅ *This project is ready for submission.*

