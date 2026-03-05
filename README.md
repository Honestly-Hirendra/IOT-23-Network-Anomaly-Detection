IoT-23 Network Anomaly Detection using Unsupervised Machine Learning
📌 Project Overview

This project focuses on detecting anomalous and malicious network traffic in IoT environments using unsupervised machine learning techniques. The analysis is performed on the IoT-23 dataset, which contains real-world benign and malicious IoT network traffic.

Since labeled data is often unavailable in real IoT deployments, unsupervised learning models are used to identify abnormal behavior patterns.

📂 Project Structure
IOT_23/
│
├── Data Preprocessing/
│   ├── IoT23 - Data Preprocessing.ipynb
│   └── iot23_Dataset.csv
│
├── Models/
│   ├── DBScan.ipynb
│   ├── Isolation forest.ipynb
│   ├── LOF Report.ipynb
│   └── iot23_Preprocessed.csv

⚙️ Data Preprocessing

  - Handled missing values and noisy features

  - Feature selection and normalization

  - Converted raw network traffic into ML-ready numerical format

  - Generated a cleaned and preprocessed dataset for modeling

🤖 Machine Learning Models Used: The following unsupervised anomaly detection algorithms were implemented and compared:

-DBSCAN:

    -Density-based clustering
    -Identifies anomalies as noise points

-Isolation Forest:

    - Tree-based anomaly detection
    - Efficient for high-dimensional data

- Local Outlier Factor (LOF)

    - Detects anomalies based on local density deviation

📊 Evaluation & Analysis

  - Compared anomaly detection capability of different models

  - Visualized anomaly clusters and outliers

  - Analyzed model sensitivity to hyperparameters

  - Discussed strengths and limitations of each approach

🧠 Key Learnings

  - Unsupervised learning is effective for IoT security where labels are scarce

  - Isolation Forest performed well on large-scale data

  - DBSCAN is sensitive to parameter tuning

  - LOF captures local anomalies effectively

🛠️ Tech Stack

  - Python

  - Pandas, NumPy

  - Scikit-learn

  - Matplotlib, Seaborn

  - Jupyter Notebook

🚀 Future Improvements

  - Ensemble-based anomaly detection

  - Real-time IoT traffic analysis

  - Feature engineering using time-series aggregation

  - Comparison with supervised learning models

📎 Dataset

  - IoT-23 Dataset (Real-world IoT network traffic)

📬 Author

  - Hirendra Basantani
 
