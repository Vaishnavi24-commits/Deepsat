# DeepCSAT – E-commerce Customer Satisfaction Score Prediction
This project aims to predict Customer Satisfaction (CSAT) scores in real-time using a deep learning-based Artificial Neural Network (ANN) model. The dataset, derived from the e-commerce platform Shopzilla, includes customer interaction data such as service channels, timestamps, agent performance, and customer feedback. Traditional satisfaction surveys often lag in response and insight generation. This model provides a scalable and fast solution for identifying satisfaction trends based on interaction behavior.

Key steps included:

Data Cleaning & Feature Engineering: Converted timestamps, calculated response durations, and derived survey delay metrics.

Categorical Encoding & Scaling: Applied Label Encoding to textual columns and standardized numerical features.

Model Architecture: Built a neural network with Keras (TensorFlow backend), including dropout regularization and ReLU activations.

Performance Evaluation: Achieved effective mean absolute error (MAE), enabling accurate prediction of satisfaction scores (1 to 5 scale).

Outcome: The model can help businesses proactively identify service gaps, improve agent performance, and enhance overall customer experience.

Technologies Used:
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow (Keras), Google Colab
