# Mood Tracker

**A simple Python project for tracking daily moods and quick notes.**

##  Overview

Mood Tracker is a user-friendly Python program that helps log daily moods along with short notes. It saves each entry in a lightweight JSON file for easy storage and reuse. Users can search and view moods by date or by mood type, making it simple to track emotional trends over time. The project is designed to be clear, modular, and easy to maintain.---

## ⚙️ Approach & Design

- Developed as a simple command-line application for straightforward interaction.
- Organized code into clean, reusable functions and helper utilities.
- Includes input validation to ensure correct date formats and mood consistency.
- Uses a JSON file for persistent data storage, which is easy to read and test.
- Follows the **DRY principle** (Don’t Repeat Yourself) to keep the code efficient.


## Key Files & Folders

| **`Mood_Tracker.ipynb`** | Contains all Python code, structured into clear Colab notebook cells: setup, helpers, logging, viewing, and the main menu. |
| **`mood_data.json`** | Stores all logged moods and notes in a simple JSON format — easy to open, edit, and verify. |
| **`MT presentation.pptx`** | Short presentation explaining the project overview, design, structure, and steps to run and test. |


##  How to Run & Test

1. **Open the notebook:** Launch `Mood_Tracker.ipynb` in [Google Colab]([https://colab.research.google.com/](https://colab.research.google.com/drive/1oOGiif8ud2bXNfRfn59mlfAuuk9jNCdV?usp=sharing)) or Jupyter Notebook.
2. 
3. **Run all cells:** Execute each cell in order to load all required functions and helpers.
   
4. **Use the interactive menu:**
   - **1:** Log a new mood
   - **2:** View moods by date or mood type
   - **3:** Exit the tracker
5. **Verify data:** Check `mood_data.json` to confirm moods are saved and updated correctly.
6. **Test filtering:** Add a few sample moods and try viewing by date or mood type to ensure everything works as expected.

## Seed Data

The `mood_data(3).json` file includes a few pre-logged sample moods to demonstrate the view and filter features immediately.


## 🎓 Presentation

Refer to `MT presentation.pptx` for a concise overview of the project’s approach, structure, and usage steps.


##  License

Open-source for demonstration and study purposes. Feel free to adapt or extend!


**Created by Anjali Solanki**
