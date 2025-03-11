# Sentiment Analysis on Customer Feedback

This project performs **Sentiment Analysis** on customer feedback using **VADER** and **TextBlob** sentiment analysis techniques. The application is deployed using **Streamlit**.

## Dataset
- **Reviews.csv**: Contains customer feedback data with text reviews and scores.

## Code Files
- **Sentimental_Analysis.ipynb**: A Jupyter Notebook for code implementation and data visualization.
- **analyzing.py**: Python script containing the Streamlit web application code for interactive user feedback analysis.

## Requirements
Install the required libraries using the following command:
pip install streamlit textblob vaderSentiment cleantext matplotlib pandas

## How to Run the Project
1. Clone the repository:
git clone https://github.com/pranjalparmar23/sentiment-analysis.git

2. Change the directory:
cd sentiment-analysis

3. Run the Streamlit application:
streamlit run analyzing.py

4. Open the provided **localhost** link in your browser.

## Features
✅ Analyzes sentiment scores and subjectivity of customer reviews using **VADER** and **TextBlob**.  
✅ Classifies sentiments into five categories:
   - Highly Positive
   - Positive
   - Neutral
   - Negative
   - Highly Negative  
✅ Provides an interactive interface for user feedback analysis.  
✅ Offers text cleaning functionality for removing noise from the text.  
✅ Displays visual graphs for the distribution of sentiment scores.  
✅ Displays a summarized DataFrame showcasing key sentiment insights.

## Graphical Representation
The application includes a **Histogram** plot that visualizes the distribution of sentiment scores for better data understanding.

## Output
- **VADER Sentiment Class** and **Score** for user-provided text.  
- **TextBlob Polarity** and **Subjectivity** metrics.  
- Cleaned text output for better readability.  

## Example Usage
Enter a sample review text in the text area to see:
- **VADER Sentiment Class and Score**
- **TextBlob Sentiment Details**
- Cleaned text result
- Graphical visualization of dataset scores.
