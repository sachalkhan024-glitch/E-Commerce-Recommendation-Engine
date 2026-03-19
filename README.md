E-Commerce Product Recommendation Engine


📌 The Business Problem
Online retailers often struggle to increase their Average Order Value (AOV). This project builds a Machine Learning recommendation engine to analyze historical purchasing behavior and automatically suggest high-converting "Items You Might Also Like."

🛠️ Tech Stack
Python (Pandas, NumPy)

Scikit-Learn (Cosine Similarity)

Data: UCI Online Retail Dataset (500,000+ real transactions)

🧠 Methodology
Data Cleaning: Purged 140,000+ rows of missing Customer IDs and filtered out canceled/returned orders to ensure the model only learned from positive buying signals.

User-Item Matrix: Transformed flat transactional data into a behavioral matrix mapping 4,339 unique customers against 3,877 distinct products.

Collaborative Filtering: Applied Cosine Similarity to mathematically calculate the distance between products based on co-purchase history.

The Engine: Built a scalable Python function that takes a target product and returns the top 5 most highly correlated items.

📈 Results
The engine successfully identifies complex purchasing patterns. For example, testing the WHITE HANGING HEART T-LIGHT HOLDER yields highly correlated aesthetic matches (e.g., RED HANGING HEART T-LIGHT HOLDER and VINTAGE METAL SIGNS), proving the algorithm understands user segment aesthetics rather than just brute-force categorical matching.
