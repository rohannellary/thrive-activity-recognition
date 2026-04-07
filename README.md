\# THRIVE — Testing Human Response In Various Environments



End-to-end ML pipeline classifying 6 human activities from real-world wearable sensor data.



\## Results

\- Macro F1 > 0.91 across all activity classes

\- Gradient Boosting ensemble outperformed Logistic Regression baseline by 8pp on macro-F1

\- Feature engineering contributed the single largest gain (\~5pp F1) in the pipeline



\## Activities Classified

Walking · Sitting · Cycling · and 3 others



\## Tech Stack

Python · scikit-learn · Gradient Boosting · Random Forest · SVM · Feature Engineering



\## How to Run

pip install -r requirements.txt

python main.py



\## Models Compared

Logistic Regression, SVM, Random Forest, Gradient Boosting

Winning model selected via systematic hyperparameter search.

