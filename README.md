# 💻 Code Editor App

A **React-based code editor application** that lets you **write, edit, and preview HTML, CSS, and JavaScript code in real-time**.  
Built with **CodeMirror** for an enhanced editing experience, it also leverages **localStorage** to persist your work even after refreshing the page.

---

## ✨ Features

- 🖊️ **Simultaneous Editing** → Write HTML, CSS, and JavaScript code side by side
- ⚡ **Real-Time Preview** → Updates live in an iframe every 250ms
- 🎨 **Syntax Highlighting** → Improved readability for HTML, CSS, and JavaScript
- ↔️ **Line Wrapping** → Prevents horizontal scrolling with auto line breaks
- ✅ **Linting** → Real-time feedback on syntax errors and issues
- 📂 **Collapsible Editors** → Focus on a specific editor by toggling panes
- 💾 **Persistent Storage** → Saves code automatically to `localStorage`

---

## 🛠️ Tech Stack

- ⚛️ **React** — Frontend framework
- 📝 **CodeMirror** — Code editor component
- 🗄️ **localStorage** — Persistent storage for code
- 🎨 **CSS** — Styling

---

## 🚀 Getting Started

### Prerequisites
- Node.js 16+
- npm or yarn

### 1️⃣ Clone the repository
```bash
git clone https://github.com/chhavikansal08/Code-Editor.git
cd Code-Editor
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Start the development server
```bash
npm run dev
```

---

## 🖥️ Usage

1. Enter your HTML, CSS, and JavaScript code in their respective editors
2. View the live **preview pane** (updates automatically every 250ms)
3. Toggle editor panes to focus on a specific section
4. Your code is **saved automatically** in `localStorage` and restored on reload

---


### Key Components

- **App Component** → Manages state for HTML, CSS, and JS, updates the preview iframe
- **Editor Component** → Uses **CodeMirror** for syntax highlighting, linting, and editing features
- **useLocalStorage Hook** → Stores and retrieves code from browser `localStorage`
- **Styles** → Defines layout for editor panes and preview window

---


## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---


## ⭐ Acknowledgments

- Built with ❤️ using **React + CodeMirror**
- Inspired by **CodePen/JSFiddle** style editors

---

## 🔗 Live Demo

[View Live Demo](https://my-react-project-rwf1.vercel.app/) 

---

## 📞 Support

If you like this project, please consider giving it a ⭐ on GitHub!

For questions or support, please open an issue in the GitHub repository.
