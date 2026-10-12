# Iris Flower Classification using ML 🌸

##  Project Overview

Iris Flower Classification is a Machine Learning project developed using **Python and Jupyter Notebook** to classify Iris flowers into their respective species based on their physical measurements.

The project involves loading and preprocessing the dataset, performing exploratory data analysis, training multiple classification algorithms, evaluating their performance, and selecting a suitable model for prediction.

The trained model is saved as a pickle file and integrated into a **Streamlit web application**, allowing users to enter flower measurements and obtain a predicted species.

##  Objectives

* Understand and preprocess a dataset for Machine Learning.
* Explore the relationships between flower measurements using data visualization.
* Train and compare different classification algorithms.
* Evaluate model performance and select a suitable classifier.
* Save the trained model and scaler for reuse.
* Build an interactive interface for flower species prediction.

##  Dataset

The project uses the Iris flower dataset, which contains measurements of Iris flowers belonging to three species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

The input features used for classification are:

| Feature      | Description                        |
| ------------ | ---------------------------------- |
| Sepal Length | Length of the sepal in centimeters |
| Sepal Width  | Width of the sepal in centimeters  |
| Petal Length | Length of the petal in centimeters |
| Petal Width  | Width of the petal in centimeters  |

The dataset is loaded into a Pandas DataFrame for preprocessing and analysis.

##  Technologies Used

* **Python** – Programming language
* **Jupyter Notebook** – Data analysis, experimentation, and model training
* **Pandas and NumPy** – Data manipulation and numerical operations
* **Matplotlib and Seaborn** – Data visualization
* **SciPy** – Statistical analysis
* **Scikit-learn** – Data preprocessing and Machine Learning
* **Pickle** – Saving and loading the trained model and scaler
* **Streamlit** – Interactive prediction interface

##  Machine Learning Algorithms

Four classification algorithms are implemented and evaluated:

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Support Vector Classifier (SVC)**
4. **Naive Bayes**

The notebook compares their performance, with Logistic Regression selected as the model for prediction.

##  Project Workflow

1. Load the Iris dataset.
2. Explore the dataset and understand its statistical properties.
3. Check for missing values and duplicate records.
4. Perform data preprocessing and remove unnecessary columns.
5. Visualize the relationships between features.
6. Encode the target labels and scale the input features.
7. Train the four classification models.
8. Evaluate and compare model performance.
9. Save the selected model and scaler as pickle files.
10. Integrate the saved artifacts into a Streamlit application.
11. Accept flower measurements and display the predicted class.

##  Project Structure

```text
Iris-Classification/
│
├── iris_classification_main.ipynb
├── streamlitapi.py
├── model.pkl
├── scaler.pkl
├── requirements.txt
├── Dataset/
│   └── Iris.csv
└── README.md
```

*Note: The dataset folder should contain `Iris.csv` at the path expected by the notebook. Adjust the structure above if your actual repository differs.*

##  Installation and Execution

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd Iris-Classification
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
pip install streamlit
```

### 3. Run the Jupyter Notebook

Open the notebook in Jupyter Notebook or JupyterLab and execute the cells to explore the dataset, train the models, and evaluate their performance.

### 4. Launch the Streamlit application

Ensure that `model.pkl` and `scaler.pkl` are available in the working directory, then execute:

```bash
streamlit run streamlitapi.py
```

The application opens in a browser, where users can enter the four flower measurements and click **Predict** to obtain a classification result.

##  Key Features

* Exploratory data analysis and visualization
* Data preprocessing and feature scaling
* Comparison of four Machine Learning algorithms
* Reusable model and scaler files
* Interactive prediction interface
* Real-time predictions based on user-provided measurements

##  Future Enhancements

* Improve input validation and error handling.
* Display model accuracy and evaluation metrics in the application.
* Add interactive visualizations of the flower measurements.
* Deploy the application to a cloud hosting platform.
* Develop a more advanced interface for exploring predictions.

##  Learning Outcomes

This project demonstrates practical experience with data preprocessing, exploratory data analysis, supervised Machine Learning, classification model evaluation, model serialization, and deployment through Streamlit.

##  Project Type

**Machine Learning | Data Science | Classification | Python**

##  License

This project is intended for educational and learning purposes. Add an appropriate license if you plan to distribute it publicly.
