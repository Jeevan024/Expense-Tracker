
💸 Expense Tracker

A modern and responsive Expense Tracker web application built using React.js, Tailwind CSS, and Context API. This app helps users efficiently manage and visualize their daily expenses.

---

🚀 Features

- ➕ Add new expenses
- ✏️ Update existing expenses
- ❌ Delete expenses
- 📊 Visualize expenses using charts
- 💾 Persistent data storage using LocalStorage
- 🔔 Real-time notifications with toast messages
- 📱 Fully responsive UI

---

🛠️ Tech Stack

- Frontend: React.js
- Styling: Tailwind CSS
- State Management: Context API + useReducer
- Charts: (Recharts / Chart.js)
- Notifications: react-hot-toast
- Build Tool: Vite

---

📂 Project Structure

src/
├── components/
│ ├── ExpenseForm.jsx
│ ├── ExpenseList.jsx
│ ├── ExpenseChart.jsx
│ └── ExpenseSummary.jsx
├── context/
│ └── ExpenseContext.jsx
├── layout/
│ └── DashboardLayout.jsx
├── pages/
│ └── Index.jsx
├── App.jsx
└── main.jsx

---

⚙️ Installation & Setup

# Clone the repository
git clone https://github.com/Jeevan024/Expense-Tracker.git

# Navigate to project folder
cd Expense-Tracker

# Install dependencies
npm install

# Run the development server
npm run dev

---

💡 How It Works

- User adds an expense through the form
- Data is managed globally using Context API
- Reducer updates the state (add/delete/update)
- Changes are automatically saved to LocalStorage
- UI components (list, charts, summary) update in real-time

---

🎯 Future Improvements

- Add authentication (login/signup)
- Connect with backend (Node.js / MongoDB)
- Add filters and category-wise insights

---

⭐ Acknowledgements

This project was built for learning and improving frontend development skills using modern React practices.
