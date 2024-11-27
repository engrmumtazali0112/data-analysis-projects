# Titanic-Survival-Prediction

### 🔹 Titanic Dataset Analysis
- **Description:** Analyze the Titanic dataset to predict passenger survival outcomes based on various features.
- **Objective:** Explore relationships between variables such as survival rate, gender, class, fare, and age. Build a machine learning model (Logistic Regression) to predict survival outcomes.
- **Dataset:** [Titanic Dataset from Kaggle](https://www.kaggle.com/c/titanic/data)
- **Key Techniques:** Data preprocessing (missing value imputation, categorical encoding), exploratory data analysis (EDA), logistic regression model, data visualization (heatmaps, bar plots, countplots).

---

## 🚀 Project Overview
This project aims to predict survival rates of Titanic passengers using machine learning and data analysis. The key features explored include gender, passenger class, fare, and age. The project involves the following major components:
- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA) using visualizations.
- Building and evaluating a Logistic Regression model to predict survival outcomes.
- Insights on how various factors (gender, class, fare) influence survival probabilities.

## 🛠 Methodology
1. **Data Preprocessing**:
   - Handled missing values by imputing the `Age` column with the median and the `Embarked` column with the most frequent value.
   - Encoded categorical variables (`Sex`, `Embarked`) for use in machine learning models.
   
2. **Exploratory Data Analysis (EDA)**:
   - Conducted EDA using visualizations like countplots, bar plots, and heatmaps to explore relationships between features and survival rates.

3. **Machine Learning Model**:
   - Built a Logistic Regression model to predict survival based on passenger features.
   - Evaluated the model's performance using accuracy metrics and adjusted for feature scaling.

4. **Visual Outputs**:
   - Generated key visualizations to uncover trends and relationships in the dataset.

---

## 📊 Visual Outputs

1. **Survival Distribution**  
   ![Survival Distribution](https://github.com/user-attachments/assets/1435d857-8790-4f48-a83c-449ae71d9b53)  
   _Countplot showing the distribution of survival vs. non-survival._

2. **Correlation Heatmap**  
   ![Correlation Heatmap](https://github.com/user-attachments/assets/939b45fd-3ded-4405-8b7d-de2d40c8959d)  
   _Heatmap showing correlations between features and survival._

  
3. **Survival by Gender**  
   ![Survival by Gender](https://github.com/user-attachments/assets/856e04e2-d6d9-4f6a-aa0a-5680294ed506)  
   _Barplot comparing survival rates between male and female passengers._

4. **Survival by Passenger Class**  
   ![Survival by Class](https://github.com/user-attachments/assets/505b8aa0-f300-4334-81fc-593a54469f3c)  
   _Barplot showing survival rates across different passenger classes._
---
## 🔗 References
[Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data)

## 📈 Key Techniques
- **Data Preprocessing**: Handling missing values and encoding categorical variables.
- **Exploratory Data Analysis (EDA)**: Visualizing survival trends across features like gender, class, and fare.
- **Machine Learning**: Logistic Regression model, accuracy evaluation, and performance improvement.
- **Visualization Tools**: Matplotlib, Seaborn for creating visualizations like heatmaps and bar plots.

---

## 💻 Installation

To run this project on your local machine, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your_username/Titanic-Survival-Prediction.git
Navigate to the project directory:
 ```
 ```
cd Titanic-Survival-Prediction
Install the required dependencies:
 ```
 ```
pip install -r requirements.txt
Run the analysis script:
 ```

python titanic_analysis.py
🧑‍💻 Requirements
Python 3.x
Pandas
Matplotlib
Seaborn
Scikit-learn
🤝 Contributing
Feel free to fork the repository and submit issues or pull requests. Contributions are welcome!
