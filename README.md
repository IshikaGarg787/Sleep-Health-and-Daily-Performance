<h1>Sleep Health & Daily Performance Prediction</h1>
<h2>📌 Project Overview</h2>
This project analyzes a 100,000-row sleep health dataset to predict sleep behavior, disorder risk, and cognitive performance using machine learning models across classification and regression tasks.

<h2>📊 Dataset</h2>
Size: 100,000 records, 32 features


Targets:

felt_rested (Binary Classification)

sleep_disorder_risk (Multiclass Classification)

cognitive_performance_score (Regression)

<h2>⚙️ Tech Stack</h2>
Python (Pandas, NumPy)

Scikit-learn

XGBoost

Matplotlib / Seaborn

Google Colab

<h2>🤖 Models Used</h2>
Logistic Regression

Random Forest

XGBoost

<h2>📈 Evaluation Metrics</h2>
AUC (Binary Classification)

F1-macro (Multiclass Classification)

RMSE (Regression)

<h2>🏁 Final Results</h2>
Task	Best Model	Metric	Score

Binary Classification (felt_rested)	Logistic Regression / Random Forest	AUC	0.82

Multiclass Classification (sleep_disorder_risk)	Random Forest	F1-macro	0.78

Regression (cognitive_performance_score)	XGBoost	RMSE	5.99

<h2>🔍 Key Insights</h2>
Sleep and stress features strongly influence cognitive performance

Tree-based models perform better for complex multiclass tasks

Linear models perform competitively for binary classification

Ensemble methods significantly reduce prediction error in regression

<h2>🚀 Conclusion</h2>
The project demonstrates effective use of machine learning for sleep health analytics across classification and regression tasks, with ensemble models achieving the best overall performance.
