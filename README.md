![alt text](https://github.com/algerza/supermarket_recommendation_system/blob/main/cover.jpg?raw=true)

# Supermarket E-Commerce Recommendation System

### What is this project about?
The online grocery market is becoming increasingly competitive, with users expecting fast, relevant, and personalized recommendations to enhance their shopping experience. Supermarkets need to understand not just what customers are buying, but why they buy — whether it’s price sensitivity, dietary preferences, or environmental awareness.

In this project, I build a recommendation engine tailored for supermarkets and grocery retailers. The system analyzes customer purchase behavior and product features to recommend relevant products to different customer segments (e.g. budget shoppers, families, vegans, eco-conscious consumers). This helps improve customer retention, boost basket sizes, and personalize promotions. I simulate this environment using a synthetic dataset that mimics real-world online grocery behavior — designed for testing and experimentation.

### Project structure
0. Load and explore the data
1. Cluster customers in similar groups based on their purchase behaviour
2. Explore clusters characteristics and visualise them
3. Create a hybrid recommendation system (what user bought in the past + what similar users have purchased) that recommends diverse products (i.e. only 1 product per sub-category to avoid recommending 5 different types of milk)
4. Test different scenarios for the recommendation system (i.e. existing user that hasn't added products to cart yet; existing user added specific products to cart; new user...)
5. Check for potential data drift on new data