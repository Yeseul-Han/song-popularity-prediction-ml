# Predicting Song Popularity Using Machine Learning Models

This project explores and predicts song popularity (hotness) using the **Million Song Subset (MSS)**. It compares a custom-built Hybrid KNN model against standard machine learning algorithms like Gaussian Naive Bayes and Gradient Boosting to identify the most effective approach for music data mining.

## Key Features
- **Exploratory Data Analysis (EDA)**: Analyzed music metadata and audio features (tempo, loudness, year, etc.) to find correlations with song popularity.
- **Custom Hybrid KNN**: Implemented a K-Nearest Neighbors algorithm from scratch, incorporating hybrid logic for better handling of music features.
- **Comparative Study**: Benchmarked three distinct models:
  - **Hybrid KNN** (Custom Implementation)
  - **Gaussian Naive Bayes**
  - **Gradient Boosting**
- **Data Preprocessing**: Handled high-dimensional sparse data, feature scaling, and categorical encoding for the Million Song Dataset.

## Methodology
- **Dataset**: Million Song Subset (Metadata and precomputed audio features).
- **Target Variable**: `song_hotness` (Categorized into classes based on percentiles: Low, Mid, High).
- **Evaluation**: Accuracy and model performance comparison across different feature sets.

## Results Summary
The project successfully categorized songs into popularity levels. The custom **Hybrid KNN** showed competitive results, while the **Gradient Boosting** model provided insights into which features (like 'year' or 'loudness') most significantly impact a song's "hotness."

## Tech Stack
- **Language**: Python (Google Colab)
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Data Source**: Million Song Dataset (MSD)

## Contributors
- Li Sha Su
- Quoc Huy Le
- Robert Cultraro
- Yeseul Han

---
*Developed for EECS 4412: Data Mining, Fall 2025.*
