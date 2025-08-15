# 🌟 My Routine Database (Tkinter + Python)

A sleek and simple desktop GUI app to track daily routines — including Date, Earnings, Exercise, Study, Diet, and Python practice — built with Python’s Tkinter. Add, search, view, and delete records effortlessly, with a clean interface and a separate backend for data storage. 🗂️✨

## 🚀 Features

➕ Add new routine entries (Date, Earnings, Exercise, Study, Diet, Python)

🔎 Search records by any combination of fields

📜 View all records in a scrollable Listbox

🖱️ Select a row to auto-fill input fields

🗑️ Delete the selected entry by its database ID

❌ Close the app gracefully with a button

## 🧰 How It Works

Frontend: Tkinter widgets — Label, Entry, Listbox, Scrollbar, and Button.

Backend: A backend.py module providing database CRUD functions:

- insert(date, earnings, exercise, study, diet, python_field)

- view()

- search(date, earnings, exercise, study, diet, python_field)

- delete(id)

- Selecting an item in the Listbox fills the input fields for convenient review or deletion.

** Tip: Use a field name like python_field in the backend to avoid confusion with the Python language/module name.


### ✅ Prerequisites

🐍 Python 3.8+

🪟 Tkinter (bundled with most Python installations)

🗄️ SQLite3 (commonly used; included with Python’s stdlib)

### 🔧 Installation
bash
### Clone the repository
git clone [https://github.com/YOUR_GITHUB_USERNAME/REPO_NAME](https://github.com/DaRkAnon1mous/Routine_Planner.git)

cd REPO_NAME

<img width="468" height="322" alt="image" src="https://github.com/user-attachments/assets/207afbb2-8c67-4a76-b122-6b975f1475e3" />


