📊 Spam Classification with ML Pipeline & DVC (In Progress)
This project aims to provide a comprehensive, end-to-end implementation of a Machine Learning pipeline for classifying spam messages, with integrated tools for experiment tracking and data versioning using DVC and AWS S3. While the model training and basic evaluation are currently implemented, integration with DVC and cloud storage is ongoing.

🚀 Project Goals
✅ Build and evaluate a spam classification model

🛠️ Set up a reproducible ML pipeline using DVC

🌩️ Store and version datasets/models using AWS S3

📊 Track model experiments, metrics, and artifacts

🔄 Enable easy collaboration and scalability

✅ Current Progress
✔ Data & Model
Dataset: SMS Spam Collection Dataset (labeled as spam/ham)

Model: Initial implementation with text preprocessing, vectorization (TF-IDF), and classifier training using Naïve Bayes or similar models.

✔ Notebook
spam_classification.ipynb: Contains data loading, cleaning, feature extraction, and baseline model training.

🛠️ Upcoming Tasks
 Refactor code into modular scripts (data ingestion, processing, model training, evaluation)

 Initialize DVC pipeline and add data/ and models/ directories to version control

 Configure AWS S3 as remote for DVC storage

 Log metrics and parameters using DVC’s experiment tracking

 Create dvc.yaml pipeline stages for reproducibility

 Tech Stack
Python

scikit-learn, pandas, numpy

DVC for version control

AWS S3 for remote storage

(Planned) MLflow or Weights & Biases for advanced tracking
