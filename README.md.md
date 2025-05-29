# Smartphone Battery Life Estimator 📱🔋

This machine learning project predicts the estimated battery life (in hours) of a smartphone based on user behavior such as screen-on time, app usage, brightness, and network activity.

## 🔍 Problem Statement
Smartphone users often wonder how long their battery will last based on their current usage. This model provides an estimate based on real-world usage patterns.

## 📂 Dataset Features
- `screen_on_time` (in hours)
- `app_usage` (total number of app launches)
- `brightness_level` (0 to 100)
- `network_usage` (MB used during session)
- `battery_life` (target, in hours)

## 🧠 Model Used
Linear Regression (can be swapped for XGBoost, Random Forest, etc.)

## 📈 Performance
Evaluated using R² Score and Mean Absolute Error.

## 🛠️ How to Run
1. Clone the repo
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Run the script:
    ```
    python battery_life_estimator.py
    ```

## 🤖 Skills Highlighted
- Data preprocessing
- Feature engineering
- Regression modeling
- Model evaluation

## 📌 Author
Ramani – M.E CSE, Sathyabama Institute of Science and Technology
