# Machine Learning & Data Analysis

A collection of Machine Learning projects, experiments, and practical implementations covering data analysis, preprocessing, regression, classification, clustering, dimensionality reduction, ensemble learning, and hyperparameter optimization using Python.

This repository documents my journey of learning and implementing Machine Learning concepts through hands-on projects and experiments.

## Repository Contents

### 1. Ford Car Price Prediction

**Notebook:** `fordcar.ipynb`  
**Dataset:** `ford.csv`

A regression project focused on predicting the prices of used Ford cars based on different vehicle characteristics.

**Key concepts covered:**
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib and Seaborn
- Categorical feature encoding (One-Hot Encoding and Label Encoding)
- Feature scaling using StandardScaler
- Train-test splitting
- Linear Regression
- Model evaluation using R² and Adjusted R² scores

**Dataset:** 17,966 records with 9 features.

### 2. Medical Insurance Cost Prediction

**Notebook:** `insurance.ipynb`  
**Dataset:** `insurance.csv`

A regression project that explores the relationship between personal characteristics and medical insurance charges.

**Key concepts covered:**
- Exploratory Data Analysis (EDA)
- Data cleaning and duplicate removal
- Handling categorical variables
- One-Hot Encoding
- Feature engineering and BMI categorization
- Feature selection using Pearson Correlation and Chi-Square tests
- Feature scaling using StandardScaler
- Linear Regression
- Model evaluation using R² and Adjusted R² scores

**Dataset:** 1,338 records with 7 original features.

### 3. Titanic Survival Prediction

**Notebook:** `titanic.ipynb`

A classification project that explores the Titanic passenger dataset and predicts passenger survival using multiple machine learning algorithms.

**Algorithms implemented:**
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Decision Tree Classifier

**Key concepts covered:**
- Data cleaning and preprocessing
- Handling missing values
- Categorical feature encoding
- Train-test splitting
- Feature scaling
- Model evaluation and comparison
- Confusion Matrix
- Accuracy, Precision, Recall, and F1-score

**Recorded result:** Logistic Regression achieved approximately 80.34% accuracy on the test dataset.

### 4. Ensemble Learning

**Notebook:** `ensambleLearning.ipynb`

An implementation-based exploration of Ensemble Learning techniques using the Iris dataset.

**Algorithms implemented:**
- Stacking Classifier
- Random Forest Classifier
- AdaBoost
- Gradient Boosting
- XGBoost

**Key concepts covered:**
- Ensemble Learning fundamentals
- Base learners and meta-learners
- Stacking
- Bagging-based learning
- Boosting techniques
- Model evaluation using accuracy

### 5. Hyperparameter Tuning – GridSearchCV

**Notebook:** `GridSearchCV.ipynb`

An exploration of hyperparameter optimization techniques using the Iris dataset.

**Key concepts covered:**
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- GridSearchCV
- RandomizedSearchCV
- Cross-validation
- Hyperparameter selection
- Model performance comparison

The SVM implementation explores different values of C and kernel configurations using 5-fold cross-validation.

### 6. K-Means Clustering

**Notebook:** `KmeansClustering.ipynb`

An unsupervised learning project exploring clustering algorithms using synthetically generated datasets.

**Algorithms implemented:**
- K-Means Clustering
- DBSCAN

**Key concepts covered:**
- Synthetic dataset generation using `make_blobs` and `make_moons`
- Feature scaling
- Elbow Method
- Inertia
- Cluster visualization
- Density-based clustering
- Comparison between K-Means and DBSCAN

### 7. Principal Component Analysis (PCA)

**Notebook:** `PCADimensions.ipynb`

A dimensionality reduction experiment demonstrating how PCA transforms high-dimensional data into a lower-dimensional representation.

**Key concepts covered:**
- Synthetic dataset generation
- Feature standardization
- Principal Component Analysis
- Dimensionality reduction
- Transformation from 5 features to 2 principal components
- Data visualization using scatter plots

---

## Technologies & Libraries

The projects in this repository primarily use the following Python libraries:

| Technology | Purpose |
|---|---|
| Python | Programming language |
| NumPy | Numerical computing |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Scikit-learn | Machine Learning algorithms and preprocessing |
| XGBoost | Gradient boosting implementation |
| SciPy | Statistical analysis |
| Jupyter Notebook | Interactive development environment |

## Repository Structure

```text
Machine-Learning-and-Analysis/
│
├── ensambleLearning.ipynb
├── fordcar.ipynb
├── ford.csv
├── GridSearchCV.ipynb
├── insurance.ipynb
├── insurance.csv
├── KmeansClustering.ipynb
├── PCADimensions.ipynb
├── titanic.ipynb
│
└── README.md
```

## Installation & Setup

Follow these steps to run the notebooks locally.

**1. Clone the repository**

```bash
git clone https://github.com/FaisalMahmudArzu/Machine-Learning-and-Analysis.git
```

**2. Navigate to the project directory**

```bash
cd Machine-Learning-and-Analysis
```

**3. Install the required libraries**

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy xgboost jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open any notebook and execute the cells to explore the implementations.

## Learning Objectives

Through these projects, I have been developing practical knowledge of:

- Understanding and analyzing real-world datasets.
- Performing Exploratory Data Analysis.
- Cleaning and preprocessing datasets.
- Engineering and selecting relevant features.
- Implementing supervised and unsupervised learning algorithms.
- Understanding regression and classification problems.
- Exploring ensemble learning techniques.
- Optimizing machine learning models using hyperparameter tuning.
- Reducing dimensionality using PCA.
- Evaluating machine learning model performance.

## Future Improvements

This repository will continue to evolve as I explore more advanced Machine Learning and Artificial Intelligence concepts.

Planned areas of exploration include:

- Advanced Machine Learning algorithms.
- Model optimization and performance improvement.
- More real-world datasets and projects.
- Deep Learning fundamentals.
- Artificial Neural Networks (ANN).
- Convolutional Neural Networks (CNN).
- Practical AI Engineering projects.

## About Me

**Faisal Mahmud Arzu**

Software Engineering student at Daffodil International University, interested in Artificial Intelligence, Machine Learning, and AI Engineering.

I use this repository to document my learning process, strengthen my understanding of machine learning algorithms, and build practical experience through hands-on implementations.

**GitHub:** [FaisalMahmudArzu](https://github.com/FaisalMahmudArzu)

---

⭐ If you find this repository useful, feel free to explore the notebooks and follow my learning journey.