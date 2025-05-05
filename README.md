# Amazon-Themed UI & Queue Implementation Project

## 🔶 Overview

This project contains two major components:

1. **Amazon-themed Frontend Webpage** – A simple static UI that mimics a basic Amazon header.
2. **Queue Implementation in C** – A console-based implementation of queue operations like enqueue, dequeue, and display.

---

## 🌐 Frontend: Amazon Homepage Clone

### 🔸 Files:
- `index.html` – Contains the HTML structure of the homepage.
- `style.css` – Contains styles for the navigation bar and logo.
- `login.jpg`, `th.jpeg` – Image assets used in the UI.

### 🔸 Features:
- Responsive design for header section.
- Styled navigation bar with logo.
- FontAwesome CDN linked for future use of icons.

### 📸 Preview:
![Login Image](login.jpg)
![Theme Image](th.jpeg)

---

## 💻 Backend: Queue in C

### 🔸 File:
- `queue.c` – Implements a fixed-size linear queue using an array.

### 🔸 Features:
- Enqueue operation with overflow check.
- Dequeue operation with underflow check.
- Display operation to print queue contents.
- Menu-driven console interface.

### ⚠️ Note:
There are some syntax issues in the C code (like assignment `=` used instead of comparison `==`). These should be corrected for proper functionality.

---

## 🚀 How to Run

### Frontend:
1. Open `index.html` in any modern web browser.

### Backend (Queue):
1. Compile the `queue.c` file using a C compiler:
   ```bash
   gcc queue.c -o queue
   ./queue
**📂 Folder Structure**
├── index.html
├── style.css
├── login.jpg
├── th.jpeg
├── queue.c
