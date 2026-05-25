# Movie Recommendation System (Content-Based)

A smart recommendation engine that suggests movies to users based on their personal preferences and movie genres using Content-Based Filtering.

### 🚀 How it Works & Setup
```bash
# 1. PROJECT GOAL:
# - Build a recommendation engine that understands user's taste in genres.
# - Recommend top movies that the user is likely to enjoy.

# 2. MACHINE LEARNING WORKFLOW:
# - Data Cleaning: Extracting release years and splitting genres into lists.
# - One-Hot Encoding: Converting genres into a binary matrix (0s and 1s).
# - User Profile: Creating a weighted profile based on user's movie ratings.
# - Scoring: Calculating a recommendation score for all movies.
# - Ranking: Sorting and displaying the top 20 movies with the highest scores.

# 3. REQUIREMENTS:
pip install pandas numpy matplotlib

# 4. QUICK START:
# - Ensure 'movies.csv' and 'ratings.csv' are in the project folder.
# - The script uses Regex to clean movie titles and process genres.
# - Run the code to see the top recommended movies for the sample user.

# 5. KEY TECHNIQUE:
# - This model uses 'Weighted Average' of genres. If a user likes 'Sci-Fi' 
#   and 'Action', the system prioritizes movies with those specific tags.
