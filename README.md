# Spell-Checker-with-sqlite3-database
The Smart Spell Checker with History is a Python-based GUI application built using Tkinter. It helps users check and correct spelling mistakes in real-time while maintaining a history of corrections using an SQLite database.

## 📌 Project Description
The **Spell-Checker-with-sqlite3-database** is a Python-based GUI application built using **Tkinter**. It helps users check and correct spelling mistakes in real-time while maintaining a history of corrections using an SQLite database.

## ✅ Features
- **Real-time Spell Checking** – Detects and corrects misspelled words using the `spellchecker` library.
- **History Tracking** – Stores previous spell checks in a database and displays them.
- **User-Friendly Interface** – Simple and intuitive GUI for easy interaction.
- **Persistent Storage** – Saves corrections even after restarting the app.
- **Reset Functionality** – Clear history with a single click.

## 🛠️ Prerequisites
Ensure you have the following installed on your system:
- **Python 3.x** ([Download Python](https://www.python.org/downloads/))
- **pip** (comes pre-installed with Python)

Install required dependencies using:
```bash
pip install tkinter pyspellchecker
```

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Spell-Checker-App.git
   cd Spell-Checker-App
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python spell_checker.py
   ```

## 📌 How It Works
1. **Enter a word** in the input box and press **Enter** or click **Check Spelling**.
2. The program suggests the correct spelling if the word is incorrect.
3. **History Section** displays past corrections stored in an SQLite database.
4. Click **Reset History** to delete all records from the database.

## 📂 Project Structure
```
Spell-Checker-App/
│── spell_checker.py  # Main Python script
│── requirements.txt   # Dependencies list
│── README.md          # Project documentation
│── .gitignore         # Ignore unnecessary files (e.g., database file)
│── spell_checker.db   # SQLite database (generated at runtime)
```

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
