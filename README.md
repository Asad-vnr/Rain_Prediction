# Rain_Prediction
🌧️ Rainfall Prediction in Australia using Logistic Regression

This project answers the question:
Will it rain tomorrow in Australia?

We use Logistic Regression for binary classification on the Rain in Australia dataset, handling missing values, encoding categorical data, removing outliers, visualizing data, and evaluating model performance.
📁 Dataset

    Source: Kaggle – Rain in Australia

    Description: Daily weather observations from various weather stations across Australia.

✅ Features

    Cleaned and preprocessed real-world weather dataset

    Replaced missing values with mean, median, or mode

    Converted categorical columns using Label Encoding

    Removed outliers using the IQR method with class balancing

    Visualized data using histograms and box plots

    Trained a Logistic Regression model using Scikit-learn

    Evaluated model using accuracy, classification report, and confusion matrix

    Visualized correlations and predictions using Seaborn

🛠️ Tools & Libraries

    Python

    Pandas, NumPy

    Matplotlib, Seaborn

    Scikit-learn

    Google Colab (for notebook execution)

📊 Model Evaluation
Metric	Score
Accuracy	~85% (may vary)
Confusion Matrix	Visualized
Classification	Precision, Recall, F1-Score printed
🔍 Steps Performed

    Import libraries

    Load and preview dataset

    Handle missing values

    Encode categorical features

    Outlier detection and removal

    Visualize distributions (histograms, box plots)

    Train-test split (with class stratification)

    Feature scaling

    Train logistic regression model

    Evaluate model

    Visualize confusion matrix and correlations

🧪 How to Run in Google Colab

    Upload the weatherAUS.csv file when prompted.

    Run each code cell in order.

    See model performance and plots in the output.
