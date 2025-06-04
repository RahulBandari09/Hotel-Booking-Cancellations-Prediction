# 🏨 Hotel Booking Cancellation Predictor
# 📌 Project Overview
Unexpected booking cancellations can lead to major operational inefficiencies and revenue loss in the hospitality industry. This project builds a machine learning classification model to predict the likelihood of a hotel booking being canceled, empowering hotel managers to make informed decisions around room allocation and revenue planning.

# 🎯 Objective
Predict whether a hotel booking will be canceled or not

Identify key drivers of cancellation to support strategic interventions

Improve room utilization and reduce last-minute losses

# 📊 Dataset
Source: Kaggle / Hotel Booking Dataset

Size: 36,275 rows

Features include: lead time, market segment, room type, special requests, arrival month, etc.

# 🛠️ Tools & Technologies
Languages: Python

Libraries: pandas, NumPy, seaborn, matplotlib, scikit-learn, statsmodels

Environment: Jupyter Notebook

# 🧠 ML Models Used
Logistic Regression (with threshold tuning)

Decision Tree (with class_weight, pre-pruning, and post-pruning)

# ✅ Key Achievements
Achieved 85% recall on test data, reducing false negatives (missed cancellations)

Performed 25+ visualizations to extract patterns from booking behavior

Applied pruning to avoid overfitting and improve generalization

Identified top features influencing cancellations:

lead_time

market_segment_type_Online

no_of_special_requests

# 📈 Evaluation Metrics
Accuracy

Precision

Recall (prioritized)

F1 Score

Confusion Matrix

ROC-AUC Curve

# 🚀 Business Impact
This model helps hotel teams proactively plan for cancellations by identifying high-risk bookings early. It enables better room reallocation, improved guest management, and reduced financial loss from no-shows.

# 🤝 Let's Connect
If you found this project interesting or useful, feel free to ⭐ the repo, give feedback, or connect with me on LinkedIn.
