📚 Book Recommendation System

A Machine Learning-powered platform that delivers personalized book recommendations using Collaborative Filtering, Content-Based Filtering, and Hybrid Recommendation techniques.


🧠 Overview
The Book Recommendation System is an end-to-end ML project that suggests books tailored to individual user preferences. It combines multiple recommendation strategies with a FastAPI backend and React frontend to deliver an intelligent, user-friendly reading experience.

✨ Features

🎯 Personalized Recommendations — Tailored suggestions based on user behavior and preferences
👥 Collaborative Filtering — Leverages similarities among users and their ratings
📖 Content-Based Filtering — Recommends books using genre, author, publication year, and description
🔀 Hybrid Recommendation System — Combines both approaches for improved accuracy
📊 Exploratory Data Analysis (EDA) — In-depth analysis of ratings, genres, and user activity
⚡ FastAPI Backend — High-performance REST API integration
⚛️ React Frontend — Clean, responsive user interface
📈 Model Evaluation — Performance measured with industry-standard metrics


🛠️ Technologies Used
Programming Languages
Python, JavaScript

Libraries & Frameworks
CategoryToolsData ProcessingPandas, NumPyMachine LearningScikit-learn, Surprise LibraryDeep LearningTensorFlow / KerasBackendFastAPIFrontendReactVisualizationMatplotlib, Seaborn
Database

SQLite / PostgreSQL

Tools

Jupyter Notebook
Docker
VS Code


📁 Project Structure
Book-Recommendation-System/
│
├── data/                    # Raw and processed datasets
├── notebooks/               # Jupyter notebooks for EDA and model development
├── backend/                 # FastAPI backend source code
│   ├── routes/
│   ├── models/
│   └── utils/
├── frontend/                # React frontend application
│   ├── src/
│   └── public/
├── models/                  # Saved ML models
├── app.py                   # Main application entry point
├── requirements.txt         # Python dependencies
└── README.md

📦 Dataset
Datasets are sourced from Kaggle and include:
FeatureDescription📗 Book DetailsTitle, ISBN, publisher✍️ AuthorsAuthor names and metadata🏷️ GenresGenre labels and categories⭐ User RatingsExplicit ratings (1–10 scale)📜 Reading HistoryUser reading activity logs

🤖 Machine Learning Techniques
👥 Collaborative Filtering
Recommends books by identifying patterns among users with similar tastes and rating behaviors.
📖 Content-Based Filtering
Recommends books based on item features:

Genre
Author
Publication Year
Book Description

🔀 Hybrid Recommendation
Combines collaborative and content-based signals to overcome individual limitations and deliver more accurate, diverse recommendations.

📊 Exploratory Data Analysis
EDA was performed using Pandas, Matplotlib, and Seaborn on the following dimensions:

📈 Book Popularity Distribution
⭐ Rating Distribution
👤 User Activity Patterns
🏷️ Genre Trends
✍️ Author Trends


🚀 Installation & Setup
1. Clone the Repository
bashgit clone <repository_link>
cd Book-Recommendation-System
2. Install Python Dependencies
bashpip install -r requirements.txt
3. Run the Backend
bashpython app.py
4. Run the Frontend
bashcd frontend
npm install
npm start

The backend API will be available at http://localhost:8000
The frontend will be available at http://localhost:3000


📐 Evaluation Metrics
The recommendation models are evaluated using the following metrics:
MetricDescriptionRMSERoot Mean Square Error — measures prediction accuracyMAEMean Absolute Error — average magnitude of prediction errorsPrecision@KFraction of top-K recommendations that are relevantRecall@KFraction of relevant items found in top-K recommendationsNDCGNormalized Discounted Cumulative Gain — measures ranking quality

🎯 Expected Outcomes

✅ Personalized recommendation engine
✅ Improved user reading experience
✅ Comparative analysis of recommendation algorithms
✅ Fully functional web-based recommendation platform


🔮 Future Enhancements

📱 Mobile application support
🧠 Deep learning-based recommendation models (Neural CF, Transformers)
⚡ Real-time recommendation updates
💬 User reviews and social sharing features


👩‍💻 Author
Gorrela Geetha Sri
B.Tech — Computer Science & Engineering
Lovely Professional University

📚 References

Collaborative Filtering Techniques
Content-Based Recommendation Systems
Hybrid Recommender Systems
Neural Collaborative Filtering (He et al., 2017)
Surprise Library Documentation
FastAPI Documentation
