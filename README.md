# 📝 Éditeur de Texte Simplifié

A simple text editor built in **C** that allows dynamic text management with advanced string operations. This project uses standard C libraries and demonstrates linked lists, stacks, and queue structures.

---

## 🛠 Technologies
- 🖥 C (Core logic and text manipulation)
- 📂 Standard C libraries (`stdio.h`, `stdlib.h`, `string.h`)
- 💾 Data structures: Linked lists, Stack, Queue

---

## ✨ Features
- Add a line at a specific position (^A)  
- Delete a line (^D)  
- Search for a word in the text (^S)  
- Replace a word with another (^R)  
- Undo last action (^Z)  
- Quit the editor safely (^X)

---

## ⌨ Keyboard Shortcuts
| Shortcut | Action |
|----------|--------|
| ^A       | Add a line |
| ^D       | Delete a line |
| ^S       | Search for a word |
| ^R       | Replace a word |
| ^Z       | Undo last action |
| ^X       | Exit editor |

---

## 🔄 How the Process Works
1. The text is stored line by line in a **dynamic queue** implemented with linked lists.  
2. **Adding/deleting lines** updates the linked list nodes dynamically.  
3. **Search and replace** traverse all lines and highlight or update occurrences.  
4. **Undo** uses a stack to store each action and revert changes when needed.  
5. The `main()` function handles the interface using `getch()` and `switch-case` for shortcuts.

---

## 🧠 What I Learned
- Dynamic memory management (`malloc`, `free`, `strdup`)  
- Implementing **Undo** with stacks  
- Searching and replacing words efficiently in dynamic text  
- Modular coding for maintainable and interactive applications

---

## 🚀 How It Can Be Improved
- Add support for **copy/paste** functionality  
- Highlight multiple occurrences with colors in console  
- Save/load multiple files  
- Implement a **GUI** interface with libraries like SDL2 (optional)

---

## ▶ How to Run the Project
1. Clone the repository:  
```bash
git clone <your-repo-link>
