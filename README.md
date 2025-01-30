# Netflix Movies and TV Shows Classification Using Machine Learning
Netflix is a subscription-based video streaming service that offers a variety of TV shows and movies. Netflix has content that comes from its own productions and other parties.  Netflix can be accessed on various devices, such as: Smart TVs, Gaming consoles, Streaming media players, Cable set-top boxes, Smartphones, Tablets, Computers.
The Netflix Movies and TV Shows Dataset available on Kaggle is a dataset that contains information about movies and TV shows available on Netflix, including features such as title, genre, release year, duration, director, actors, country of origin, rating, and short description.
This project analyzes the Netflix Movies and TV Shows dataset from Kaggle, exploring trends in content distribution, genre popularity, and country-wise production. Additionally, we apply machine learning models to classify and predict content types based on available features.
#### The dataset is available on Kaggle: https://www.kaggle.com/datasets/anandshaw2001/netflix-movies-and-tv-shows/data

# 🎯Goals
1. Perform Exploratory Data Analysis (EDA) to understand key insights from the dataset.
2. Preprocess and clean the data for further analysis.
3. Apply machine learning models to classify content (Movie vs TV Show).
4. Compare different classification models and evaluate their accuracy.

# 🛠Tools and Libraries
This project is built using Python and the following libraries:
1. <b>Data Processing & EDA</b>: Pandas, NumPy, Matplotlib, Seaborn
2. <b>Machine Learning Models</b>: Scikit-learn (Decision Tree, Random Forest, Logistic Regression)
3. <b>Model Evaluation</b>: Accuracy Score, Confusion Matrix, Classification Report

# 🔄Project Workflow
1. <b>Data Loading & Exploration</b>
   - Load dataset and inspect missing values.
   - Perform statistical analysis and data visualization.
2. <b>Data Preprocessing & Feature Engineering</b>
   - Handle missing values.
   - Convert categorical variables into numerical formats.
   - Feature extraction (e.g., converting duration to minutes or season count).
3. <b>Machine Learning Implementation</b>
   - Split data into training and testing sets.
   - Train and evaluate Decision Tree, Random Forest, and Logistic Regression models.
   - Compare accuracy scores and visualize results.
4. <b>Model Evaluation & Insights</b>
   - Generate confusion matrix & classification reports.
   - Identify best-performing models.
   - Provide business insights based on findings.

# 📊Conclusion
1. Movies dominate Netflix's content compared to TV Shows.
2. Most content originates from the United States, followed by India and the UK.
3. Random Forest outperforms Logistic Regression in classification accuracy.
4. Future enhancements: Implement a recommender system or use NLP for sentiment analysis on movie descriptions.
