## 🧮 Virtual Calculator
A Python-based interactive virtual calculator that uses computer vision (via MediaPipe and OpenCV) for hand gesture recognition along with a Jupyter notebook interface for expression evaluation.

## 🚀 Overview
This project showcases:
Real-time gesture-based virtual calculator using webcam input.
Basic arithmetic operations with hand gestures (addition, subtraction, etc.).
Extended mathematical functionality like exponentiation, modulus, square root.
Optional notebook-based interface for step-by-step calculation demonstration.

## 📋 Features
✅ Real-time hand gesture recognition for digits and operations.
✅ Clean and intuitive calculator display.
✅ Addition, subtraction, multiplication, division.
✅ Exponentiation (via ^ or **) and modulus (%).
✅ Interactive mouse + gesture support.
✅ Error feedback on invalid expressions (e.g., division by zero).
✅ Equation editing via gestures (delete, clear).


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
  🧠 Enhance expression error handling and correction
  🎨 UI improvements (rounded buttons, dark mode)
  👋 Add support for multi-hand input or gestures for functions like square root
