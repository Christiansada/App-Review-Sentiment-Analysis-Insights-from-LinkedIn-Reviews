# App Review Sentiment Analysis: Insights from LinkedIn Reviews

This repository presents a sentiment analysis project on LinkedIn app reviews, leveraging natural language processing (NLP) techniques to uncover insights about user satisfaction and feedback trends. The analysis utilizes text mining and visualization tools to identify sentiment patterns in user reviews.

---

## Project Overview

User feedback is crucial for improving app experiences. This project analyzes LinkedIn app reviews to classify sentiments as positive, negative, or neutral, providing actionable insights for product improvement and user engagement strategies.

---

## Dataset Details

The dataset, `linkedin-reviews.csv`, contains app reviews extracted from the LinkedIn app. Key attributes include:

- **Review Text**: The written feedback from app users.
- **Rating**: Numeric rating provided by the users.

---

## Key Features of the Project

1. **Data Cleaning and Preprocessing**:
   - Handling missing values and duplicates.
   - Text preprocessing, including tokenization, stopword removal, and stemming.

2. **Sentiment Analysis**:
   - Using the `TextBlob` library to classify sentiments into positive, negative, or neutral categories.
   - Generating sentiment scores for each review.

3. **Visualization**:
   - Creating word clouds to highlight frequent words in positive and negative reviews.
   - Plotting sentiment distributions and trends over time using `matplotlib` and `seaborn`.

---

## Project Structure

- **Notebook**: `App_Review_Sentiment_Analysis.ipynb`  
  Contains the complete code pipeline for data analysis and visualization.
- **Dataset**: `linkedin-reviews.csv`  
  The dataset used for sentiment analysis.
- **Requirements**: `requirement.txt`  
  A file listing all the dependencies for this project.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/App-Review-Sentiment-Analysis.git
   cd App-Review-Sentiment-Analysis
2. Install the required Python packages
   ```bash
   pip install -r requirement.txt

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook App_Review_Sentiment_Analysis.ipynb

4. Run the notebook cells sequentially to explore the results.


---

## Results and Insights

- Sentiment Distribution: Breakdown of positive, negative, and neutral reviews.
- Frequent Words: Word clouds highlighting key themes in user feedback.
- Recommendations: Insights into areas for product improvement based on user sentiment.


