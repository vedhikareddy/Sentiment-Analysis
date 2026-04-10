Sentiment Analysis for University Branding
Project Overview
This project focuses on quantifying the brand reputation of an educational institution by analyzing unstructured student feedback from social media platforms. By implementing a text-mining pipeline, the project transforms thousands of qualitative reviews into quantitative insights, allowing administrative stakeholders to identify institutional strengths and areas for improvement.

Technical Workflow
The project follows a rigorous Data Science lifecycle:

Data Acquisition: Scraped and aggregated real-world student reviews and social media posts regarding campus life, faculty, and infrastructure.

Text Preprocessing (NLP): Utilized NLTK and Scikit-Learn to clean the data through:

Tokenization and Stop-word removal.

Lemmatization to standardize word forms.

TF-IDF Vectorization to convert text into numerical feature vectors.

Sentiment Classification: Trained a Multinomial Naive Bayes classifier to categorize reviews into positive and negative polarities.

Evaluation: Validated model performance using precision, recall, and F1-score metrics to ensure accurate sentiment detection despite the informal nature of social media language.

Key Insights & Visualizations
Identified key "Brand Drivers" (e.g., specific departments or facilities) that correlate with high student satisfaction.

Generated Seaborn and Matplotlib heatmaps and word clouds to visualize recurring themes in student complaints and praise.

Demonstrated that data-driven sentiment tracking can provide a scalable alternative to traditional manual surveys.

Technologies Used
Language: Python

Libraries: Pandas, NumPy, Scikit-Learn, NLTK, Matplotlib, Seaborn

Concepts: Supervised Learning, Natural Language Processing, Feature Engineering
