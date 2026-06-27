# Machine Learning, Data Science, and Deep Learning with Python 🚀

Welcome to this comprehensive collection of Jupyter Notebooks, Python scripts, and datasets covering a wide spectrum of Data Science and Machine Learning topics. This repository is designed to serve as both a self-contained learning path and a practical reference guide for building, training, and deploying intelligent models.

---

## 📖 Repository Overview

The materials in this repository progress from foundational statistics and Python libraries to advanced Deep Learning architectures and Big Data pipelines.

### 🧠 Key Domains Covered

* **🐍 Python for Data Science:** Foundations of Python, along with deep dives into data manipulation and visualization using **Pandas**, **Matplotlib**, and **Seaborn**.
* **📊 Statistics & Mathematics:** Essential statistical concepts including probability distributions, variance, percentiles, moments, and hypothesis testing (T-tests).
* **🤖 Classical Machine Learning:** Robust implementations of foundational algorithms:
    * *Regression:* Linear, Multiple, and Polynomial regression.
    * *Classification:* Naive Bayes, Decision Trees, K-Nearest Neighbors (KNN), and Support Vector Classifiers (SVC).
    * *Clustering & Unsupervised Learning:* K-Means and Principal Component Analysis (PCA).
* **⚡ Deep Learning & AI:** Cutting-edge neural network implementations using **TensorFlow** and **Keras**:
    * Multi-layer Perceptrons (MLP)
    * Convolutional Neural Networks (CNNs) for image classification.
    * Recurrent Neural Networks (RNNs) for sequential data.
    * Transfer Learning techniques.
* **🎬 Recommender Systems:** Building collaborative filtering systems based on user-item interactions (e.g., MovieLens datasets).
* **☁️ Big Data (Apache Spark):** Leveraging **PySpark** for scalable machine learning pipelines (Decision Trees, K-Means, PCA).
* **🎮 Reinforcement Learning:** Q-Learning implementations for autonomous agent training.
* **📝 Natural Language Processing (NLP):** Text processing algorithms like TF-IDF for search and classification.

---

## 🗂️ Project Highlights

This repository includes several applied projects that tackle real-world problems:

| Project Notebook | Description | Tech Used |
| :--- | :--- | :--- |
| 🧬 `mammo_masses_project.ipynb` | **Mammographic Masses Classification:** Predicting benign vs. malignant tumors using patient data. | Scikit-Learn, Pandas |
| 🖼️ `DeepLearningProject.ipynb` | **Deep Learning Image Classification:** Training neural networks to classify edge-case images. | TensorFlow, Keras |
| 🗳️ `PoliticsExercise.ipynb` | **Political Data Analysis:** Clustering and predicting political affiliations based on voting records. | K-Means, Scikit-Learn |

---

## 🛠️ Tech Stack & Requirements

To run the notebooks and scripts in this repository, you will need an environment equipped with:

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook / JupyterLab
* **Core Libraries:** `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`
* **Deep Learning:** `tensorflow`, `keras`
* **Big Data:** `pyspark`

---

## 💡 How to Use

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
   cd YOUR-REPO-NAME
   Set up your environment:
Ensure you have the required dependencies installed (we highly recommend using an Anaconda environment).

Bash
pip install -r requirements.txt
(Note: Remember to create a requirements.txt file if you haven't already!)

Launch Jupyter:

Bash
jupyter notebook
Open the notebooks in your browser and execute the cells sequentially to follow along with the concepts and data pipelines.

⚠️ Note on Datasets: Some datasets (such as ml-100k, emails, and MNIST_data) must be present in the local directory for the models to train correctly. Make sure they are downloaded before running the respective notebooks.


## 🗺️ Course Index & Directory Structure

---

### 📊 Basics & Statistics
*Foundational concepts in statistics and exploratory data analysis.*

* **Python & Visualization Foundations:**
  * 🐍 `Python101.ipynb`
  * 🐼 `PandasTutorial.ipynb`
  * 📈 `MatPlotLib.ipynb`
  * 📊 `Seaborn.ipynb`
* **Descriptive & Inferential Statistics:**
  * 📐 `MeanMedianMode.ipynb` / `MeanMedianExercise.ipynb`
  * 📉 `StdDevVariance.ipynb`
  * 🎯 `Percentiles.ipynb`
  * 🔄 `Moments.ipynb`
  * 🔔 `Distributions.ipynb`
  * 🔗 `CovarianceCorrelation.ipynb`
  * 🎲 `ConditionalProbabilityExercise.ipynb` / `ConditionalProbabilitySolution.ipynb`
  * 🧪 `TTest.ipynb`
  * 🚨 `Outliers.ipynb`

---

### 🧠 Classical Machine Learning
*Notebooks training regression, classification, clustering models, and data preprocessing.*

| Category | Jupyter Notebooks |
| :--- | :--- |
| **📈 Regression** | `LinearRegression.ipynb`, `PolynomialRegression.ipynb`, `MultipleRegression.ipynb` |
| **🎯 Classification** | `NaiveBayes.ipynb`, `DecisionTree.ipynb`, `KNN.ipynb`, `SVC.ipynb` (Support Vector Classifier) |
| **🔮 Clustering & Dimensionality** | `KMeans.ipynb`, `PCA.ipynb` (Principal Component Analysis) |
| **🧪 Model Validation** | `TrainTest.ipynb`, `KFoldCrossValidation.ipynb` |

---

### 🤖 Deep Learning & Reinforcement Learning
*Notebooks covering Neural Networks, Deep Learning frameworks, and advanced concepts.*

* ⚙️ `Tensorflow.ipynb`
* 🧠 `Keras.ipynb`
* 🖼️ `Keras-CNN.ipynb` *(Convolutional Neural Networks)*
* 🔂 `Keras-RNN.ipynb` *(Recurrent Neural Networks)*
* 🔄 `TransferLearning.ipynb`
* 🎮 `Q-Learning.ipynb` *(Reinforcement Learning)*

---

### 🌐 Recommender Systems
* 🎬 `SimilarMovies.ipynb`
* 👥 `ItemBasedCF.ipynb` *(Item-Based Collaborative Filtering)*

---

### 🚀 Big Data (Apache Spark)
*Python scripts utilizing PySpark for scalable machine learning pipelines.*

* 🪵 `SparkDecisionTree.py`
* 🧼 `SparkKMeans.py`
* 📉 `SparkLinearRegression.py`
* 📐 `SparkPCA.py`

---

### 📝 Natural Language Processing (NLP)
* 🔤 `TF-IDF.py` *(Term Frequency-Inverse Document Frequency)*

---

### 🎯 Projects and Assignments
* 📑 `FinalProjectAssignment.ipynb`
* 🧬 `mammo_masses_project.ipynb` *(Mammographic Masses dataset analysis)*
* 🖼️ `DeepLearningProject.ipynb` / `DeepLearningProject-Solution.ipynb`
* 🔝 `TopPages.ipynb`
* 🗳️ `PoliticsExercise.ipynb`

---

### 📂 Datasets and Data Subdirectories
*Raw data files and folders serving as inputs for the notebooks and scripts.*

#### 📁 Subdirectories:
* 📂 `MNIST_data/` *(Handwritten digit dataset used for computer vision)*
* 📂 `ml-100k/` *(MovieLens dataset for recommender systems)*
* 📂 `emails/` *(Corpus likely utilized for Naive Bayes spam classification)*

#### 📄 Data Files:
* 🧾 `PastHires.csv`, `access_log.txt`, `regression.txt`, `subset-small.tsv`
* 🇺🇸 `house-votes-84.data.txt`, `house-votes-84.names.txt`
* 🧬 `mammographic_masses.data.txt`, `mammographic_masses.names.txt`

---

### 🖼️ Images
*Image assets likely utilized in the transfer learning or CNN deep learning modules.*

> 🖼️ `VLA.jpg`, `breakfast.jpg`, `bridge.jpg`, `bunny.jpg`, `castle.jpg`, `fighterjet.jpg`, `firetruck.jpg`, `peek.jpg`
>
> 📊 `MyPlot.png` *(Example exploratory graph output)*
