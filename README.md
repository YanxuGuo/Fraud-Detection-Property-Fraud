# Fraud-Detection-Property-Fraud
The objective of this project is to construct an unsupervised model to detect tax fraud using the Property Valuation and Assessment Data dataset, which can identify individuals who may be misrepresenting their property characteristics and underpaying taxes. To accomplish this, data cleaning and imputation are performed. Subsequently, the team endeavors to develop variables that can provide better estimates of a property's value and detect abnormal properties. To achieve this, 91 novel variables are created by leveraging the original field, and less important features are discarded. Since the dataset contains many characteristics, PCA is employed to reduce dimensionality, and only the five most significant principal components are retained. Two scoring methods are employed to identify anomalies in the dataset after dimensionality reduction. Two additional columns are created to store the ranking of each record in the dataset, based on its respective score, when sorted in descending order. Then, the final fraud score is computed based on the equal weight of the two scores, and the properties are sorted by their fraud score from the highest to the lowest. 1,000 Properties with a high probability of fraud are identified based on their high fraud scores. These properties are passed to experts for analysis and feedback to enhance the model's effectiveness.The data could be found at at: https://data.cityofnewyork.us/Housing-Development/Property-Valuation-and-Assessment-Data/rgy2-tti8
