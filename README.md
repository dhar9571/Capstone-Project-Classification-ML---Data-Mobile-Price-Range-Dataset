# Project Name: Mobile Price Range Classification

# Business Use Case:
The primary objective of the "Mobile Price Range Classification" project is to harness machine learning techniques to accurately classify mobile phones into different price ranges based on their features and specifications. This project empowers consumers, retailers, and manufacturers to make informed decisions regarding mobile phone purchases, inventory management, marketing strategies, and product development.

# Potential Impact:
The potential impact of this project is substantial, benefiting both mobile phone consumers and the broader mobile technology industry.

# Approach:

Dataset Explanation: The project used mobile price range dataset comprising a total of 2000 entries and 21 columns with no missing and duplicate values.

Feature Engineering: Data preprocessing involved deriving new features using existing features such as pixel density by multiplying pixel_height and pixel_width features. This step was crucial for preparing the data for machine learning modelling.

Algorithms: Multiple machine learning algorithms were trained, including DecisionTree, RandomForest, XGBoost, SVM and KNN. Among them, the Support Vector Classifier model demonstrated the best performance, achieving an accuracy of 95%.

End Output: The project's final output is a predictive model capable of classifying mobile phones into different price range categories based on their features and specifications.

# Challenges Faced:
The biggest challenge was to find and handle infinity numbers created in pixel density features. In order to handle this, I first replaced them with median in order to avoid errors in model training.
Another challenge was selecting the best features for model training as a lot of features were redundant. Therefore, I used SelectKBest class from sklearn library and opted best features with highest scores.

# Future Scope:
The immediate future scope involves deploying the best-performing classification model for real-time predictions, providing retailers with valuable decision support for instant pricing and inventory management.

In conclusion, this project holds the potential to deliver substantial benefits to the mobile technology sector by providing precise price range classifications for mobile phones. The combination of data preprocessing, feature engineering, and machine learning models establishes a robust foundation for future advancements and practical implementations in the industry.
