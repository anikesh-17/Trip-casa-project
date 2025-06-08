# 🏡 TripCasa

**TripCasa** is a fullstack hotel and house booking platform inspired by Airbnb. Built using the **MVC architecture**, this application allows users to explore listings, book accommodations, manage their accounts, and more.

🌐 **Live Site:** [https://tripcasa.onrender.com/listings](https://tripcasa.onrender.com/listings)


## ✨ Features

- 🔐 User authentication with sessions and Passport.js  
- 🏘️ Create, read, update, and delete property listings  
- 📷 Image upload support with Cloudinary and Multer  
- ✅ Form validation with Joi  
- 💬 Flash messages for user feedback  
- 🌍 MongoDB for data storage (via Mongoose)  
- 📦 Environment variable support with dotenv  
- 💻 Server-side templating with EJS and EJS-Mate  
- 🔄 Method override for supporting PUT and DELETE in forms

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, EJS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB with Mongoose  
- **Authentication:** Passport.js (Local Strategy)  
- **File Uploads:** Multer + Cloudinary  
- **Validation:** Joi

---

## 📁 Project Structure

TripCasa/
│
├── models/ # Mongoose models
├── routes/ # Route handlers
├── views/ # EJS templates
├── public/ # Static files (CSS, JS)
├── controllers/ # Controller functions (MVC)
├── middleware/ # Custom middleware functions
├── utils/ # Utility functions (e.g., for cloudinary config)
├── app.js # Entry point
└── .env # Environment variables (not committed)

👥 Contributors
Anikesh Sharma

