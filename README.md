# 📝 Task Manager & Productivity Dashboard

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/qwerty274/taskmanager-nsoc2)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-v4.0+-FF6384?style=flat&logo=chart.js&logoColor=white)](https://www.chartjs.org/)

A sleek, responsive, and feature-rich Web Task Management Application built using pure Vanilla JavaScript, HTML5, and CSS3, with analytics charts powered by [Chart.js](https://www.chartjs.org/).

Designed for clarity, focus, and ease of use, Task Manager allows users to track active items, categorize by priority, edit inline, monitor overdue tasks, inspect historical completion trends, and visualize productivity stats.

---

## ✨ Key Features

- ⚡ **Task Management**: Create tasks with custom due dates and priority tags (Low, Medium, High).
- ✏️ **Inline Double-Click Editing**: Double-click any task title to edit it inline on the fly.
- 🚨 **Overdue Detection**: Automatic visual highlighting for overdue active tasks.
- 📆 **Month-wise Task Grouping**: Groups tasks by due month for organized long-term planning.
- 📊 **Productivity Analytics Dashboard**:
  - **Priority Breakdown**: Pie chart displaying task distribution across priorities.
  - **Monthly Completion Trends**: Interactive bar chart tracking weekly completions with month-by-month navigation.
- ⏳ **History & Filtering**: Toggle history view to filter tasks by `All`, `Active`, `Done`, or `Overdue`.
- 💾 **Local Storage Persistence**: Automatically saves data in browser `localStorage` — no server or database required.
- 🌙 **Modern Dark Theme**: Styled with a modern dark theme featuring glassmorphism, responsive grid layouts, and soft animations.
- ♿ **Accessible & Responsive**: Keyboard navigable, WCAG compliant contrast, and optimized for mobile, tablet, and desktop screens.

---

## 🛠️ Tech Stack

| Technology | Role |
| :--- | :--- |
| **HTML5** | Semantic layout & accessible form controls |
| **CSS3** | Vanilla CSS, CSS Variables (`:root`), Flexbox, Grid, Glassmorphism, Animations |
| **JavaScript (ES6+)** | DOM manipulation, state handling, `localStorage` API, Event Delegation |
| **Chart.js** | Interactive data visualization for task analytics |

---

## 📁 Project Structure

```text
taskmanager/
├── index.html                # Main application structure & container
├── style.css                 # Custom design system, layout, and theme styles
├── script.js                # Core app logic, state management, and Chart.js integration
├── netlify.toml              # Netlify deployment configuration & security headers
├── README.md                 # Project documentation & overview
├── CONTRIBUTING.md           # Guidelines for open-source contributors
├── CODE_OF_CONDUCT.md        # Community behavior standards
├── LICENSE                   # MIT Open Source License
├── .gitignore                # Ignored files for Git tracking
└── .github/                  # Issue & Pull Request templates
    ├── PULL_REQUEST_TEMPLATE.md
    └── ISSUE_TEMPLATE/
        ├── bug_report.md
        └── feature_request.md
```

---

## 🚀 Quick Start & Local Setup

No node packages, build steps, or servers are required!

### Method 1: Direct File Open
1. **Clone the repository:**
   ```bash
   git clone https://github.com/qwerty274/taskmanager-nsoc2.git
   cd taskmanager-nsoc2
   ```
2. **Open in browser:**
   Double-click `index.html` or open it directly in your favorite browser (Chrome, Firefox, Edge, Safari).

### Method 2: Live Server (VS Code Extension)
1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Click **"Go Live"** in the bottom status bar or right-click `index.html` -> `Open with Live Server`.

---

## 🤝 Contributing

We welcome contributions of all kinds! Whether you are fixing a bug, adding new features, improving documentation, or refining accessibility, your help is appreciated.

Please check out our **[CONTRIBUTING.md](CONTRIBUTING.md)** guide before submitting a Pull Request.

### Quick Workflow
1. **Fork** the repository on GitHub.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/taskmanager-nsoc2.git
   ```
3. **Create a branch**:
   ```bash
   git checkout -b feature/amazing-feature
   ```
4. **Commit** your changes following Conventional Commits format:
   ```bash
   git commit -m "feat: add drag-and-drop task reordering"
   ```
5. **Push** to your fork and open a **Pull Request**.

---

## 🗺️ Roadmap & Ideas for Future Contributors

Looking for ideas to contribute? Here are some recommended features:

- [ ] **Drag and Drop**: Reorder tasks using HTML5 Drag and Drop API.
- [ ] **Tags & Categories**: Add custom tags/labels to tasks.
- [ ] **Export / Import**: Backup tasks to JSON or CSV files.
- [ ] **Subtasks / Checklist**: Breakdown tasks into smaller sub-items.
- [ ] **Dark / Light Mode Toggle**: Allow users to switch between themes.
- [ ] **PWA Support**: Offline capability with Service Workers and Web Manifest.

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more details.

---

## 💬 Questions or Feedback?

Feel free to open an issue or start a discussion on the [GitHub Repository](https://github.com/qwerty274/taskmanager-nsoc2)!
