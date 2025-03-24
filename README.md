# Jupyter-notebook
I have tried to understand how sentiment analysis works with the help of a hotel reviews and rating dataset.
The dataset was taken from Kaggle: https://www.kaggle.com/code/jonathanoheix/sentiment-analysis-with-hotel-reviews/notebook#Conclusion

This project focuses on building a text classification model designed to predict whether a given review carries a positive or negative sentiment. It begins with transforming raw text data into a structured numeric format using a method that converts the text into a matrix of token counts. The dataset is then divided into training and test sets to ensure the model is evaluated on unseen data for a realistic performance measure.

The first model tested leverages a probabilistic classifier, Naive Bayes Classifier, known for handling high-dimensional data efficiently. While the initial results were reasonable, further improvements were pursued using a Logistic Regression Model algorithm. To enhance performance, a hyperparameter tuning process was implemented — testing different combinations of regularization techniques and solver algorithms to find the optimal configuration. This ensures the model generalizes well to new data without overfitting.

Once the best model configuration was identified, a performance evaluation was conducted using detailed metrics like precision, recall, and F1-score to assess how well the model differentiates between positive and negative sentiments. A confusion matrix visualization further illustrates how the predictions align with the true labels, offering insights into potential misclassifications.

The project integrates visual feedback at different stages, ensuring that progress is measurable and improvements are visible. The final outcome is an optimized, reliable model capable of classifying sentiments with high accuracy — demonstrating a complete, end-to-end approach to solving a real-world text classification problem. 

P.S.- WHAT DIDNOT WORK FOR ME:
I tried the GridSearchCV and my system kept running for 10 mins straight. After changes the quantity, it still didnt work. I understood this is a large dataset so took longer time. Then finally, I switched to Randomized CV.

