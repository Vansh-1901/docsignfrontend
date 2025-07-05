# 🖋️ DOCSIGNAPP – Digital Document Signing Platform

**DOCSIGNAPP** is a full-stack web application built by **Vansh Gupta**, a B.Tech 2nd Year student, using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. The platform allows users to digitally sign PDF documents through a smooth and intuitive interface that supports both **typed** and **drawn** signatures.

---

## 🔗 Live Demo

> Coming Soon

---

## 🚀 Features

### 🔐 Authentication

- Secure user registration and login
- JWT-based session management

### 📄 PDF Upload

- Upload and preview any PDF file for signing

### ✍️ Signature Modes

- **Typed Signature**: Type your name, choose font style, and color
- **Drawn Signature**: Draw your signature using a digital canvas

### 🖱️ Drag-and-Drop Placement

- Drag and place your signature freely anywhere on the PDF

### 💾 Save Final Document

- Download the signed PDF with embedded signature
- Finalized using `pdf-lib` for precise embedding

### 📜 Audit & History (Optional Future Feature)

- Track signing activity for transparency and trust

---

## 🛠️ Tech Stack

| Frontend     | Backend    | Database      | Additional Tools             |
| ------------ | ---------- | ------------- | ---------------------------- |
| React.js     | Node.js    | MongoDB Atlas | JWT for Authentication       |
| Tailwind CSS | Express.js | Mongoose      | Multer for File Uploads      |
| React-PDF    |            |               | pdf-lib for PDF manipulation |

---

## 📁 Project Structure

doc_sign/
├── client/ # React Frontend
│ └── src/
│ ├── components/
│ ├── pages/
│ └── utils/
├── server/ # Node.js Backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── middleware/
└── README.md

---

## 🧑‍💻 Getting Started

### 🔧 Prerequisites

- Node.js & npm
- MongoDB Atlas

### 🛠 Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Vansh-1901/Docsignapp2
   cd doc_sign
   	2.	Install Backend Dependencies
   cd server
   npm install
   npm start
   	3.	Install Frontend Dependencies
   cd ../client
   npm install
   npm start
   	4.	Environment Setup
   	•	Create .env files in both client/ and server/ directories
   	•	Example for server/.env:
   ✍️ Author
   ```

Vansh Gupta
B.Tech 2nd Year Student
Developer & Builder of DOCSIGNAPP
GitHub – Vansh-1901
