# 🧑‍💼 React Employee Task Dashboard

This project is a beginner-friendly React app that simulates a basic task management system for employees and admins. It includes role-based dashboards, authentication, task handling, and local data storage.

## 🚀 Features

- 🔐 **Login System**: Simulated login system using React Context API.
- 👥 **Role-based Dashboards**:
  - **Employee Dashboard**: View and manage assigned tasks.
  - **Admin Dashboard**: Manage users and assign tasks.
- 📦 **React Context API**: For managing global authentication and task states.
- 💾 **Local Storage**: Persists data like login sessions and tasks across refreshes.
- 🧠 **AI-assisted Data Creation**: Uses ChatGPT-generated sample data.
- 🔄 **Logout & Session Management**: Easily switch between users with session awareness.

## 🛠️ Tech Stack

- **React**
- **React Router**
- **Tailwind CSS** (optional if you used it)
- **Context API**
- **LocalStorage API**

## 📂 Project Structure
/src
├── components
│   ├── Dashboard.jsx         # Reusable dashboard layout
│   ├── Login.jsx             # Login form component
│   └── TaskList.jsx          # Task list display component
│
├── context
│   ├── AuthContext.jsx       # Handles authentication state
│   └── TaskContext.jsx       # Manages task-related state
│
├── pages
│   ├── AdminDashboard.jsx    # Admin-specific dashboard view
│   ├── EmployeeDashboard.jsx # Employee-specific dashboard view
│   └── Login.jsx             # Login page (might reuse Login component)
│
├── utils
│   └── storage.js            # Utility functions for localStorage handling
│
├── App.jsx                   # Root component with routing logic
└── main.jsx                  # Entry point that mounts the app


## 📦 Installation & Setup

1. **Clone the Repository**
   ```bash
2. git clone https://github.com/your-username/employee-task-dashboard.git
   cd employee-task-dashboard
3. Install Dependencies
    npm install
4. Run the App
    npm run dev
5.Open http://localhost:5173 in your browser.

📝 Future Improvements
Integrate a real backend (e.g., Node/Express + MongoDB)
Add user registration
Add task filtering, status updates
Improve UI with animations and better UX
