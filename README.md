# 🧮 Calculator Project – C (Shared)

👥 Shared with ALI CS Club

---

This is the **shared C calculator repository** for ALI CS Club members.  
It includes both versions:
- `cli/` – A terminal-based calculator written in C.
- `gui/` – A graphical calculator built using the GTK library.

Each version is stored in its own folder, with a single entry-point `.c` file.

---

## 📁 Project Structure

```
calculator-c-shared/
├── cli/
│   └── calculator.c              # CLI version – compile with gcc
└── gui/
    └── calculator_gui.c         # GUI version – built with GTK
```

---

## 🚀 How to Run

### CLI Version

```bash
cd cli
gcc calculator.c -o calculator
./calculator
```

### GUI Version (GTK)

> ⚠️ Requires GTK (e.g., GTK 3 or 4) to be installed on your system

```bash
cd gui
gcc calculator_gui.c `pkg-config --cflags --libs gtk4` -o calculator_gui
./calculator_gui
```

---

## 🤝 Contribution Guidelines

- If you're working **independently**, please **fork** this repo or create a new **branch**, and submit a **pull request** when your work is ready to merge.
- If you're working **together with a club member** (e.g., in a meeting), only **one person should edit and push at a time** to avoid conflicts.
- Keep code clean, well-documented, and placed in the appropriate folder (`cli/` or `gui/`).

---

## 🧠 Purpose

This project helps members strengthen:
- Knowledge of pointers, memory, and C syntax (CLI version)
- Understanding of GUIs and event-driven architecture with GTK (GUI version)
- GitHub-based collaboration and version control in a low-level language

Happy coding in C!
