# 📝 Notes App (Google Keep Clone)

A simple, modern **Notes App** built with **Vanilla JavaScript**. This project is designed as a step-by-step learning journey, helping you master JavaScript from beginner to advanced concepts.

---
## 🚀 Features

- **Add, Edit, and Delete Notes**
- **Persistent Storage** (via Local Storage)
- **Search & Filter Notes**
- **Drag & Drop Reordering**
- **Dark Mode Toggle**
- **Responsive Design**
- **Rich Text Editing** (bold, italic, lists)
- **Note Pinning & Archiving**
- **Reminders & Notifications** (using the Notifications API)
- **Color-coded Notes**
- **Tagging & Filtering by Tags**
- **Undo/Redo Note Changes** (using the Command Pattern)
- **Bulk Actions** (select multiple notes to delete/archive)
- **Export Notes** (PDF / Text file)
- **Voice-to-Text Note Input** (Web Speech API)
- *(Optional)* **PWA Support** (offline-ready)

---

## 🧑‍💻 JavaScript Concepts Covered

- Variables, Data Types, Operators, Functions
- DOM Manipulation (create, edit, delete elements)
- Event Handling
- Local Storage API
- ES6+ Features (Classes, Modules, Template Literals, Destructuring, Spread)
- Array & Object Methods (`map`, `filter`, `forEach`, `find`, `reduce`, `some`, `every`)
- Asynchronous JavaScript (`fetch`, `async/await`, Promises)
- Modular Project Structure
- **Custom Events & Event Bubbling**
- **Observer Pattern** (for UI updates)
- **Command Pattern** (for Undo/Redo)
- **Debouncing & Throttling** (for search/filter)
- **Web APIs** (Notifications, Speech Recognition, Clipboard)
- **Error Handling & Validation**
- **Accessibility (a11y) Enhancements**
- **Unit Testing** (with Jest or similar)

---

## 📂 Project Structure

```
notes-app/
├── index.html
├── style.css
├── /js
│   ├── app.js        # Main logic & rendering
│   ├── storage.js    # LocalStorage helpers
│   ├── note.js       # Note class (OOP)
│   ├── commands.js   # Undo/Redo logic (Command Pattern)
│   ├── observer.js   # Observer pattern for UI updates
│   ├── tags.js       # Tagging logic
│   ├── reminders.js  # Reminders & Notifications
│   ├── voice.js      # Voice-to-text input
│   └── utils.js      # Utility functions
└── /assets
    └── icon.png
```

---

## 🛠️ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nirajkumardangi/notes-app-js.git
   ```
2. **Navigate to the project folder:**
   ```bash
   cd notes-app
   ```
3. **Open `index.html` in your browser:**
   - Double-click the file, or
   - Use: `start index.html` (Windows) or `open index.html` (Mac)

---

## 🏗️ Learning Roadmap

Each step introduces new JavaScript concepts:

1. **Basic Setup** – Add Note button (Variables, Functions, Events)
2. **DOM Manipulation** – Display notes dynamically
3. **Edit & Delete** – Update and remove notes
4. **Local Storage** – Persist notes after refresh
5. **Search / Filter** – Filtering with `filter()`
6. **OOP with Classes** – Note class, Encapsulation
7. **ES6+ Features** – Template literals, Destructuring, Spread
8. **Async JS** – Fetch random quotes (optional)
9. **Extras** – Dark mode, Drag & Drop, PWA support
10. **Rich Text Editing** – Contenteditable, execCommand
11. **Pin/Archive Notes** – Array methods, UI state
12. **Reminders & Notifications** – setTimeout, Notifications API
13. **Color-coded Notes** – Dynamic styling
14. **Tagging** – Sets, filtering, tag UI
15. **Undo/Redo** – Command Pattern, history stack
16. **Bulk Actions** – Array methods, selection logic
17. **Export/Import** – File API, JSON
18. **Voice-to-Text** – Web Speech API
19. **Testing** – Unit tests for core logic

---

## ✅ Progress Checklist

| Step | Feature                  | Concepts Covered                          | Status |
|------|--------------------------|-------------------------------------------|--------|
| 1    | Add Note                 | Variables, Events                         | ⬜      |
| 2    | DOM Manipulation         | createElement, appendChild                | ⬜      |
| 3    | Edit & Delete            | Event Handling, DOM Traversal             | ⬜      |
| 4    | Local Storage            | JSON, localStorage                        | ⬜      |
| 5    | Search / Filter          | Array methods (`filter`, `map`)           | ⬜      |
| 6    | OOP with Classes         | Classes, Encapsulation                    | ⬜      |
| 7    | ES6+ Syntax              | Template literals, Spread, Destructuring  | ⬜      |
| 8    | Async (Quotes API)       | fetch, async/await                        | ⬜      |
| 9    | Extra Features           | Dark Mode, Drag & Drop                    | ⬜      |
| 10   | Rich Text Editing        | contenteditable, execCommand              | ⬜      |
| 11   | Pin/Archive Notes        | Array methods, UI state                   | ⬜      |
| 12   | Reminders/Notifications  | setTimeout, Notifications API             | ⬜      |
| 13   | Color-coded Notes        | Dynamic styling                           | ⬜      |
| 14   | Tagging                  | Sets, filtering, tag UI                   | ⬜      |
| 15   | Undo/Redo                | Command Pattern, history stack            | ⬜      |
| 16   | Bulk Actions             | Array methods, selection logic            | ⬜      |
| 17   | Export/Import            | File API, JSON                            | ⬜      |
| 18   | Voice-to-Text            | Web Speech API                            | ⬜      |
| 19   | Testing                  | Unit tests                                | ⬜      |

---

## 🎯 Learning Goals

By completing this project, you’ll gain confidence in:

- DOM Manipulation
- Event Handling
- State Management with Local Storage
- Modern JavaScript (ES6+)
- OOP in JS
- Asynchronous Programming
- Building Modular, Scalable JS Apps
- Advanced JS Patterns (Observer, Command)
- Using Web APIs (Notifications, Speech, Clipboard)
- Testing and Debugging

---

## 📸 Preview

*screenshot*

---

## 🤝 Contributing

Want to add features? Fork this repo and submit a pull request! Ideas:

- Reminders/Alarms
- Cloud sync (e.g., Firebase)
- Collaboration (real-time editing)
- More themes

---

## 📜 License

MIT License. Free for personal and commercial use.