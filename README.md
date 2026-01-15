# 🛒 Forever – Full Stack E-Commerce Application

Forever is a **full-stack e-commerce web application** built with the **MERN stack**. Users can browse products, manage their cart, place orders using multiple payment options, and track order status. The project also includes a separate **Admin Dashboard** to manage products and orders.  

All three parts — **Frontend**, **Backend**, and **Admin Dashboard** — are deployed independently on **Vercel**.

---

## 🌐 Live Deployments

- **Frontend (User App):** [https://forever-frontend-six-ruby.vercel.app](https://forever-frontend-six-ruby.vercel.app)  
- **Admin Dashboard:** [https://forever-admin-rho-three.vercel.app](https://forever-admin-rho-three.vercel.app)

---

## 🔐 Demo Admin Credentials

> ⚠️ For demonstration purposes only

- **Email:** admin@forever.com  
- **Password:** admin@123  

**Admin panel features:**

- Admin authentication  
- Add new products  
- Delete existing products  
- View all user orders  
- Update order status (e.g., **Shipping → Delivered**)  

> ⚠️ Note: Product update/edit functionality is not implemented. To modify a product, it must be deleted and re-added.

---

## 🚀 Features

### 👤 User Features

- Login / Register with authentication  
- Browse products by category  
- Select product size and add to cart  
- Place orders using:  
  - Cash on Delivery (COD)  
  - Stripe  
  - Razorpay  
- Track order history  
- Notifications using **React-Toastify**

### 🛠️ Admin Features

- Admin login / authentication  
- Add new products  
- Delete products  
- View all orders  
- Update order status through predefined stages  

---

## 🧰 Tech Stack

**Frontend:** React.js, Tailwind CSS, React Router, Axios, React-Toastify  
**Backend:** Node.js, Express.js, MongoDB (Mongoose), JWT Authentication  
**Backend Dependencies:** bcrypt, cloudinary, cors, dotenv, jsonwebtoken, multer, stripe, razorpay, validator  
**Payments:** Stripe, Razorpay  
**Deployment:** Vercel (Frontend, Backend, Admin Panel)

---

## 📂 Project Structure

Forever-Full-Stack/

    ├── frontend/ → User-facing React application
    ├── admin/ → Admin dashboard (React)
    ├── backend/ → Node.js & Express API
    └── README.md


---

## ⚙️ Environment Variables

Sensitive data such as:

- Database connection string  
- JWT secret  
- Stripe & Razorpay keys  
- Admin credentials  

are configured securely in **Vercel Environment Settings** and are **not exposed** in the repository.

---

## 🚀 Deployment Details

- Each part (**Frontend**, **Backend**, **Admin**) is deployed independently on Vercel.  
- Backend APIs are connected to Frontend and Admin via **environment-based URLs**.  
- **React Router** support is handled using `vercel.json`.

---

## 📌 Future Improvements

- Add **product update/edit functionality** in Admin panel
