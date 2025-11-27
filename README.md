README – Personalized News Recommendation Engine
Overview
This project implements a Personalized News Recommendation Engine using Python, Pandas,
Scikit-Learn, and WordCloud. The system trains a Naive Bayes classifier on a labeled news dataset
and recommends articles based on the user’s preferred category. It also generates a topic word cloud
for visualization.
Features
• Upload CSV dataset dynamically using Google Colab file uploader.
• Train a TF-IDF Vectorizer + Multinomial Naive Bayes model.
• Predict news categories based on titles.
• Calculate a custom recommendation score using:
- AI confidence
- Category match
- Recency (newness) of article
• Display top 5 personalized news recommendations.
• Generate a word cloud for key topics in the selected category.
How It Works
1. Load dataset (news_dataset.csv).
2. Extract ‘title’ and ‘category’.
3. Train Naive Bayes classification pipeline.
4. User inputs preferred category (sports, politics, health, tech).
5. System predicts categories & computes confidence.
6. System applies a scoring formula:
final_score = α*confidence + β*match + γ*recency
7. Sort results and display top 5.
8. Generate word cloud.
Technologies Used
• Python
• Pandas, NumPy
• Scikit-Learn (TfidfVectorizer, MultinomialNB)
• Matplotlib
• WordCloud
• Google Colab
How to Run
1. Open the notebook in Google Colab.
2. Upload news_dataset.csv when prompted.
3. Run all cells.
4. Enter your preferred category.
5. View recommended news and auto■generated word cloud.
File Source
The content of this README is based on the uploaded PDF: “News retrieval.pdf”.
