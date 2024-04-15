# Movie-Industry-Correlations-Using-Python
 The dataset comprised diverse data types, with text-based attributes like name, rating, and genre, alongside integer values in the year column and numerical data encompassing score, votes, budget, gross earnings, and runtime.
The movie industry spans various genres and cultural narratives, evolving with technology and societal shifts. From Hollywood blockbusters to indie gems, cinema captivates audiences globally, serving as a universal language through the magic of film.

Harnessing the power of data analysis, I delved into the complex network of correlations within the movie industry using Python, leveraging a dataset sourced from Kaggle to gain insights.

To begin, I imported essential libraries and meticulously cleaned the dataset, addressing null values and eliminating duplicates. Notably, around 28% of entries lacked budget information, while approximately 2% lacked gross earnings data.

Focusing on the relationship between gross earnings and budget, I observed that the movie "Avatar," released in 2019, emerged as the highest-grossing entry in the dataset. Visualizing this correlation via a scatter plot, the significant impact of budget on gross earnings became evident.

Further analysis via Pearson and Kendall correlations revealed intriguing insights. Notably, a moderate positive correlation (approximately 0.560449) between votes and gross earnings emerged, indicating that higher vote counts tend to align with increased movie earnings. Additionally, a weak positive correlation (approximately 0.300115) between movie ratings and vote counts suggested that well-rated films attract more audience engagement.

To enhance visualization, a heatmap was generated, reinforcing the observed correlations.

Contrary to initial assumptions, factors like company affiliation exhibited lesser correlation compared to variables such as votes, gross earnings, and budget. Notably, votes displayed a strong correlation of 0.632870 with gross earnings, while budget exhibited a robust correlation of 0.750157, underscoring their significance in predicting movie success.

In conclusion, my exploration of correlations within the movie industry using Python and a dataset from Kaggle has provided valuable insights into the factors influencing movie success.
I discovered that while the movie landscape is diverse and ever-evolving, certain trends and relationships remain consistent. Factors such as budget and audience engagement, as measured by votes, demonstrate strong positive correlations with gross earnings. This suggests that investing in production quality and marketing efforts can significantly impact a movie's financial performance.
Overall, this analysis underscores the power of data in understanding the complex dynamics of the movie industry, offering filmmakers, studios, and industry stakeholders valuable insights for informed decision-making and strategic planning.
