
# 🏢 Smart Complaint Management System

A full-stack MERN application that allows college students to securely voice their concerns regarding college facilities, hostel maintenance, canteen food, and other amenities.

## 🚀 Live Demo
- **Frontend (Vercel):** [https://campusvoice-ten.vercel.app]

## ✨ Key Features
- **Secure Authentication:** Implemented JWT (JSON Web Tokens) for safe user authentication and role-based authorization (Separate panels for Students and Admins).
- **Media Upload:** Integrated **Multer** and **ImageKit API** to allow students to upload photo proofs along with their complaints.
- **Real-time Status Tracking:** Students can track whether their complaint is *Pending*, *In Progress*, or *Resolved*.
- **Admin Dashboard:** Admins can view all complaints, filter them by category, and update their resolution status.

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS / Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Cloud Storage:** ImageKit.io
- **Deployment:** Vercel (Frontend), Render (Backend)

## 🔧 Installation & Setup
1. Clone the repository: `git clone https://github.com`
2. Install dependencies for both frontend and backend using `npm install`.
3. Create a `.env` file and set up your MongoDB URI, JWT Secret, and ImageKit credentials.
4. Run the project locally using `npm start` or `npm run dev`.
5.
