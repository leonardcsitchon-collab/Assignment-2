# Assignment-2
Logistic Regression on sentiment analysis  This notebook will utilize the dataset of the movie reviews in the reviews.csv and practice.csv. Goal: Predict if a movie review is **positive (1)** or **negative (0)**.

## How It Works
1. **Loads the dataset:** Reads `practice.csv` (training) and `reviews.csv` (testing).  
2. **Preprocesses text:** Cleans, lowercases, and vectorizes words using **TF-IDF**.  
3. **Trains the model:** Uses **Logistic Regression** from `scikit-learn` to learn sentiment patterns.  
4. **Evaluates results:** Prints accuracy, F1 score, and a confusion matrix.  
5. **Predicts new input:** You can enter your own review text to see if it’s positive or negative.

## How to Run
1. Open the notebook in **Google Colab** or **Jupyter Notebook**.  
2. Run all cells in order.  
3. Results will appear at the end of the notebook.  

Example:
Review: "The movie was inspiring and fun to watch."
Prediction: Positive (0.87 confidence)

## Files
- `practice.csv` — Training data (100 reviews)  
- `reviews.csv` — Test data (20 reviews)  
- `sentiment_analysis.ipynb` — Notebook file containing all code  

---

## Requirements
Install dependencies if running locally:
```bash
pip install pandas scikit-learn matplotlib seaborn
