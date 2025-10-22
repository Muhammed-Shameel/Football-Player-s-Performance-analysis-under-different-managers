# ⚽ Football Player Analysis Project

This project analyzes football player performance data and provides tactical recommendations — including identifying the best managers for specific players and recommending players that best fit each manager’s tactical style.

---

## 🗂️ Project Structure

football-player-analysis/
│
├── data/ # Cleaned dataset (no copyrighted statistics data)
├── notebooks/ # Jupyter notebooks
├── src/ # Python source code (Flask app + ML models)
├── Screenshots/ # Output plots or summaries
├── static/ # Static files (images, CSS, JS)
├── templates/ # HTML templates for the web app
├── README.md # This file
└── requirements.txt # Python dependencies

---

## 🧩 Note on Source Code (`src.zip`)

Due to GitHub’s file size limitations, the complete source code (Flask application and machine learning scripts) is provided as a compressed file named **`src.zip`** in the repository.

To use it:
1. Download the `src.zip` file from this repository.  
2. Extract it inside the main project folder so that your structure looks like:
football-player-analysis/
├── data/
├── notebooks/
├── src/
├── templates/
├── static/
├── Screenshots/
└── requirements.txt

3. Then follow the installation and running steps below.

---

## 🚀 Features

- Player performance analysis  
- Tactical and positional recommendations  
- Manager-player compatibility scoring  
- Seasonal performance tracking  
- Player comparison tools  
- Copyright-compliant player images (auto-generated)  
- Physical attribute display (position, height, weight, BMI)  
- Year-specific data filtering  

---

## ⚙️ Installation

1. **Install the required packages:**
```bash
pip install -r requirements.txt
Run the application:

cd src
python app.py
Access the app:
Open your browser and go to 👉 http://localhost:5000

📊 Data Sources
The analysis uses publicly available football player and match statistics from multiple leagues.
Data includes player info, manager records, and match-level performance indicators.
All images or copyrighted content have been removed or replaced with auto-generated placeholders.

🧱 Project Organization
data/ – Player, manager, and team data (cleaned and anonymized)

src/ – Flask web app and machine learning scripts (inside src.zip)

templates/ – HTML templates for the web interface

static/ – Static assets (CSS, JS, auto-generated player images)

notebooks/ – Jupyter notebooks (for data exploration and experiments)

Screenshots/ – Output visualizations and model performance results

👤 Player Information Displayed
Name (from player.xlsx)

Team name

Position (year-specific, from player_stat.csv)

Height, Weight, and BMI

Impact score (overall or year-specific)

Abilities: Passing, Shooting, Creativity, Dribbling, Defense

Auto-generated image with player’s name (no real photos used)

📆 Year-Specific Data
When a specific year is selected:

Displays the player’s year-specific position and ability scores

Keeps static attributes constant (height, weight, BMI)

Shows impact score variations across seasons

🖼️ Player Images (Copyright-Safe)
All player images are auto-generated with a white background and the player’s name displayed at the center.
This ensures full compliance with copyright and allows the project to be publicly shared.
Images are automatically created when requested and saved under:

static/images/
▶️ Running the Application
Navigate to the src directory

Run:
python app.py
Open your browser and go to:
👉 http://localhost:5000

The app automatically loads player, manager, and team data from the data/ folder and uses trained machine learning models from the src/ directory.

🧠 Technologies Used
Languages & Libraries: Python, Pandas, NumPy, Scikit-learn, Flask, Matplotlib, Seaborn

Machine Learning: Factor Analysis, Regression Models, Compatibility Scoring

Visualization: Matplotlib, Seaborn, HTML Dashboards

⚖️ Data Ethics
All copyrighted material (images or proprietary datasets) has been excluded.
This repository only includes open-source, generated, or anonymized data and code for educational and research purposes.

👨‍💻 Author
Muhammed Shameel
📧 muhammedshameel3009@gmail.com
