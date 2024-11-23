Image Classification Project: Apples vs. Tomatoes
This project focuses on image classification using machine learning techniques to distinguish between images of apples and tomatoes. The dataset consisted of images organized into two categories, stored in separate folders: apples and tomatoes.

Data Preprocessing
To process the images, I utilized several libraries, including pandas, numpy, matplotlib, imutils, and cv2. The images were converted into numerical data using numpy, which initially resulted in a 3D array. To simplify the data for machine learning algorithms, I applied a flattening method to transform the 3D array into a 2D array. This structured data was then converted into a DataFrame, making it easier to handle and manipulate for analysis.

Dataset Splitting
The dataset was divided into training and testing sets to build and validate the models. I used an 80/20 split, with 80% of the data for training the models and 20% for testing. This approach ensured a sufficient amount of data for both training and evaluation.

Modeling and Algorithms
To classify the images, I implemented a variety of machine learning algorithms, including:

Naive Bayes: A simple probabilistic classifier based on Bayes' theorem.
K-Nearest Neighbors (KNN): A distance-based algorithm that classifies data points based on their nearest neighbors.
Decision Tree Classifier: A tree-based model that splits data based on feature values.
Random Forest Classifier: An ensemble learning method that builds multiple decision trees and combines them for more accurate results.
Logistic Regression: A linear model for binary classification.
Model Evaluation
For evaluation, I utilized standard metrics such as accuracy, precision, recall, and F1-score to assess the performance of each classifier. These metrics provided insights into the strengths and weaknesses of each algorithm, allowing me to compare their effectiveness in distinguishing between apples and tomatoes.

Project Outcome
This project was a comprehensive hands-on experience in computer vision, covering the entire machine learning pipeline—from data preprocessing and transformation to model building, training, and evaluation. It enhanced my understanding of classification techniques and image processing, providing valuable experience for future projects in the field of computer vision.
