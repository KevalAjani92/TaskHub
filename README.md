# 🚀 Project Management Dashboard

A modern, responsive **Project Management Dashboard** built using **React**, **Vite / React Router v7**, **TypeScript**, and **Tailwind CSS v4**, powered by **Shadcn UI** components.

The application helps teams manage workspaces, projects, tasks, and collaboration efficiently with a clean and scalable architecture.

The frontend communicates with a **Node.js + Express.js** backend and uses **MongoDB** as the database.

---

# 🌐 Live Demo

🔗 **Live Preview:** [Click Here To Visit](https://task-hub-steel.vercel.app/)


---

# ✨ Features

## 📊 Dashboard Overview
- Project statistics and analytics
- Task progress tracking
- Activity overview
- Workspace insights

## 🏢 Workspace Management
- Create and manage multiple workspaces
- Invite and manage members
- Workspace-level permissions

## 📁 Project Management
- Create and organize projects
- Track project status and progress
- Assign members to projects

## ✅ Task Management
- Create, update, delete tasks
- Task priorities and statuses
- Due dates and assignments
- Subtasks support
- Activity logs and history tracking
- Task comments and discussions
- Mentions (`@username`)
- Emoji reactions

## 👤 User Profile Management
- Update profile details
- Avatar upload support
- Account settings management

## 🔔 Notifications
- Real-time notification system
- Task updates and mentions
- Project activity alerts

## 🔐 Authentication & Security
- Sign In / Sign Up
- Forgot Password
- Reset Password
- Email Verification
- Two-Factor Authentication (2FA)
- Secure authentication flow

## 📂 Attachments
- Upload files
- Add external URLs as attachments

## 📌 Archived / Achieved Work
- Achieved projects
- Completed task history

## 📱 Responsive Design
- Fully responsive UI
- Optimized for desktop, tablet, and mobile devices

---

# 🛠️ Tech Stack

## Frontend
- React
- TypeScript
- Vite
- React Router v7
- Tailwind CSS v4
- Shadcn UI
- Axios
- React Hook Form
- Zustand / Context API

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

---

# 📂 Project Structure

```bash
src/
│
├── app/
├── components/
├── features/
├── hooks/
├── layouts/
├── lib/
├── pages/
├── routes/
├── services/
├── store/
├── types/
├── utils/
└── styles/
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/project-management-dashboard.git

cd project-management-dashboard
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

---

## 3️⃣ Setup Environment Variables

Create a `.env` file in the root directory.

```env
VITE_API_BASE_URL=http://localhost:5000/api
```

---

## 4️⃣ Run the Development Server

```bash
npm run dev
```

Application will run on:

```bash
http://localhost:5173
```

---

# 🔧 Backend Setup

Make sure the backend server is running.

## Backend Requirements
- Node.js
- Express.js
- MongoDB

## Example Backend `.env`

```env
PORT=5000

MONGODB_URI=your_mongodb_connection

JWT_SECRET=your_secret_key

CLIENT_URL=http://localhost:5173
```

---

# 🧪 Available Scripts

```bash
npm run dev        # Start development server

npm run build      # Build for production

npm run preview    # Preview production build

npm run lint       # Run ESLint
```

---

# 📸 Screenshots

> Add your application screenshots here

- Dashboard
- Project Board
- Task Details
- Authentication Pages
- Notifications
- Mobile Responsive UI

---

# 🌟 Future Improvements

- Real-time collaboration with Socket.io
- Kanban drag & drop
- Team chat system
- Calendar integration
- Advanced analytics
- Role-based access control (RBAC)
- AI-powered productivity insights

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create your feature branch

```bash
git checkout -b feature/amazing-feature
```

3. Commit your changes

```bash
git commit -m "Add amazing feature"
```

4. Push to the branch

```bash
git push origin feature/amazing-feature
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed by **Keval Ajani**

- Full Stack Developer
- MERN & ASP.NET Developer

---

# 💡 Notes

This project is built with scalability, maintainability, and modern frontend architecture in mind, making it suitable for real-world team collaboration and project management workflows.
