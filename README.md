# Football-Player-s-Performance-analysis-under-different-managers
This project investigates how football managers influence player performances across top Premier League clubs — Manchester United, Chelsea, Arsenal, Tottenham, and Liverpool — between 2017 and 2025. The study focuses on understanding player development, tactical impact, and performance consistency under different managerial styles.
⚽ Football Performance and Tactical Analytics Using Factor Analysis
🎓 M.Sc. Data Science Capstone Project (2017–2025 Football Seasons)

This project explores how managerial tactics influence player performance in top Premier League clubs — including Manchester United, Chelsea, Arsenal, Liverpool, and Tottenham — between 2017 and 2025.
By combining statistical modeling, factor analysis, and tactical profiling, the project identifies latent skill dimensions such as attacking, defending, playmaking, passing, and dribbling, while linking these to managerial and tactical contexts.

📊 Project Overview

Traditional football analytics often rely on descriptive statistics like goals, assists, or passes.
This project moves beyond that by:

Extracting latent player abilities through Factor Analysis (FA).

Quantifying how managerial tactics (formations, tempo, pressing style, width, etc.) affect player performance.

Building a predictive framework that identifies the best tactical environments for players to thrive.

Providing interpretable outputs for scouts, analysts, and coaching staff.

⚙️ Methodology
1. Data Sources

Match-level player statistics from 2017–2025.

Tactical and managerial data (formations, tempo, pressing style, width, etc.).

Derived variables include:

Attacking Score, Defensive Score, Passing, Playmaking, Dribbling, Potential Score, and their Z-scores.

Tactical components like line height, tempo, build-up, and pressing intensity.

2. Data Preprocessing

Missing value handling, normalization, and encoding of categorical tactical variables.

Power transformation and Z-score standardization for model stability.

Dataset integration across player, manager, and team tables.

3. Exploratory Factor Analysis (EFA)

Extracted five main latent skill dimensions using FA.

Applied Varimax rotation for interpretability.

Validated factor structure through Confirmatory Factor Analysis (CFA).

4. Managerial & Tactical Analysis

Evaluated how tactical factors affect player impact under different managers (e.g., Solskjær, Mourinho, Tuchel, Conte).

Created tactical profiles using Multiple Correspondence Analysis (MCA) for categorical data.

Compared player adaptability under varying formations and tempos.

5. Visualization

Heatmaps of factor loadings and correlations.

Radar charts of player tactical fit.

Comparative visualizations between managers and tactical components.

🧠 Key Findings

Marcus Rashford achieved his highest performance (impact score: 54) in 2020 under Ole Gunnar Solskjær, with best tactical context emphasizing direct play and variable tempo.

Bruno Fernandes showed peak performance under Solskjær as well, dominated by defensive contribution and tactical stability.

Thomas Tuchel favored fast, high-pressing systems (2-4-2-1 formation), enhancing player creativity and passing synergy.

Antonio Conte emphasized a structured defensive shape (3-4-3 formation), boosting defensive scores but reducing creative freedom.

Jose Mourinho, across Manchester United and Tottenham, maintained low-block tactics, showing tactical consistency but moderate creativity indexes.

🔬 Tools & Technologies
Category	Tools / Libraries
Programming	Python (NumPy, Pandas, SciPy, Scikit-learn, Statsmodels)
Visualization	Matplotlib, Seaborn, Plotly
Statistical Methods	Exploratory & Confirmatory Factor Analysis, Multiple Correspondence Analysis
Data Management	Microsoft SQL Server
Development Environment	Jupyter Notebook, Visual Studio Code
🚀 Future Work

Integrate spatiotemporal tracking data for dynamic player positioning.

Expand dataset to include multiple leagues (La Liga, Serie A, Bundesliga) for cross-league tactical comparisons.

Apply deep learning models (e.g., autoencoders, graph neural networks) for automatic tactic recognition.

Build an interactive dashboard for scouts and analysts to explore player–manager fit in real-time.
