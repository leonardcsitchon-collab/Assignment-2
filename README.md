# Assignment-2
**Logistic Regression on sentiment analysis**

In this notebook, the dataset of the movie reviews that will be used will be the `reviews.csv` and `practice.csv`.  

**Target:** Determine whether the movie review is a positive one (1) or a negative one (0).

## How It Works
- **Loads the data:** Reads `practice.csv` (training) and `reviews.csv` (testing).  
- **Clean Text:** Removes, lowers, and vectors TF-IDF words.  
- **Model training:** Training Logistic Regression of scikit-learn to train sentiment patterns.  
- **Measures performance:** Prints accuracy, F1 score and a confusion matrix.  
- **Makes predictions:** This is a configuration where you can type in your own review text and find out whether it is going to be a positive or a negative one.

## How to Run
1. Open the notebook on **Google Colab** or **Jupyter Notebook**.  
2. Run all cells in order.  
3. The outcomes will be found at the end of the notebook.

**Example:**
Review: The film was great and enjoyable to see.
Prediction: Positive (0.87 confidence)

## Files
- `practice.csv` - Training data (100 reviews)  
- `reviews.csv` - Test data (20 reviews)  
- `sentiment_analysis.ipynb` - Notebook file with the entire code.


## ⚙️ Requirements
Install requirements when running on the host:

```bash
pip install pandas scikit-learn matplotlib seaborn
