# 🎓 StudentHub – Student Dashboard

A simple and interactive **Student Dashboard** built using React.js. It helps students view course information, track learning progress, monitor attendance, and manage completed assignments through a clean dashboard interface.

## 🚀 Key Features

- 📊 **Dashboard Overview** – Displays important student statistics.
- 📚 **Total Courses** – Shows the total number of enrolled courses.
- ✅ **Completed Courses** – Displays completed course statistics.
- 📅 **Attendance Tracking** – Shows the student's attendance percentage.
- 🔍 **Course Search** – Search and filter courses dynamically.
- 📈 **Course Progress** – Displays individual course completion progress.
- 📝 **Assignment Counter** – Tracks completed assignments.
- 🔄 **Reset Functionality** – Resets the assignment counter to zero.
- 🧩 **Reusable Components** – Uses a separate StatCard component.
- ⚡ **React State Management** – Uses the useState Hook for interactive features.

## 🛠️ Technologies Used

- React.js
- JavaScript (ES6+)
- HTML5
- CSS3
- Vite
- React Hooks (useState)

## 📂 Project Structure

```text
student-dashboard/
│
├── public/
├── src/
│   ├── components/
│   │   └── StatCard.jsx
│   │
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
│
├── index.html
├── package.json
└── README.md
```

## ⚙️ Installation and Setup

**Step 1: Clone the Repository**

```bash
git clone <your-repository-url>
```

**Step 2: Navigate to the Project Folder**

```bash
cd student-dashboard
```

**Step 3: Install Dependencies**

```bash
npm install
```

**Step 4: Start the Development Server**

```bash
npm run dev
```

**Step 5: Open in Browser**

Visit the local URL displayed in your terminal, usually:

```text
http://localhost:5173/
```

## 💡 React Concepts Learned

1. Functional Components
2. JSX Syntax
3. Import and Export
4. useState Hook
5. Event Handling (onClick, onChange)
6. Array Methods (filter and map)
7. Conditional Data Rendering
8. Reusable Components
9. Props and Component Communication
10. Dynamic Search Functionality

## 🎯 Learning Outcomes

- Learned how to build a dashboard using React.
- Understood component-based architecture.
- Practiced managing data using the useState Hook.
- Implemented dynamic course searching.
- Learned to display course progress using HTML progress elements.
- Understood how reusable components improve code organization.

## 👨‍💻 Developer

**G Shahith**

B.E. Computer Science and Engineering (AI & ML)

Mohamed Sathak A.J. College of Engineering, Chennai

---

⭐ If you find this project useful, consider giving it a star!# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
