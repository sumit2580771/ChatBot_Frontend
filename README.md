💬 Chat Application – Frontend

A modern real-time chat frontend built with React (Vite), React Router, Context API, and Tailwind CSS.
This application provides authentication, chat interface, and user state management with a clean and responsive UI.

🚀 Tech Stack
🖥️ Frontend

React 18

Vite

React Router DOM

Context API (Global State Management)

Axios

React Hot Toast

Tailwind CSS

React Icons

📁 Project Structure
chat-frontend
│
├── public
│   └── vite.svg
│
├── src
│   ├── assets
│   ├── components
│   │   ├── Header.jsx
│   │   ├── Loading.jsx
│   │   └── Sidebar.jsx
│   │
│   ├── context
│   │   ├── ChatContext.jsx
│   │   └── UserContext.jsx
│   │
│   ├── pages
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   └── Verify.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── index.html
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── vite.config.js

✨ Features

🔐 User Authentication (Login & Verification)

🌍 Protected Routes using React Router

💬 Chat UI with Sidebar

🔄 Global State using Context API

⚡ API communication using Axios

🔔 Toast Notifications

🎨 Modern UI with Tailwind CSS

📱 Fully Responsive Layout

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone <your-repo-url>
cd chat-frontend

2️⃣ Install Dependencies
npm install

3️⃣ Run Development Server
npm run dev


The app will run on:

http://localhost:5173

📦 Available Scripts
npm run dev      → Start development server
npm run build    → Build for production
npm run preview  → Preview production build
npm run lint     → Run ESLint

🧠 Architecture Overview
🔹 Context API

UserContext → Manages authentication and user session.

ChatContext → Manages chat state and messages globally.

🔹 Routing

Login → User login page

Verify → Verification page

Home → Main chat interface (protected)

🔹 API Handling

Axios handles backend communication.

Centralized state ensures efficient rendering and clean data flow.

🎨 Styling

This project uses:

Tailwind CSS

PostCSS

Autoprefixer

Utility-first CSS ensures faster UI development and responsive design.

🔮 Future Improvements

Real-time messaging with Socket.io

Message status indicators (Seen/Delivered)

File & image sharing

Dark mode toggle

Typing indicator

Deployment to Vercel
