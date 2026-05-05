# 🛰️ Mission Control — Task Manager

A lightweight, futuristic task management app built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no installation required — just open the file in your browser and start managing your missions.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat)

---

## ✨ Features

- **Priority levels** — Mark tasks as High, Medium, or Low priority with color-coded indicators
- **Due dates** — Assign due dates with automatic overdue detection and visual warnings
- **Reminder notifications** — Set a reminder time per task; get notified (in-app + browser) if the task hasn't been started
- **Live task timer** — Start and pause a timer on any task to track how long you've been working on it
- **Drag to reorder** — Reorganize tasks by dragging them into any order
- **Filter & sort** — View All / Active / Done tasks, and sort by Priority or Due Date
- **Persistent storage** — Tasks are saved to `localStorage` and survive page refreshes or browser restarts
- **Fully offline** — No internet connection, server, or account needed

---

## 🚀 Getting Started

### Option 1 — Direct download

1. Download [`mission-control.html`](./mission-control.html)
2. Double-click the file to open it in your browser
3. That's it — you're ready to go

### Option 2 — Clone the repo

```bash
git clone https://github.com/mohamedhegazy010091-spec/mission-control.git
cd mission-control
open mission-control.html   # macOS
start mission-control.html  # Windows
```

> No build step. No `npm install`. No config files. Just open and use.

---

## 🖥️ Preview

> A clean, soft blue & white interface with a futuristic HUD-style layout.

- Stats bar showing total / active / completed task counts
- Input panel for adding tasks with priority, due date, and reminder time
- Task list with live timers, drag handles, and quick-action buttons

---

## 🗂️ Project Structure

```
mission-control/
└── mission-control.html   # The entire app — self-contained single file
```

---

## 🔔 Notifications

Browser notifications require permission. On first load, the app will request permission automatically. If you missed it:

1. Click the lock icon in your browser's address bar
2. Set **Notifications** to **Allow**
3. Reload the page

> Reminders fire when the clock matches the time you set on a task — as long as the file is open in a browser tab.

---

## 💾 Data & Privacy

All data is stored locally in your browser using `localStorage`. Nothing is sent to any server. Clearing your browser's site data will erase your tasks.

---

## 🛠️ Built With

- **HTML5** — structure and layout
- **CSS3** — styling, animations, and responsive design
- **Vanilla JavaScript** — all logic, timers, drag-and-drop, and storage

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a pull request

---

*Built with ❤️ using zero dependencies.*
