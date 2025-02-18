# Spell-Checker-with-sqlite3-database

The Smart Spell Checker with History is a Python-based GUI application built using Tkinter. It helps users check and correct spelling mistakes in real-time while maintaining a history of corrections using an SQLite database.

## 📌 Project Description

The **Spell-Checker-with-sqlite3-database** is a Python-based GUI application built using **Tkinter**. It helps users check and correct spelling mistakes in real-time while maintaining a history of corrections using an SQLite database. This project also works on **Jupyter Notebook** in **VS Code** with the `.ipynb` extension and requires a **Python kernel**. Additionally, it includes a **.venv** folder for virtual environment support.

## ✅ Features

- **Real-time Spell Checking** – Detects and corrects misspelled words using the `spellchecker` library.
- **History Tracking** – Stores previous spell checks in a database and displays them.
- **User-Friendly Interface** – Simple and intuitive GUI for easy interaction.
- **Persistent Storage** – Saves corrections even after restarting the app.
- **Reset Functionality** – Clear history with a single click.
- **Jupyter Notebook Compatibility** – Works with `.ipynb` files in **VS Code**.
- **Python Kernel Requirement** – Requires a Python kernel for execution in Jupyter Notebook.
- **Virtual Environment Support** – Includes a `.venv` folder for dependency management.

## 🛠️ Prerequisites

Ensure you have the following installed on your system:

- **Python 3.x** ([Download Python](https://www.python.org/downloads/))
- **pip** (comes pre-installed with Python)
- **Jupyter Notebook** (for `.ipynb` support)
- **Python Kernel** (for running in Jupyter Notebook)
- **Virtual Environment** (for isolated package management)

Install required dependencies using:

```bash
pip install tkinter pyspellchecker jupyter
```

If you need to install the Jupyter kernel, run:

```bash
pip install ipykernel
python -m ipykernel install --user
```

If using the virtual environment, activate it and install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate  # On macOS/Linux
.venv\Scripts\activate     # On Windows
pip install -r requirements.txt
```

## 🚀 How to Run the Project

### For Python Script (.py)

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Spell-Checker-App.git
   cd Spell-Checker-App
   ```
2. Activate the virtual environment (if using `.venv`):
   ```bash
   source .venv/bin/activate  # On macOS/Linux
   .venv\Scripts\activate     # On Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python spell_checker.py
   ```

### For Jupyter Notebook (.ipynb in VS Code)

1. Open **VS Code**.
2. Install the **Python extension** from the Extensions Marketplace.
3. Open the Jupyter Notebook file (`spell_checker.ipynb`).
4. Select the Python kernel (if not selected automatically).
5. Activate the virtual environment if using `.venv`.
6. Run the notebook cells to execute the spell checker.

## 📂 Project Structure

```
Spell-Checker-App/
│── spell_checker.py  # Main Python script
│── spell_checker.ipynb  # Jupyter Notebook version
│── README.md          # Project documentation
│── .gitignore         # Ignore unnecessary files (e.g., database file, .venv)
│── spell_checker.db   # SQLite database (generated at runtime)
│── .venv/             # Virtual environment folder
```

## 🐜 How It Works

1. **Enter a word** in the input box and press **Enter** or click **Check Spelling**.
2. The program suggests the correct spelling if the word is incorrect.
3. **History Section** displays past corrections stored in an SQLite database.
4. Click **Reset History** to delete all records from the database.
5. In **Jupyter Notebook**, execute the notebook cells to interact with the spell checker.

## 🐝 License

This project is open-source and available under the [MIT License](LICENSE).

