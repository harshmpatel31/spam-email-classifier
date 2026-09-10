# spam-email-classifier
Machine Learning Spam Email Classifier built with Python and Scikit-Learn.
A Machine Learning Project that classifies messages as either spam or legitimate (ham) using Python and scikit-learn.
Built to understand how real-world spam filters work, applying NLP and classification techniques on 5,572 email messages.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- TF-IDF
- Logistic Regression

## How It Works
1. Loads the email dataset using Pandas
2. Cleans missing values
3. Convert spam/ham labels into numerical values
4. Split the dataset into training and testing data
5. Convert text into numerical features using TF-IDF
6. Train a Logistic Regression model
7. Evaluate the model using accuracy
8. Use the trained model to classify new messages

## Model
The project uses:
- TF-IDF Vectorization
- Logistic Regression
The dataset contains 5,572 messages.

## Accuracy, Precision and Recall
<img width="885" height="770" alt="Screenshot 2026-09-09 at 10 38 30 PM" src="https://github.com/user-attachments/assets/7d6e62ad-a506-400a-b8bc-7aa398e3d4d5" />

## Example
Input:
"hey, do you wanna go play cricket at the family picnic this Saturday"

Prediction:
Ham :D
