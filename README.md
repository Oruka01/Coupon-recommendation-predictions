# Coupon-recommendation-predictions
This project aims to predict whether a person will accept the coupon recommended to him/her in different driving scenarios

Data Source

https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation
Tong Wang, tong-wang '@' uiowa.edu, University of Iowa
Cynthia Rudin, cynthia '@' cs.duke.edu, Duke University
Methodology

The project uses the Classification models to predict whether or not a driver will accept a coupon recommended to them. Specifically, we used the following techniques:

decision tree classifier, KNeighbors Classifier, Bagging Classifier and Random Forest Classifier, to create models that predict the coupon recommendations. However from the multiple models created, the Random Forest Classifier produced the highest F1 score meaning this model performed better than the rest of the models, and therefore logical to adopt this model for production

Results

The F1 score is a metric that measures the balance between precision and recall for a binary classification problem such as the one we are dealing with, It is often used as a performance metric for machine learning models.

For our binary classification problem, we achieved an F1 score of 0.72 for the negative class and an F1 score of 0.80 for the positive class.

The F1 score ranges from 0 to 1, where a score of 1 represents perfect precision and recall, and a score of 0 represents the worst possible performance. Therefore, our model performed reasonably well for both classes, with a higher score for the positive class.

Therefore the model would be useful in production, this is an algorithm that is used for classification tasks.

The model can be used in the following ways:-

Random Forest Classifier is a popular machine learning algorithm that is used for classification tasks. It is an ensemble learning method that combines multiple decision trees to improve the accuracy of the model. Here's how Random Forest Classifier model can be used in machine learning:

Data Preparation: Before using the Random Forest Classifier model, you need to prepare the data. This involves cleaning and preprocessing the data to make it suitable for training the model.

Model Training: Once the data is ready, you can train the Random Forest Classifier model. During the training process, the algorithm builds multiple decision trees on different subsets of the training data. Each decision tree is constructed using a random subset of features, which helps to reduce overfitting.

Model Evaluation: After the training process is complete, you need to evaluate the performance of the model. You can do this by using a test dataset that was not used during the training process. The performance of the model is typically measured using metrics such as accuracy, precision, recall, and F1 score.

Model Deployment: Once the model is trained and evaluated, it can be deployed in a production environment. This involves integrating the model into an application or system that can use it to make predictions on new data.

In summary, Random Forest Classifier is a powerful machine learning algorithm that can be used for classification tasks. It is particularly useful when dealing with large datasets, noisy data, and complex relationships between features. By combining multiple decision trees, Random Forest Classifier can improve the accuracy of the model and reduce overfitting.

Images:

image

image

The Model;

Random Forest Classifier is a popular machine learning algorithm used for classification tasks. It is an ensemble learning method that combines multiple decision trees to make predictions.

Each decision tree in a Random Forest is trained on a random subset of the training data and a random subset of the input features. This helps to reduce overfitting and increase the diversity of the individual trees. The final prediction is made by combining the predictions of all the trees in the forest.

The algorithm is suitable for both binary and multiclass classification problems and can handle both categorical and numerical data. It is also capable of handling missing values and can be used for feature selection.

Overall, Random Forest Classifier is a powerful and versatile algorithm that is widely used in machine learning for its high accuracy and robustness.

Limitations;

Interpretability: Random Forest Classifier is not as interpretable as some other algorithms like decision trees. It can be difficult to understand which features are important for making predictions.

Memory and Computation: Random Forest Classifier can require a lot of memory and computation, especially when the number of trees in the forest is high or the data has a large number of features.

For further information;

For any additional questions, please contact email oruka.rapha01@gmail.com
