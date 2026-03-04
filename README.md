# Todo List App with AI Emoji Priority Detection

A sleek, responsive to-do list application built with plain HTML, CSS, and JavaScript. It uses localStorage to persist tasks and includes a simple AI-powered priority detector that automatically adds emojis based on keywords in the task description.

### 🚀 Features

- **Add, delete and complete tasks**
- **Filters**: view *All*, *Active*, or *Completed* items
- **Statistics**: shows total, active, and completed counts
- **Persistent storage** via browser `localStorage`
- **AI Emoji Priority Detection**:
  - 🔥 Tasks containing words like "urgent", "now", "important", etc. are marked with a fire emoji.
  - ☁️ Tasks mentioning "later", "maybe", or similar low-priority keywords get a cloud emoji.
- **Responsive and modern UI** with gradient background and interactive elements
- **Keyboard support**: press Enter to add a task

### 📁 Files

- `index.html` – main application file (HTML, CSS, JavaScript)

### 🛠️ Usage

1. Open `index.html` in your browser.
2. Type a task into the input box and click **Add** or press Enter.
3. Use the checkboxes to toggle completion, and the **Delete** button to remove tasks.
4. Filter tasks using the buttons underneath the input field.
5. View statistics at the bottom of the page.

Tasks are automatically saved in your browser and will be restored on page reload.

### 💡 Extending the App

This project serves as a simple foundation. You can expand it by:

- Adding due dates or reminders
- Integrating with a backend API for synchronization across devices
- Improving AI detection with more advanced natural language processing

### 📄 License

This project is available under the [MIT License](LICENSE) (if applicable).

---

Made with ❤️ and plain JavaScript.
