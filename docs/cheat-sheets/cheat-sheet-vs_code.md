**© 2025 Hamadi Sy. All Rights Reserved. Unauthorized distribution or reproduction is strictly prohibited.**

---

## 🚀 80/20 Principle: The Essential 20% of VS Code for Full-Stack Web-Developers to cover 80% of their daily tasks

---

# 🎯 Purpose
Visual Studio Code is a free, powerful code editor (IDE) that helps you write, debug, and manage code for almost any programming language.

---

# 🌱 Origin
The name Visual Studio Code (VS Code) links it to Microsoft's "Visual Studio" developer tools, with "Code" added to distinguish it as a focused editor. The first stable version was released on April 2016.

---

# ⚙️ Ubuntu Installation
```bash Installation
# Follow the official installation guide https://code.visualstudio.com/docs/setup/linux 

# Download VS Code installer and save it to /tmp/code.deb, use current URL from official website
wget -qO- https://go.microsoft.com/fwlink/?LinkID=760868 -O /tmp/code.deb
# Install VS Code
sudo apt install /tmp/code.deb
# Reload shell
exec $SHELL
# Verify VS Code version:
code -v
```

```bash uninstallation
# To uninstall VS Code
sudo apt remove code; sudo apt purge code
# remove config files
rm -rf ~/.config/Code; rm -rf ~/.vsCode
# remove package metadata
sudo apt autoremove; sudo apt clean
```

# 🧠 Essentials

## 🛠 Useful VS Code shortcuts

* **Keyboard Shortcuts** (`Ctrl+K Ctrl+S`): Show/update keyboard shortcuts
* **Command Palette** (`Ctrl+Shift+P`): Access all commands quickly.
* **File Navigation** (`Ctrl+P`): Jump to any file instantly.
* **Multi-cursor Editing** (`Alt+Click`): Efficient code changes.
* **Code Navigation**: Go to definition (`F12`), rename (`F2`).
* **Copy line up / down**: (`Shift+Alt + ↓ / ↑ `)
* **Integrated Terminal** (`Ctrl+Shift+´`): Run commands without leaving VS Code.

## 📂 Project & Source Control

* **Explorer Sidebar**: Navigate files and folders.
* **Git Integration**: Commit, push, pull, and branch handling directly in VS Code.
* **.gitignore Management**: Exclude files from version control.

## 🧩 Extensions (Key Ones)

* **Prettier**: Code formatting  
     → configure as default formatter
* **ESLint**: JavaScript/TypeScript Code Quality Tracker (linting)  
     → see real time code warnings
* **Live Server**: Instant frontend deployment & preview  
     → open HTML-File in Browser. Code updates not visible in browser
     → open HTML-File with live server. Code updates visible in browser
* **HTML/CSS/JS Support**: Syntax highlighting, snippets, IntelliSense for efficient FE dev
* **PlantUML**: Diagrams Viewer
* **Draw.io**: Diagrams Viewer
* **GitLens**: Changes Tracker (what line of code, when, & why)
* **REST Client**: Test APIs directly from VS Code

## 🧰 Build-In Productivity Boosters

* **IntelliSense**: Autocompletion and documentation. see. https://code.visualstudio.com/docs/editing/intellisense
* **Emmet**: Fast HTML/CSS writing. see: https://code.visualstudio.com/docs/languages/emmet

---
