# Telugu Recipe App

🦋 Welcome to the Telugu Recipe App!  
This is a simple Streamlit app to search Telugu recipe text files by keyword.

---

## Features

- Loads recipes stored as UTF-8 text files from the `data` folder.  
- Search recipes by keywords (e.g., "biryani", "Chicken 65", "Fruit Custard").  
- Displays matched recipe content in the app UI.  
- Bilingual support with Telugu subheader.  

---

## How to Run Locally

1. Clone or download this repository.  
2. Create and activate a Python virtual environment:
    ```bash
    python -m venv venv
    # Windows PowerShell:
    .\venv\Scripts\Activate.ps1
    # Or Windows CMD:
    .\venv\Scripts\activate.bat
    ```
3. Install dependencies:
    ```bash
    pip install streamlit
    ```
4. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```
5. Open the URL shown in the console (usually http://localhost:8501) in your browser.

---

## Folder Structure

recipe-telugu/

├── app.py

├── data/

│ ├── biryani.txt

│ ├── chicken_65.txt

│ └── ... other recipe text files ...

├── requirements.txt

└── README.md


---

## Usage

- Type a keyword (e.g., `biryani`, `Mutter Rice`) in the input box.  
- The app searches for the keyword in the file names and file contents.  
- Matches are displayed with recipe text.

---

## Notes

- Recipe text files must be UTF-8 encoded `.txt` files placed inside the `data` folder.  
- This is a simple text-based search app without AI or translation features yet.

---
