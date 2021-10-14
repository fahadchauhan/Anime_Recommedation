# Anime_Recommedation
1) Content-Based: selected features were converted into embedding using FASTTEXT, and cosine similarity to pick the top 10 similar anime.

2) Collaborative Based Filtering: Ensemble of Random Forest Regressor (RGR) and Gradient Boosted Regressor (GBR) were used to rank animes based on how users have given ratings before. evaluation metrics were Mean square error (MSE) and Mean absolute error (MAE).

3) Content + Collaborative - Hybrid: Based on the top 10 animes watched by the user, recommend top a10 anime after removing duplicates and already watched anime.

Bonus: Handled the Cold-start problem, by recommending top 10 animes in the data to the new user.

metadata.txt -- metadata of the dataset

Find the dataset in the link: https://drive.google.com/drive/folders/1g1BscQS7L985q7wLtSzMBpL0mVXxULel?usp=sharing
