# 🎓 Saad-Python: Smart Orientation Assistant (2AC)

Welcome to the **Smart Orientation Assistant**! This tool is designed specifically for Moroccan students in the 2nd Year of Middle School (2AC). By entering your marks, the assistant calculates the best academic path for your future based on weighted coefficients.

## 🚀 Features
* **Precise Calculation:** Uses official 2AC coefficients for Physics, Math, SVT, and more.
* **Percentage Analysis:** Shows you exactly how well you fit into each branch.
* **Local Storage:** Automatically saves your results to `Orientation_Result.txt`.
* **User-Friendly GUI:** Built with Python's Tkinter for a smooth desktop experience.

---

## 🛠️ Installation & Execution

Follow these steps to set up the assistant on your Linux (Fedora/Ubuntu) or Windows machine.

### 1. Prerequisites
Ensure you have Python 3.10 or higher installed. If you are on **Fedora**, you may need to install the Tkinter interface:
`sudo dnf install python3-tkinter -y`

### 2. Clone the Repository
Download the project files to your local machine:
`git clone https://github.com/adnaneSaad/Saad-Python.git`
`cd Saad-Python`

### 3. Install the Library
Install the `saad_tools` package so the assistant can access the core utilities:
`pip install .`

### 4. Run the Assistant
Launch the application using the following command:
`python3 main.py`

---

## 📝 How to Use
1. Enter your marks (0-20) for each subject in the provided fields.
2. Click the **Submit** button.
3. A popup will appear showing your best orientation (e.g., Scientific Trunk, Arts & Humanities).
4. Check your project folder for `Orientation_Result.txt` to see a saved copy of your analysis.

---

## ⚖️ Disclaimer
*This project is for educational purposes only. Always consult with your school counselor before making final academic decisions.*
