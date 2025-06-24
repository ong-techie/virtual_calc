# Virtual Calculator 🧮

A Python-based interactive calculator in a Jupyter notebook (`.ipynb`), featuring basic and extended mathematical operations with a clean, cell-by-cell interface.

## 🚀 Project Overview

This notebook guides users through:

- Basic arithmetic operations (addition, subtraction, multiplication, division, modulus)
- Extended functions such as exponentiation, square root, and possibly more  
- Handling and evaluating expressions interactively within Jupyter cells
- Clean demonstration using Markdown and code cells

## 📋 Features

- ✅ Addition, subtraction, multiplication, division  
- ✅ Exponentiation(via `**` )  , Modulus  
- ✅ Interactive expression input  
- ✅ Step-by-step usage showcased in notebook format

*(Optional: Note any additional functions you’ve added—e.g., `%`, trig, factorals, keyboard support.)*

## 🛠️ Getting Started

 **Clone the repo**
   
   git clone https://github.com/ong-techie/virtual_calc.git
   cd virtual_calc
  

  
🛠️ Install Dependencies
  It is strongly recommended to use a virtual environment to isolate dependencies and avoid version conflicts.

✅ Recommended Setup
  Python Version: 3.11.9
  (Note: Python 3.12+ is not supported by mediapipe as of now)
  mediapipe: 0.10.21
  opencv-python (cv2): 4.11

📦 Setup Instructions
  1. Create and activate virtual environment
  python3.11 -m venv venv
  # For Windows
  venv\Scripts\activate
  # For macOS/Linux
  source venv/bin/activate
  2. Upgrade pip
  pip install --upgrade pip
  3. Install dependencies
  pip install mediapipe==0.10.21 opencv-python==4.11
   
🧩 Future Enhancements
  🔭 Add scientific functions (log, sin, cos, etc.)
  🧠 Include error handling (invalid input, division by zero)
  🎨 Improve interface with widgets (e.g., ipywidgets)
