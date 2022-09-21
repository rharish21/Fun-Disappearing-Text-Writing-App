# Disappearing Text Writing App

A Python-based writing application built using the `tkinter` library. The app challenges users to keep typing, as the text they write will disappear if they stop for more than a few seconds. This project is a fun way to practice focus and typing speed.

---

## Features

- **Disappearing Text**: If the user stops typing for a set amount of time (e.g., 5 seconds), the text will disappear.
- **Focus Mode**: Encourages continuous writing without distractions.
- **Simple Interface**: Easy-to-use GUI for a seamless writing experience.

---

## How It Works

The app starts a timer when the user begins typing. If the user stops typing for more than the specified time limit, the text in the input area is cleared. This encourages users to keep writing without pauses.

---

## Technologies Used

- **Python**: Core programming language.
- **Tkinter**: Used for creating the graphical user interface (GUI).
- **Time Module**: Used to track the elapsed time since the last keystroke.

---

## How to Use

1. Clone the repository:

```bash
   git clone https://github.com/your-username/disappearing-text-app.git
```
2. Navigate to the project directory:

```bash
cd disappearing-text-app
```
3. Run the program:

```bash
python main.py
```
4. Start typing in the text box. If you stop typing for more than 5 seconds, the text will disappear.