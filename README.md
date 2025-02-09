# 🌲 Algerian Forest Fire Prediction 🔥

## 📌 Project Overview
Forest fires pose a significant threat to ecosystems and human life. This project focuses on predicting forest fires in Algeria using multiple regression techniques to analyze environmental factors affecting fire intensity.

## 🚀 Features
- Implemented **Linear Regression, Lasso, Ridge Regression, and ElasticNet** models.
- Evaluated models based on **Mean Squared Error (MSE) and R² Score**.
- Achieved high accuracy in predicting fire intensity.
- Utilized **Algerian Forest Fire Dataset** for training and testing.

## 📊 Results
| Model           | MSE  | R² Score |
|----------------|------|----------|
| **Linear Regression** | 1.0276 | 0.9704 |
| **Lasso Regression**  | 2.1640 | 0.9377 |
| **Ridge Regression**  | 1.0690 | 0.9692 |
| **ElasticNet**        | 4.9449 | 0.8575 |

## 🔧 Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Machine Learning Models (Linear, Ridge, Lasso, ElasticNet Regression)**

## 📂 Dataset
The **Algerian Forest Fire Dataset** was used, which contains meteorological and environmental attributes like:
- Temperature
- Relative Humidity
- Wind Speed
- Rainfall
- Fine Fuel Moisture Code (FFMC)
- Duff Moisture Code (DMC)
- Initial Spread Index (ISI)
- Fire Weather Index (FWI)

## 📖 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Algerian-Forest-Fire-Prediction.git
2. Navigate to the project directory:
   cd Algerian-Forest-Fire-Prediction
3. Install dependencies:
   pip install -r requirements.txt
4. Run the Jupyter Notebook or Python script:

## Notebook
Open Algerian_Forest_Fire_Prediction.ipynb and execute the cells.
📈 **Model Evaluation**
**Mean Squared Error (MSE)**: Measures how close predictions are to actual values.
**R² Score**: Indicates the goodness of fit.
## 🏆 Key Takeaways
Linear Regression and Ridge Regression provided the most accurate predictions.
Lasso Regression penalized features, reducing overfitting but slightly lowering accuracy.
ElasticNet performed the worst, likely due to hyperparameter selection.
## 💡 Future Improvements
Optimize hyperparameters using **GridSearchCV**.
Implement **Random Forest Regression** and Neural Networks for better performance.
Deploy the model as a web application using **Flask or FastAPI**.
## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributions
Feel free to contribute by:
  Forking the repo
  Creating a pull request

**Reporting issues**
🔗 Connect With Me
LinkedIn: https://www.linkedin.com/in/naveen-narasimhappa/
GitHub: https://github.com/naveennn2924