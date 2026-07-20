# 🎉Event Booking Platform

A full-stack Event Booking Platform built with the **MERN Stack** that allows users to discover events, book tickets securely, and manage their bookings. The platform also provides an admin dashboard for managing events and users.

---

## 📌 Features

### 👤 User
- User Registration & Login (JWT Authentication)
- Secure OTP Email Verification
- Browse Available Events
- View Event Details
- Book Event Tickets
- View Booking History
- User Dashboard
- Responsive UI

### 👨‍💼 Admin
- Admin Login
- Create New Events
- Update Existing Events
- Delete Events
- Manage Bookings
- Manage Users

### 🔒 Security
- JWT Authentication
- Protected Routes
- Password Encryption
- Environment Variable Support
- Email OTP Verification

---

# 🛠 Tech Stack

## Frontend
- React.js
- Vite
- Tailwind CSS
- React Router
- Axios

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Nodemailer

---

# 📂 Project Structure

```
Event-Booking
│
├── Backend
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── utils
│   ├── server.js
│   └── package.json
│
├── Frontend
│   ├── src
│   ├── public
│   ├── package.json
│   └── vite.config.js
│
├── .gitignore
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Priyanshu87571/Event-Booking.git
```

Move into the project folder

```bash
cd Event-Booking
```

---

## 2️⃣ Install Backend Dependencies

```bash
cd Backend
npm install
```

---

## 3️⃣ Install Frontend Dependencies

```bash
cd ../Frontend
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the **Backend** folder.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
PORT=5000
```

---

# ▶️ Run Backend

```bash
cd Backend
npm start
```

or

```bash
npm run dev
```

---

# ▶️ Run Frontend

```bash
cd Frontend
npm run dev
```

---

# 📸 Screenshots


### Home Page

<img width="1878" height="848" alt="image" src="https://github.com/user-attachments/assets/54dababc-b2d1-4bd8-ace1-5c4973503e88" />


### Login

<img width="1805" height="852" alt="image" src="https://github.com/user-attachments/assets/9fb0eb83-3caf-4c2b-a32b-a887bb10b5db" />

<img width="1726" height="832" alt="image" src="https://github.com/user-attachments/assets/6cb6d3ca-13de-4883-9c6a-53d37bc5a9d4" />


### Dashboard

<img width="1878" height="848" alt="image" src="https://github.com/user-attachments/assets/54dababc-b2d1-4bd8-ace1-5c4973503e88" />

<img width="1808" height="827" alt="image" src="https://github.com/user-attachments/assets/ea092678-9fd5-4a70-a536-ac116d62e23f" />

<img width="1841" height="285" alt="image" src="https://github.com/user-attachments/assets/bd2095ba-8034-4aa5-b610-603e0380cdd5" />

---

# 🚀 Future Enhancements

- Online Payment Integration
- Event Categories
- Search & Filter
- Seat Selection
- QR Code Ticket
- Email Notifications
- Event Reviews
- Live Chat Support
- Dark Mode

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 👨‍💻 Author

**Priyanshu Raj**

- GitHub: https://github.com/Priyanshu87571
- LinkedIn: https://www.linkedin.com/in/priyanshu-raj-162763306/

---

# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub!

---

