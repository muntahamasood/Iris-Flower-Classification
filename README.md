# Iris-Flower-Classification
Machine Learning project for classifying Iris flower species using Python.
Iris Flower Classification 🌸
A beginner-friendly Machine Learning project that predicts the species
of an Iris flower using four flower measurements and a Random Forest
Classifier.
📌 Project Overview
The objective of this project is to build a classification model that
identifies an Iris flower as one of three species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica
The model uses sepal length, sepal width, petal length, and petal width
to make its prediction.
📊 Dataset
This project uses the Iris dataset (Iris.csv).

The original dataset contains 150 records and 6 columns. The Id column
was removed because it is not useful for classification. Three duplicate
records were also removed, leaving 147 records in the cleaned
dataset.
Features
  Feature         Description
  SepalLengthCm   Sepal length in centimeters
SepalWidthCm    Sepal width in centimeters
PetalLengthCm   Petal length in centimeters
PetalWidthCm    Petal width in centimeters

Target variable: Species
🛠️ Tools and Technologies
- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
⚙️ Project Workflow
1. Load the dataset using Pandas.
2. Explore the data by checking its structure, summary statistics,
   species distribution, missing values, and duplicate records.
3. Clean the data by removing the unnecessary Id column and
   duplicate rows, and checking missing values.
4. Select features and target: use the four flower measurements as
   input features and Species as the target.
5. Split the dataset into training and testing sets using an 80:20
   split and stratification.
6. Scale the features using StandardScaler, fitted on the
   training data and applied to both sets.
7. Train the model using a RandomForestClassifier with 100
   estimators.
8. Evaluate the model using accuracy and a classification report.
🤖 Machine Learning Model
Algorithm: Random Forest Classifier

Configuration: - n_estimators = 100 - random_state = 42
📈 Results
  Metric                       Result
  Cleaned dataset size       147 rows
Training samples                117
Testing samples                  30
Accuracy                 96.67%

The model correctly classified 29 out of 30 test samples.
Classification Report
  Species                  Precision     Recall   F1-score   Support
  Iris-setosa                   1.00       1.00       1.00        10
Iris-versicolor               1.00       0.90       0.95        10
Iris-virginica                0.91       1.00       0.95        10
Macro average         0.97   0.97   0.97    30
Weighted average      0.97   0.97   0.97    30
📁 Repository Structure
Iris-Flower-Classification/
├── Iris.csv
├── Iris_Flower_Classification.ipynb
└── README.md
If your notebook has a different filename, update the filename above to
match the file uploaded to your repository.
▶️ How to Run the Project
1. Clone or download this repository.
2. Open Iris_Flower_Classification.ipynb in Jupyter Notebook or
   Google Colab.
3. Make sure Iris.csv is available in the notebook's working
   directory, or update the dataset path.
4. Run the notebook cells from top to bottom.
Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn
💡 Conclusion
The Random Forest Classifier achieved 96.67% accuracy on the test
set. This project demonstrates a basic machine learning classification
workflow, including data exploration, cleaning, feature preparation,
model training, and evaluation.
👩‍💻 Author
Muntaha Masood

This project was completed as part of a Machine Learning internship
task.
