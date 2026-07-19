# 🎉 Eventora - Event Booking Platform

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

> Add screenshots here after deployment.

### Home Page

```
assets/home.png
```

### Login

```
assets/login.png
```

### Dashboard

```
assets/dashboard.png
```

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
- LinkedIn: *(Add your LinkedIn profile here)*

---

# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub!

---

## 📜 License

This project is licensed under the MIT License.
