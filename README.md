# 🏆 UEFA Champions League Predictor 2026

## ⚽ Project Overview
This project uses **Machine Learning (Random Forest)** to predict the winner of the 2025/2026 UEFA Champions League. 
By analyzing key football metrics such as **Current Form, Squad Value, UEFA Coefficients, and Manager Experience**, the model estimates the winning probability for the top 32 European teams.

The goal was to move beyond subjective debates and use data to determine the true favorites.

## 🧠 How It Works
The model is trained on a **synthetic historical dataset** representing 20 years of UCL winners and losers. It learns which features (Defense, Attack, Money, Experience) traditionally lead to lifting the trophy.
It then applies this logic to the real-world 2026 dataset (`data.csv`).

### 🔑 Key Features Analyzed:
*   **Current Form:** Weighted performance in the last 15 games (Heavily weighted).
*   **Squad Value:** Market value of the team in Millions €.
*   **UEFA Coefficient:** Official 5-year ranking points.
*   **Defense/Attack Ratings:** Performance indices.
*   **Experience:** Number of previous UCL titles.

## 📊 Visualizations
The project includes interactive **Plotly** visualizations:
*   **Radar Charts:** To compare top rivals (e.g., FC Barcelona vs. Real Madrid vs. Man City).
*   **Feature Importance:** Exploring what matters most to win.
*   **Prediction Bar Chart:** Final probabilities for the top contenders.

## 🚀 How to Run
1.  Clone this repository:
    ```bash
    git clone https://github.com/YOUR_USERNAME/Champions_League_Prediction.git
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
4.  Open `Champions_League_Prediction.ipynb` and run all cells!

## 🏆 Current Prediction (Feb 2026)
According to the model (v3.0 Logical Form Update):
1.  🥇 **FC Barcelona** (Top Favorite)
2.  🥈 **Arsenal** (Dominant Form)
3.  🥉 **Manchester City**

*Note: Real Madrid currently ranks outside the Top 5 due to recent poor form.*

---
*Created by a Data Science enthusiast & Football fan.* 🔵🔴
