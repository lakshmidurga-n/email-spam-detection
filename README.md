# Email Spam Detection using Machine Learning

A machine learning model that classifies emails/messages as **Spam** or **Ham (not spam)**. Built as part of my AI/ML Internship project.

## Dataset
- File: `mail_data.csv`
- Columns: `Category` (spam / ham) and `Message` (mail text)
- Labels: spam = 0, ham = 1

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Workflow
1. Load the dataset and handle null values
2. Explore data (spam vs ham count)
3. Encode labels (spam = 0, ham = 1)
4. Split into training (80%) and testing (20%) sets
5. Convert text to numerical features using TF-IDF
6. Train a Logistic Regression model
7. Evaluate with accuracy, classification report and confusion matrix
8. Predict on new mails

## Results
- Training accuracy: 96.77%
- Testing accuracy: 96.68%
- Spam: precision 1.00, recall 0.76
- Ham: precision 0.96, recall 1.00

## How to Run
1. Open `Email_spam_Detection.ipynb` in Google Colab
2. Run the cells from top to bottom
3. Upload `mail_data.csv` when asked

## Sample Prediction
- "WINNER!! You have won a free prize. Call now to claim your reward!" -> SPAM
- "Hi, are we meeting at the college tomorrow for the project review?" -> HAM

## Author
Lakshmidurga
