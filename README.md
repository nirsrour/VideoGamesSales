Background:
The video game industry is dynamic and highly competitive, with countless titles released each year across various platforms and genres. To succeed in this space, it's essential for publishers and developers to have a deep understanding of market dynamics, including sales trends, popular genres, and effective platforms for distribution.

Project Objectives:
Analyze global video game sales data (from Kaggle) to identify key trends and patterns.
Determine the most influential factors affecting game sales, such as genre, platform, and region.
Explore market share among game publishers to understand the competitive landscape.
Segment games into different sales categories for targeted analysis.
Create predictive models to estimate global game sales based on available data.

Project Challenge:
Navigating the vast and intricate landscape of video game sales data presented a significant challenge. Managing a dataset with missing values and diverse attributes required meticulous data preprocessing. Additionally, interpreting complex correlations and high cardinality features while building predictive models demanded a combination of statistical expertise and machine learning proficiency.

Dealing with a large and diverse dataset with missing values.
Identifying meaningful correlations between variables to derive valuable insights.
Handling high cardinality features like genres and publishers.
Creating accurate predictive models to estimate sales.
Extracting actionable insights from complex sales data.
Initial insights
The data set contains mostly nominal and ordinal values, which can be challenging for certain machine learning algorithms.
Unsupervised learning was chosen for this project.
The data set used in this project is relatively small, and it only includes video games that have sold over 100,000 copies. This means that the results of the analysis may not be generalizable to all video games.

Solutions:
To tackle these challenges, I employed various data analysis and modeling techniques. I cleaned the dataset, visualized correlations, and used both linear regression and machine learning algorithms like K-Means clustering to gain insights. I also considered one-hot encoding for categorical features and performed in-depth statistical analyses.

Data preprocessing:
Irrelevant data, such as the "RANK" column and null values, were removed.
Records with dates after 2017 were excluded, as the data set was created in 2017.
Methods
Linear regression was used to compare the "North America Sales" and "Global Sales" columns. However, the linear regression algorithm did not adequately capture the non-linear trends in the data.
Decision tree regression was used to predict "Global Sales" based on the other features in the data set. The decision tree model was able to follow the non-linear trends in the data better than the linear regression model


Results:

My analysis revealed several key findings:

The decision tree regression model was able to predict "Global Sales" with reasonable accuracy. The model could be used to identify video games that are likely to sell well, which could be helpful for game developers and publishers.
The genre and platform of a game significantly impact its sales.
Some publishers dominate the market, while others have a smaller but dedicated share.
Clustering helped me identify games with low, medium, and high sales potential.
Linear regression models provided insights into the relationship between variables and sales.
Extracting actionable insights from complex sales data.
These findings offer valuable insights for game developers, publishers, and marketers, helping them make data-driven decisions in the competitive video game industry.
