# Sentiment Analysis Model

This project is a Machine Learning model that classifies text into three categories: **Positive**, **Negative**, or **Neutral**. It uses TF-IDF for text vectorization and Logistic Regression for classification.

## Dataset
The dataset (`Sentiment Analysis Data.csv`) contains 600 sentences, each labeled with a sentiment.

## How to Run This Project

### Option 1: Run in Google Colab (Easiest)
1. Download the `.ipynb` and `.csv` files from this repository.
2. Go to [Google Colab](https://colab.research.google.com/).
3. Upload both files to the Colab workspace (using the folder icon on the left).
4. Open the notebook and click **Runtime > Run all**.

### Option 2: Run Locally
If you have Python installed on your machine, follow these steps:
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt