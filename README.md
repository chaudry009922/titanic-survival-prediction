
Titanic Survival Prediction

This project uses machine learning to predict whether a passenger survived the Titanic shipwreck based on features like age, sex, class, and more.

Project Overview

- Goal: Predict survival using classification algorithms
- Dataset: Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic) or [DataScienceDojo GitHub](https://github.com/datasciencedojo/datasets)
- Tech Stack: Python, pandas, scikit-learn, seaborn, matplotlib

Features

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering
- Multiple ML models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Model evaluation using accuracy, precision, recall, and F1-score
- Visualizations (e.g., survival by gender)

## 📊 Sample Visualization

![Survival by Gender](sample_output.png) <!-- You can add this if you export a plot -->

Files Included

- Titanic_Project.ipynb`: Main notebook
- requirements.txt`: Required Python packages
- README.md`: This file

How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload `Titanic_Project.ipynb`
3. Run all cells step-by-step

Or clone and run locally:
```bash
pip install -r requirements.txt
jupyter notebook Titanic_Project.ipynb
```

Model Performance (Example Output)

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | ~82%    |
| Decision Tree       | ~79%    |
| Random Forest       | ~84%    |

Learnings

- Handling missing data and categorical encoding
- Choosing and evaluating different ML models
- Importance of feature selection
- Tradeoffs between precision and recall

Author

Made with ❤️ by a machine learning enthusiast from Pakistan.
