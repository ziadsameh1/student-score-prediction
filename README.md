# 🎯 Student Score Prediction using Machine Learning

This project demonstrates how to use a simple Linear Regression model to predict students' exam scores based on study-related features such as hours studied. It's an ideal beginner-level project to understand the fundamentals of supervised machine learning using Python.

## 📁 Dataset

- **Source**: https://www.kaggle.com/datasets/lainguyn123/student-performance-factors
- **File**: StudentPerformanceFactors.csv
- **Features used**:
  - Hours_Studied (input)
  - Exam_Score (target/label)

## 🧠 Objective

To build a regression model that accurately predicts a student’s exam score based on the number of hours they studied.

## ⚙️ Tools & Libraries

- Python
- Google Colab / VS Code
- pandas
- matplotlib
- scikit-learn (Linear Regression)

## 📊 Workflow

1. Load and explore the dataset
2. Check for missing values
3. Select feature (Hours_Studied) and target (Exam_Score)
4. Split dataset into training and test sets
5. Train a Linear Regression model
6. Evaluate performance using Mean Squared Error and R² score
7. Visualize predictions vs actual scores

## 🚀 Results

- ✅ Model trained successfully
- 📉 Mean Squared Error: *(shown in output)*
- 📈 R² Score: *(shown in output)*
- 📊 Scatter plot showing predicted vs actual scores

## 📌 Sample Code

python
model = LinearRegression()
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
  
📸 Output Visualization
The chart below represents actual exam scores vs predicted scores based on study hours.


📚 Learnings
Basics of Linear Regression

Data preprocessing & cleaning

Train/test split

Performance evaluation

Real-world data prediction

🏁 Conclusion
This project proves that even a simple linear regression model can give meaningful predictions when working with clean and relevant features like study hours. A great first step into the world of machine learning.

