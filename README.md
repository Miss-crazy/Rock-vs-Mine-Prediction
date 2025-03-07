# Rock-vs-Mine-Prediction
This project focuses on classifying underwater objects as either rocks or mines based on sonar sensor data. The dataset consists of 60 numerical features representing different frequency responses. The goal was to build a machine learning model that can accurately differentiate between these objects.

Initially, I experimented with Logistic Regression, but later, I implemented a Random Forest Classifier, which improved accuracy significantly. The model was trained and evaluated using performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

<h2>Dataset Overview :</h2>
 The dataset contains sonar frequency readings for objects labeled as M (Mine) and R (Rock).
Each sample has 60 numerical features representing different sonar wave responses.
The target variable is binary:
M → Mine (1) ,
R → Rock (0) .

<h2>Technologies Used :</h2>
 Python 🐍 for implementation
Pandas & NumPy for data handling ,
Scikit-Learn for model building ,
Matplotlib & Seaborn for data visualization ,
Jupyter Notebook / Google Colab for experimentation .

<h2>Model Performance & Observations :</h2>
 I initially implemented Logistic Regression, which resulted in an accuracy of 71.4%. However, switching to a Random Forest Classifier significantly improved performance, achieving 81% accuracy.

<h2>Key Observations:</h2>
✔ Feature scaling (StandardScaler) improved model performance.
✔ Random Forest outperformed Logistic Regression, making better predictions on test data.
✔ The model never misclassified a mine (R) as a rock, achieving 82% recall for mines.
✔ Feature importance analysis could be done to remove unimportant features and optimize performance.

# Conclusion :
 This project successfully built a machine learning model that can classify underwater objects based on sonar readings. Random Forest proved to be the best-performing algorithm in this case, and with further improvements, it could be used in marine exploration, underwater navigation, and object detection systems.
