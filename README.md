# Web-Based Code Editor 🚀

A lightweight, browser-based integrated development environment (IDE) built from scratch that allows users to write, compile, and preview HTML, CSS, and JavaScript code in real-time.

 <!-- Optional: Add an actual screenshot link here later -->

## 🔗 Links
- **Live Demo:** [View Live Site](https://gourgit.github.io/My-Code-Editor/)
- **GitHub Repository:** [GitHub Repo](https://github.com/yourusername/web-code-editor)

## ✨ Features
- **Real-Time Compilation:** Instantly view changes as you type with zero-delay hot reloading.
- **Iframe Sandboxing:** Safely isolates and executes custom HTML/CSS/JS without interfering with the parent application.
- **Persistent Storage:** Integrated `LocalStorage` to automatically save the user's latest code progress across browser sessions.
- **Responsive Layout:** Responsive side-by-side split screen interface designed for both wide monitors and smaller viewports.

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Storage:** Web Storage API (LocalStorage)

## 🚀 How It Works
1. **The Code Inputs:** The application utilizes distinct text inputs/textareas to separate structure (HTML), styling (CSS), and logic (JS).
2. **The Compiler Logic:** Using JavaScript, the app captures the live string inputs from all three sections on every keystroke.
3. **The Rendering Engine:** The inputs are merged dynamically into a compiled string template and injected into an isolated `<iframe>` using the `srcdoc` attribute to execute safely.

## 💻 Local Setup & Installation

To run this project locally, you don't need any complex servers—just a modern web browser.

1. **Clone the repository:**
```bash
   git clone [https://github.com/yourusername/web-code-editor.git](https://github.com/yourusername/web-code-editor.git)
