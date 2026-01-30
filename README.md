🎬 Movie Recommendation System using Collaborative Filtering
Project Overview
This project implements a Recommendation Engine that predicts user ratings for movies based on historical patterns. By utilizing User-Based Collaborative Filtering, the system identifies users with similar tastes and forecasts how a specific user would rate a film they haven't seen yet. This is a core technology used by platforms like Netflix and Amazon.

🚀 Key Features
Data Processing: Merges raw rating logs (u.data) with movie metadata (u.item) for a complete user-movie profile.

Similarity Modeling: Uses Cosine Similarity to compute a similarity matrix between 943 unique users.

Metric Analysis: Performance is validated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to ensure prediction accuracy.

Visual Analysis: Includes "Actual vs Predicted" distribution plots to verify the model's reliability.

Automated Export: Saves final results directly to movie_predictions.csv for easy viewing in Excel or other tools.

📊 Dataset Description
The project uses the MovieLens 100k dataset, which includes:

Ratings: 100,000 ratings (1-5 scale) from 943 users on 1,682 movies.

User ID: Unique identifier for each user.

Movie ID: Unique identifier for each film.

Metadata: Movie titles and genres.

🛠️ Installation & Setup
Clone the Repo:

Bash
git clone [https://github.com/AyeshaArshad-22/Movie-Recommendation-System-ML.git]
Install Requirements:

Bash
pip install -r requirements.txt
Run the Analysis:

Bash
jupyter notebook "Movie Rating Prediction.ipynb"
📂 Project Structure
Plaintext
├── u.data                      # User rating dataset
├── u.item                      # Movie metadata (titles/genres)
├── Movie Rating Prediction.ipynb # Main project notebook
├── movie_predictions.csv       # Exported results (CSV format)
├── requirements.txt            # List of Python dependencies
└── README.md                   # Project documentation
📜 License
This project is open-source and available under the MIT License
