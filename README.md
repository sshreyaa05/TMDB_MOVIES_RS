### TMDB Movie Recommendation System Using Multiple Approaches

### Project Overview:

The objective of this project was to build a comprehensive movie recommendation system using the TMDB dataset. We explored and implemented four different approaches for recommending movies:

1. Weighted Average Recommendation

2. Popularity-Based Recommendation

3. Normalization Score-Based Recommendation (with 50% priority to weighted average and popularity)

4. Content-Based Recommendation

The project began with Exploratory Data Analysis (EDA) to understand the dataset. Each recommendation approach was then applied, providing effective and personalized movie suggestions.

### Steps Performed:

#### Data Collection and Preprocessing:

1. Collected the TMDB movie dataset containing information on movies, ratings, and popularity.

2. Cleaned the data by removing duplicates and handling missing values.

3. Converted the dataset into a suitable format for analysis.

#### Exploratory Data Analysis (EDA):

1. Visualized key metrics such as movie ratings, popularity, and genres.

2. Analyzed the distribution of movies based on genres and release years.

3. Identified top-rated and most popular movies.

#### Weighted Average Recommendation:

1. Applied the weighted average formula using vote count and average rating to recommend movies.

2. Prioritized movies with higher vote counts to ensure reliable recommendations.

#### Popularity-Based Recommendation:

1. Recommended movies based on their popularity scores.

2. Provided trending and widely watched movie suggestions.

#### Normalization Score-Based Recommendation:

1. Combined the weighted average and popularity scores using a normalization approach.

2. Gave 50% priority to both metrics to balance quality and popularity.

3. Recommended movies using the calculated normalized scores.

#### Content-Based Recommendation:

1. Implemented a content-based filtering approach using movie descriptions and genres.

2. Used cosine similarity to measure the similarity between movies.

3. Recommended movies that were similar to a given movie based on content.

#### Evaluation:

1. Compared the recommendations from all four approaches.

2. Evaluated the relevance of recommendations using sample user scenarios.

3. Ensured that the recommendations met user preferences effectively.

### Results:

1. The weighted average approach provided reliable recommendations by focusing on highly-rated movies with substantial votes.

2. The popularity-based approach effectively highlighted trending and widely-watched movies.

3. The normalization score method balanced quality and popularity, giving well-rounded recommendations.

4. The content-based system delivered personalized recommendations based on movie descriptions and genres.

5. Overall, the combination of all four approaches enhanced the recommendation experience, offering diverse and accurate movie suggestions.
