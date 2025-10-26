📝 To-Do List App

A simple and responsive To-Do List web app built using HTML, CSS, and JavaScript.
This project allows users to add, check off, and delete tasks — with all tasks saved in local storage so they remain even after refreshing the page.

🚀 Features

✨ Add Tasks: Quickly add new tasks to your list.

✅ Mark as Complete: Click on a task to mark it as completed.

❌ Delete Tasks: Remove unwanted tasks using the × icon.

💾 Persistent Storage: Automatically saves tasks to your browser’s local storage.

🔄 Auto-Load: Loads saved tasks every time you open the app.

🧠 How It Works

When you enter a task and click Add, a new <li> element is created and appended to the list.

Each task has a delete (×) button added as a <span> element.

Clicking a task toggles the “checked” class, which visually marks it as done.

Clicking the × removes the task.

The app saves all changes to localStorage so your tasks persist even after refreshing.

🧩 Code Overview
addTask()

Checks if the input is empty.

Creates a new list item (<li>) with a delete button (<span>).

Saves updated data to localStorage.

Event Listener on listContainer

Detects clicks on list items or delete buttons.

Toggles completion state or removes the task.

saveData() and showTask()

saveData(): Saves the current task list HTML to localStorage.

showTask(): Loads stored tasks when the page loads.

🗂️ File Structure
📁 ToDo-List/
│
├── index.html          # Main HTML structure
├── style.css           # Styling for the app
├── script.js           # JavaScript logic (your provided code)
└── README.md           # Project documentation

💡 Example Usage

Type your task in the input box.

Click Add or press Enter.

Click on a task to mark it done.

Click the × to delete a task.

Refresh — your tasks stay saved!

🧰 Technologies Used

HTML5 – Page structure

CSS3 – Styling and layout

JavaScript (ES6) – Core functionality

LocalStorage API – Data persistence

🖼️ Demo (Optional)

If you’ve hosted it (e.g., on GitHub Pages or Netlify), you can add:

🔗 Live Demo

📄 License

This project is open-source and available under the MIT License