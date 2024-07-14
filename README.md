von Samir Sadikovic

In this project, we analyzed, cleaned, and visualized datasets from WeRateDogs. We went through the essential steps of data wrangling, from gathering and assessing data to cleaning and final analysis. Here is a summary of our key steps and findings:

#### Data Gathering
We combined several data sources:
1. The original WeRateDogs Twitter archive dataset.
2. Image predictions of the dog images.
3. Additional tweet data via the Twitter API.

#### Data Assessment and Cleaning
During the data assessment, we identified and resolved several quality and tidiness issues:
1. **Missing Values**: We removed columns with many missing values that were not essential for analysis.
2. **Erroneous Datatypes**: We adjusted data types by converting `timestamp` to datetime objects and `tweet_id` to strings.
3. **Retweets and Replies**: We filtered out retweets and replies to keep only original tweets.
4. **Inconsistent Ratings**: We manually corrected some inconsistent ratings.
5. **Dog Stage Columns**: We combined the dog stage columns `doggo`, `floofer`, `pupper`, and `puppo` into a single `dog_stage` column.
6. **Incorrect Dog Breed Predictions**: We cleaned the dog breed names to ensure consistent and readable names.
7. **Non-Dog Images**: We filtered images to ensure only dogs were considered in our analysis.

#### Analysis and Visualization
We analyzed and visualized the cleaned data to gain interesting insights:
1. **Most Common Dog Breeds**: We identified and visualized the most frequently predicted dog breeds.
2. **Distribution of Ratings**: We analyzed and visualized the distribution of rating numerators.
3. **Relationship Between Retweets and Favorites**: We analyzed and visualized the correlation between retweet counts and favorite counts.

#### Key Findings
1. **Most Common Dog Breeds**: We found that certain dog breeds like Golden Retrievers and Labrador Retrievers are particularly common in the predictions.
2. **Distribution of Ratings**: The distribution of rating numerators shows that most dogs receive high ratings, reflecting the positive rating culture of WeRateDogs.
3. **Correlation Between Retweets and Favorites**: There is a strong positive correlation between the number of retweets and the number of favorites, indicating that popular tweets are both frequently favorited and retweeted.

#### Conclusion
This project highlighted the importance of data wrangling in analyzing social media data. By combining and cleaning multiple datasets, we were able to derive valuable insights and create meaningful visualizations. These methods and findings can be applied to similar projects to uncover deeper insights from data.

The project not only enhanced our data analysis and cleaning skills but also our ability to tell interesting stories from data. The visualizations and analyses provide a clear and understandable representation of popular WeRateDogs tweets and their characteristics.

Overall, this project demonstrates the power of data analysis and visualization in discovering patterns and trends in social media data.

---

