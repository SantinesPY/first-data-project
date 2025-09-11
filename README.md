# 🚀 first-data-project

**etl-bootstrap** is a beginner-friendly ETL (Extract, Transform, Load) project focused on cleaning and normalizing supplier names from CSV or Excel files using Python and a graphical user interface (GUI).  
It was built as a first step into data engineering and ETL development.

---

## 📌 Features

- 📂 Load CSV or Excel input files
- ✅ Validate structure and required columns
- 🧠 Normalize supplier names using fuzzy logic (Levenshtein distance)
- 🔍 Manual review of matches (optional)
- 💾 Export cleaned file, categorized by match quality
- 🖥️ Simple GUI for non-technical users

---

## 🛠 Tech Stack

- **Python 3.x**
- `pandas`
- `fuzzywuzzy` + `python-Levenshtein`
- `customtkinter` *(or `tkinter` / `PyQt` depending on version)*
- `openpyxl` *(for Excel support)*

---

## 📁 Project Structure

first-data-project/
│
├── main.py # GUI entry point
├── normalizer.py # Supplier matching logic
├── requirements.txt # Python dependencies
├── SampleSuperstore.csv # Sample input file
├── ETL_PROCESS.ipynb # Optional notebook version
├── .gitignore
└── README.md


---

## ▶️ How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/tu-usuario/first-data-project.git
   cd first-data-project

   📬 Contact

Made with ❤️ by Eduardo Macias
📧 lic.eduardom89@gmail.com
