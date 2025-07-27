Math Solver Web App
===================

Description:
------------
This is a web-based Math Solver built using Flask (Python) for the backend and HTML/CSS/JavaScript (Chart.js) for the frontend. It allows users to:

- Calculate logarithmic and exponential values of real numbers.
- Plot custom mathematical functions like "x^2 + 3", "sin(x)", "log(x)" etc.
- View graphs with styled axes and gridlines.

Folder Structure:
-----------------
project/
│
├── app.py                  # Flask backend
├── templates/
│   └── index.html          # Frontend HTML
└── static/
    └── style.css           # Styling
    └── script.js           # Interactions


Usage Instructions:
-------------------
1. Ensure Python and Flask are installed.
2. Place all files in the correct folder structure (above).
3. Run the Flask app:
       python app.py
4. Open a browser and go to:
       http://127.0.0.1:5000

Features:
---------
- Logarithmic and exponential calculator.
- User-defined function plotter with Chart.js.
- Dark theme with Orbitron font.
- Zoomed graph axes from -10 to 10 with clear ticks.

Function Syntax:
----------------
- Use standard math syntax: `x^2`, `x^3 + 2*x`, `sin(x)`, `log(x)`, `exp(x)`, `sqrt(x)`, etc.
- Use `e` and `pi` for Euler's number and π. (will be added soon)

Example Inputs:
---------------
Function input:   x^2 + 2*x + 1
Log input:        2.71828 (to get ln(e)=1)
Exponential:      1 (to get e^1 = e)

Requirements:
-------------
- Flask
- SymPy
- Chart.js (via CDN, already included in HTML)

Notes:
------
- If CSS doesn't load, make sure your folder has a `static/` directory and that Flask logs show the CSS file being served.
- Clear browser cache (Ctrl+F5) if you see stale styling.

Author:
-------
This app was developed as a math utility for visualizing functions and calculating values dynamically via a web interface.
