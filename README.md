# PersonalizedRecommendationSystem
A simple Java-based system for recommending items to users based on their ratings and user similarity.

## Features
- Allows users to rate various items.
- Calculates similarity between users using their common item ratings.
- Recommends items to a user by leveraging user similarity and ratings of other users.

## How It Works
1. **User Ratings**: Users can rate items with a score (e.g., between 1.0 and 5.0).
2. **User Similarity**: Similarity between users is calculated using cosine similarity, considering common items rated by both users.
3. **Item Recommendation**: Items that the target user has not rated are recommended based on ratings and similarity of other users.
