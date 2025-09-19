 # Fake News Detection using Machine Learning

This project demonstrates the development of a high-accuracy machine learning model to classify news articles as either "Real" or "FAKE". The entire process, from data exploration and cleaning to model training and evaluation, is detailed in the accompanying Jupyter Notebook.

---

## 🎯 Project Overview

The primary goal of this project is to leverage Natural Language Processing (NLP) and classification algorithms to build a robust tool for combating misinformation. The notebook explores two different models—Logistic Regression and Random Forest—and compares their performance, ultimately achieving an accuracy of over 99%.

### ✨ Key Features:
* **High-Performance Model:** The final Random Forest model achieves an outstanding **99.83% accuracy** on the test set.
* **Comparative Analysis:** Includes a detailed comparison between a baseline Logistic Regression model and the more advanced Random Forest model.
* **In-depth Data Visualization:** Features charts, a confusion matrix heatmap, and word clouds to provide deep insights into the dataset and model performance.
* **Reproducible Workflow:** The notebook is well-documented and follows a clear, logical structure, making the project easy to understand and reproduce.

---

## 💾 Dataset

The dataset for this project is sourced from Kaggle and contains over 40,000 news articles, each labeled as either real or fake.

Due to GitHub's file size limits, the dataset is not included in this repository. Please download it from the original source below:

* **Link:** [Fake News Detection Datasets on Kaggle](http://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets)

**Instructions:** After downloading, unzip the folder and place the `true.csv` and `fake.csv` files in the same directory as the Jupyter Notebook.

---

## 🛠️ Technologies Used

* **Python 3**
* **Jupyter Notebook**
* **Pandas:** For data loading and manipulation.
* **Scikit-learn:** For machine learning model implementation (TF-IDF, Logistic Regression, Random Forest) and evaluation.
* **Matplotlib & Seaborn:** For data visualization, including charts and heatmaps.
* **WordCloud:** For generating insightful word cloud images.

---

## 🚀 How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/Your-Repository-Name.git](https://github.com/YourUsername/Your-Repository-Name.git)
    ```
2.  **Download the Dataset:** Use the Kaggle link provided above to download the `true.csv` and `fake.csv` files. Place them in the cloned repository folder.

3.  **Install Dependencies:** It is recommended to create a virtual environment. Install the required libraries:
    ```bash
    pip install pandas scikit-learn matplotlib seaborn wordcloud jupyter
    ```
4.  **Run the Notebook:** Launch Jupyter Notebook and open the `Fake_News_Detection_and_Evaluation_with_Confusion_Matrix.ipynb` file.
    ```bash
    jupyter notebook
    ```
5.  **Execute the Cells:** You can run the cells in order from top to bottom to see the entire process and results.

---

## 📊 Results

The project successfully compared two models, with the Random Forest Classifier proving to be significantly more effective.

| Model | Accuracy |
| :--- | :---: |
| Logistic Regression | 93.88% |
| **Random Forest Classifier** | **99.83%** |

The confusion matrix for the Random Forest model shows an extremely low number of misclassifications, confirming its high reliability.



---

## 📄 Report

A detailed project report in `.docx` format is also included in this repository, outlining the project's objectives, methodology, and conclusions.


## 🎥 Project Demonstration

Click the thumbnail below to watch a 2-minute video demonstration of the project, from data loading to live prediction.

[![Project Demo Video](https://img.youtube.com/vi/lhjATx-EqZk/0.jpg)](https://youtu.be/lhjATx-EqZk)
