

Fake Profile Detection on Social Networking Websites

Overview

This project aims to detect fake profiles on social media platforms such as Facebook, Instagram, and Twitter using machine learning techniques. Fake accounts can be used for spreading misinformation, phishing, scams, and identity theft, posing serious cybersecurity threats. The system classifies profiles as real (0) or fake (1) by analyzing user behavior and profile features.

Technologies Used

Languages: Python

Algorithms: Random Forest, XGBoost

Tools/Libraries: Scikit-learn, Pandas, NumPy, Matplotlib, Instaloader (for Instagram)

Dataset: Publicly available datasets from Kaggle and social media APIs


Features

Detects fake profiles using behavioral and profile metadata.

Implements Random Forest and XGBoost for classification.

Applies MAX Voting ensemble method for better accuracy.

Preprocessing includes feature selection, normalization, encoding, and imputation.

Real-time analysis for Instagram; manual input for Facebook and Twitter.


Dataset Features

Number of followers/followings

Engagement metrics (likes, comments)

Profile details (bio, account age)

Posting frequency and patterns

Account verification status


Methodology

1. Data Collection: Data gathered from Kaggle, Instagram API, and manual inputs.


2. Preprocessing:

Handle missing values

Normalize and encode data

Split into train/test sets



3. Model Training:

Train Random Forest and XGBoost classifiers

Tune hyperparameters using Grid Search & Cross Validation



4. Prediction: Use trained models to classify new profiles


5. Evaluation: Accuracy, precision, recall, F1-score, and confusion matrix



Results

XGBoost generally showed better performance across datasets.

Confusion matrices indicate good classification on Facebook and Instagram; Twitter showed moderate results due to data limitations.


Limitations

Difficulty in detecting highly sophisticated fake accounts

Manual data input needed for some platforms

Privacy concerns in analyzing user data

Model accuracy varies by platform


Future Work

Use of deep learning (e.g., LSTM, Transformers) for unstructured data

Real-time data stream integration

Fully automated multi-platform data collection

Improved privacy compliance


Authors

Kommu Bhushanm (Assistant Professor)

Rapolu Sravani, Syed Suhana Khatun, Tadiparthi Jhansi Yasaswini, Padavala Tarun (Students)


Contact

kommubhushanm@vvit.net

rapolusravani2003@gmail.com

suhana02062003@gmail.com

yashu001t@gmail.com

padavalatarun17@gmail.com





