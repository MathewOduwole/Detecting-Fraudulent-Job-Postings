# Detecting-Fraudulent-Job-Postings
This dataset contains job descriptions out of which a pecerntage of them are fake. The data consists of both textual information and meta-information about the jobs. The primary purpose of this dataset is to facilitate the development of models capable of identifying fraudulent job postings.



Introduction <a name="introduction"></a>
The Fraudulent Job Postings Detection project aims to develop machine learning models that can effectively identify fraudulent job postings. Fraudulent job postings can cause financial harm and damage a company's reputation. This project helps organizations filter out fake job advertisements, thereby improving the quality of their hiring process.

Getting Started <a name="getting-started"></a>
Prerequisites <a name="prerequisites"></a>
Before running the project, ensure you have the following prerequisites installed:

Python 3.7+
Required Python libraries (specified in requirements.txt)
Installation <a name="installation"></a>

Project Overview <a name="project-overview"></a>
The project involves the following key components:

Data collection and preprocessing
Exploratory Data Analysis (EDA)
Machine learning model development
Model evaluation and interpretation
Deployment for real-time predictions
Data <a name="data"></a>
Data Source <a name="data-source"></a>:
The dataset used in this project is sourced from [[Kaggle](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)]. It consists of approximately 18,000 job descriptions, with around 800 classified as fraudulent.

Data Description <a name="data-description"></a>:
The dataset includes both textual information and meta-information about job postings. Features include job titles, locations, company profiles, descriptions, requirements, and more. Data preprocessing steps were applied to handle missing values, encode categorical features, and normalize numerical features.

Usage <a name="usage"></a>
Data Preprocessing <a name="data-preprocessing"></a>:
Data preprocessing involved handling missing values, encoding categorical variables, and scaling numerical features to prepare the data for analysis.

Exploratory Data Analysis (EDA) <a name="eda"></a>:
EDA was performed to gain insights into the dataset. Visualizations and statistical summaries were used to understand the distribution of features and identify patterns.

Model Building <a name="model-building"></a>:
Several machine learning models, including Support Vector Machines (SVM), were trained using the preprocessed data to classify job postings as fraudulent or genuine.

Model Evaluation <a name="model-evaluation"></a>:
Model performance was evaluated using various metrics, including accuracy, precision, recall, and F1-score. Cross-validation techniques were used to ensure robustness.

Model Interpretation <a name="model-interpretation"></a>:
Model interpretation involved analyzing feature importance and identifying key traits or phrases associated with fraudulent job postings.

Contributing <a name="contributing"></a>:
I welcome contributions from the community. If you'd like to contribute, please follow the contribution guidelines.



Acknowledgments <a name="acknowledgments"></a>:
I would like to thank the Kaggle comunity for providing the dataset used for this project.

