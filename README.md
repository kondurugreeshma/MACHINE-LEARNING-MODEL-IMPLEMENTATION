# MACHINE-LEARNING-MODEL-IMPLEMENTATION

**COMPANY**: CODTECH IT SOLUTIONS PVT.LTD

**NAME**: KONDURU GREESHMA

**INTERN ID**: CT08LLZ

**DOMAIN**: PYTHON PROGRAMMING

**BATCH DURATION**: January 10th, 2025 to February 10th, 2025

**MENTOR NAME**: NEELA SANTHOSH

# ENTER DESCRIPTION OF TASK PERFORMED NOT LESS THAN 500 WORDS

**Machine Learning Model Implementation**: Predicting Spam Emails
*Objective*: The goal of this project is to create a predictive machine learning model to classify emails as "spam" or "ham" (non-spam). The dataset used is the "SMS Spam Collection" dataset, which consists of SMS messages labeled as either spam or not spam.
*Steps to Implement*:
Import Required Libraries: We start by importing essential libraries such as pandas, scikit-learn, and matplotlib for data processing, model building, and evaluation.
Load the Dataset: The SMS Spam Collection dataset is loaded using pandas. The dataset contains two columns: one for the message content and the other for the label ("ham" or "spam").
Convert the target labels (ham, spam) into binary values (0 for ham and 1 for spam).
Clean the text data by removing stopwords, special characters, and converting all text to lowercase. This helps standardize the text for better model performance.
Feature Extraction: The text data needs to be converted into numerical features using the CountVectorizer from scikit-learn. This step involves creating a "bag of words" model, where each word in the dataset is treated as a feature.
Train-Test Split: The dataset is split into training and testing sets (usually a 70-30 or 80-20 split) using train_test_split from scikit-learn. This ensures that the model is trained on one portion of the data and evaluated on a separate, unseen portion.
Model Building: We use the MultinomialNB (Naive Bayes) classifier, which is effective for text classification tasks. The model is trained on the training data using fit().
Model Evaluation: After training, the model’s performance is evaluated using metrics like accuracy, precision, recall, and F1-score. These metrics help in assessing how well the model is distinguishing between spam and ham messages.
Results: The model’s accuracy and other evaluation metrics are printed. Visualizations (e.g., confusion matrix) are created using matplotlib to show the model’s performance in detail.
