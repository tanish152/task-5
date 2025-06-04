# task-5
 # 🩺 Heart Disease Prediction using Decision Tree and Random Forest
This project focuses on predicting the presence of heart disease using two powerful machine learning algorithms: Decision Tree and Random Forest. The dataset used is heart.csv, which contains various medical attributes such as age, cholesterol, chest pain type, etc.
# 
📊 Project Workflow
Load and prepare the dataset.

Train a Decision Tree Classifier and visualize it.

Control overfitting using tree depth.

Train a Random Forest Classifier and compare its accuracy.

Visualize feature importances.

Evaluate models using cross-validation.
#
🧰 Libraries Used
Make sure the following Python libraries are installed:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Explanation of libraries:

Library	Purpose
pandas	Data manipulation and loading CSV file
numpy	Numerical operations
matplotlib	Plotting graphs and visualizing trees
seaborn	Advanced visualizations (feature importance)
scikit-learn	Machine learning algorithms and evaluation tools
#
🗂️ Dataset
The dataset heart.csv must be present in the same directory. It includes columns like:

age

sex

cp (chest pain type)

chol (cholesterol)

thalach (maximum heart rate achieved)

target (0 = No heart disease, 1 = Heart disease)
#
🚀 How to Run the Code
Clone this repository:
git clone https://github.com/your-username/heart-disease-ml.git
cd heart-disease-ml


 
 # 📈 Output
Accuracy of both models

Visualization of Decision Tree

Feature importances from Random Forest

Cross-validation scores

Classification report with precision, recall, and F1-score
#
✅ Conclusion
Random Forest usually performs better than a single Decision Tree.

Controlling the depth of trees helps reduce overfitting.

Feature importance helps understand key indicators of heart disease.
