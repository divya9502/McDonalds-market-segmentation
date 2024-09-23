This project analyzes McDonald's customer data to segment them based on their product preferences, visit frequency, and demographics. Techniques like K-Means Clustering, Principal Component Analysis (PCA), and Regression are used to identify and understand these customer segments.
Dataset
The dataset contains survey responses with information such as:
Attributes: Customers' opinions on whether McDonald's is yummy, convenient, greasy, etc. (binary Yes/No).
Age, Gender, VisitFrequency: Demographic information.
Like: Rating of McDonald’s from 1 to 5.
Steps
Load the Data: Read the McDonald's dataset using Pandas.
Preprocess the Data: Convert "Yes"/"No" values to 1/0 for analysis.
PCA: Reduce the dataset's dimensionality to visualize key features.
K-Means Clustering: Identify customer segments.
Regression and Tree Models: Predict and understand customer preferences.
