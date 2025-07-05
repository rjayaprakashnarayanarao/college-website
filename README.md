
# 🏫 Certificate Management System – Necn-Hub

**Necn-Hub** is a digital certificate management system developed for **NECN College**. It replaces traditional paper-based processes with an efficient, secure, and user-friendly web platform. The system allows admins to generate and issue certificates, and students to view and download them, all within a streamlined role-based dashboard environment.

---

## ✨ Features

- 🔐 **Login System**: Secure login with role-based access (Admin & User)
- 🧑‍💼 **Admin Panel**: Issue certificates, view submissions, and manage student data
- 🧾 **Automated Certificate Generation**: Generate PDF certificates with one click
- 📤 **Student Upload**: Upload necessary files for verification
- 📨 **Email Notifications**: Automatic emails upon certificate issue
- 📄 **PDF Export**: Certificates can be downloaded as secure PDFs
- 🧭 **Role-Based Dashboards**: Tailored interfaces for admin and student experiences

---

## 🗂 Project Structure

```
college-website-main/
├── public/                  # Static assets
│   └── ...
├── views/                   # EJS templates for frontend
│   ├── admin/
│   ├── student/
│   └── ...
├── routes/                  # Express routes
├── controllers/             # Request handlers
├── models/                  # Database models
├── utils/                   # Helper functions
├── .env                     # Environment variables
├── app.js                   # Main server entry point
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js
- MongoDB (local or Atlas)

### Clone and Run Locally

```bash
git clone https://github.com/rjayaprakashnarayanarao/certificate-management-system.git
cd certificate-management-system
npm install
npm start
```

### Environment Variables (`.env`)

```env
PORT=3000
DB_URL=              # Your MongoDB connection string
EMAIL_USER=          # Email used for sending notifications
EMAIL_PASS=          # App password or email password
JWT_SECRET=your_jwt_secret
```

---

## ⚙️ How It Works

1. **Admin logs in** to the dashboard and uploads certificate data or student details.
2. The system automatically generates a certificate in **PDF format**.
3. A confirmation **email is sent** to the student with access instructions.
4. **Students log in**, verify their identity, and view/download their certificates.
5. The platform ensures secure access using **role-based views and routing**.

---

## 📘 Learn More

This project is built with:

- **Backend**: Node.js + Express  
- **Frontend**: EJS, CSS  
- **Database**: MongoDB  
- **PDF Generation**: PDFKit  
- **Email**: Nodemailer  
- **Templating**: EJS  

---

## 📄 License

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it.

---

## 📬 Contact

**Author**: Jaya Prakash Narayana Rao  
- GitHub: [rjayaprakashnarayanarao](https://github.com/rjayaprakashnarayanarao)  
- Email: [rjayaprakashnarayanarao@gmail.com](mailto:rjayaprakashnarayanarao@gmail.com)  
- Phone: +91 93908 66948  

---

> Built with care to modernize certificate management at NECN 🎓
