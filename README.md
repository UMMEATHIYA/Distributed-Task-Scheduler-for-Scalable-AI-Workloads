# Distributed Task Scheduler

A simple web-based Distributed Task Scheduler that allows users to submit, schedule, and track tasks.

## 🚀 Features
- Add and schedule tasks via a modal form.
- Store tasks in `localStorage` for persistence.
- Display tasks in a table with status updates.
- Automatic status updates from "Scheduled" → "Running" → "Completed".

## 🛠️ Technologies Used
- **HTML**: Structure
- **Bulma CSS**: Styling
- **JavaScript**: Functionality
- **localStorage**: Data persistence

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd distributed-task-scheduler
   ```
2. Open `index.html` in a browser **or** start a simple local server:
   ```bash
   python3 -m http.server 8000
   ```
3. Visit `http://localhost:8000` in your browser.

## 📷 Screenshot
![Distributed Task Scheduler UI]![image](https://github.com/user-attachments/assets/8cec0fbf-feb0-4ac8-879f-e3a201c1c012)


## 📄 File Structure
```
/distributed-task-scheduler
│── index.html         # Main UI
│── styles.css         # Custom styles (if any)
│── script.js          # Main JavaScript logic
│── README.md          # Documentation
└── run.sh             # Bash script to start the server
```

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).

---
Happy Scheduling! 🚀
