# Google Play Store Apps Analysis

![](https://media.tenor.com/8gXeiN5vTqEAAAAC/google-play-apps-google-play-services.gif)

This repository contains an exploratory data analysis (EDA) project focused on analyzing Google Play Store apps data. The Play Store is a significant platform for Android app developers, offering vast potential for app-making businesses to thrive. By extracting actionable insights from the available data, developers can gain valuable knowledge to capture the Android market successfully.

## Problem Statement
The objective of this project was to perform a comprehensive analysis of the Google Play Store, addressing various problem statements to gain insights into app categories, ratings, content ratings, sentiments, genres, pricing, size, and correlations between different variables. By analyzing these aspects, the project aimed to provide valuable insights for app developers and stakeholders to make informed decisions in the highly competitive app marketplace.

## Summary and Conclusion
Google Play Store is renowned as one of the largest and most popular Android app stores worldwide. With its extensive collection of apps and a wealth of data, it presents an optimal opportunity for creating effective models and identifying trends and future challenges.

In this EDA project, we utilized two raw datasets from Kaggle: one containing Play Store attributes and the other consisting of user reviews. The first dataset encompasses 13 different attributes, while the second dataset provides five additional features for data manipulation and analysis.

To ensure data integrity, we began by performing crucial data cleaning steps. This involved removing duplicate entries and dropping non-essential null values. However, due to a large number of null values in the rating column (1645), dropping them entirely would have adversely affected our final results. Therefore, we replaced these null values with the mode of ratings.

After cleaning the data, we conducted exploratory data analysis to gain a comprehensive understanding of our dataset. This involved various analyses, such as examining the number of installations for each category and exploring the correlation between app size, Android version, and the number of installs. 

Furthermore, we merged both dataframes to discover correlations between the columns of the two datasets, which yielded fascinating results.

Key insights and conclusions drawn from our analysis include:

- There is a positive correlation between the number of reviews and the number of installs, meaning that as the number of installs increases, it is more likely that 
  users will leave reviews. Conversely, there is a negative correlation between price and rating, indicating that higher-priced apps tend to have lower ratings.
- Art and design have the most number of installs.
- Developing apps in the Family and Lifestyle categories can be a strategic choice for maximizing profitability and generating high revenue.

- Approximately 61% of people expressed positive sentiments, while a relatively low percentage of around 15% reacted negatively. The majority of the remaining 
  respondents had a neutral sentiment.

- Out of the total number of apps, approximately 92.12% are free, while around 7.81% are paid, indicating a significant majority of apps being offered for free 
  compared to paid alternatives.

- The "Everyone" content rating, which encompasses all age groups, has the highest percentage of apps, accounting for approximately 81.80% of the total.

- The Family, Game, and Tools categories have the highest number of apps, indicating that these categories contain a significant portion of the total app offerings.
- Game category presents a promising opportunity for developers as it demonstrates a high demand with a large number of installs, suggesting that it is an area with 
  potential for growth and where competition may not be as saturated.
- Users have a strong inclination towards downloading apps from genres such as Tools, Entertainment, Education, Business, and Medical, indicating a high level of 
  interest and demand for apps in these categories.

- The average rating of apps available on the Play Store is a commendable 4.17, indicating a generally positive reception from users. When it comes to purchasing 
  apps, users tend to show a preference for lightweight applications, indicating a willingness to pay for apps that have a smaller file size or consume less device 
  storage.

- Paid apps with larger file sizes may face challenges in the market and may not achieve optimal performance.The presence of a large number of user reviews 
  positively influences the download frequency of a given app, indicating that users are more likely to download an app that has received a substantial number of 
  reviews.

  Users tend to provide more critical reviews for paid apps.

- There is a positive relationship between the number of installs and the app rating.

- Developing an app that achieves a high rating requires regularly updating it with the latest version while ensuring it remains optimally sized.

- Developing a free app with a content rating suitable for all age groups is a favorable approach.

- By successfully achieving our project objectives and answering our research questions, we have obtained valuable insights into the Google Play Store apps ecosystem and the trends within.

## Summary and Conclusion
To achieve our business objectives, we need to strategically address the key findings and conclusions derived from our analysis. Based on the provided insights, we have identified several actionable solutions.

- Firstly, we should focus on capitalizing on the popularity of the Art and Design category, which has the highest number of installs. By allocating our resources 
  and efforts towards developing high-quality apps in this category, we can tap into the existing demand and attract a larger user base.

- In addition, the Family and Lifestyle categories present a promising opportunity for maximizing profitability and generating high revenue. By identifying specific 
  niches within these categories and developing tailored apps that cater to the needs and preferences of the target audience, we can position ourselves for success.

- To ensure positive sentiment and maintain a good reputation, it is crucial to encourage users to leave reviews and ratings. Positive reviews not only enhance our 
  app's credibility but also influence the download frequency. We must also address negative feedback promptly to improve user satisfaction and continually enhance 
  the quality of our apps.

- Considering that the majority of apps are offered for free, we should optimize our freemium model. By offering a free version of our app with additional paid 
  features or in-app purchases, we can attract a larger user base and increase the likelihood of generating revenue.

- Furthermore, developing apps with content suitable for all age groups can widen our target audience. We should ensure compliance with content rating guidelines 
  and provide a safe and inclusive experience for users of all ages.

By initiating these actions based on the insights obtained, we can steer our business towards success and stay competitive in the dynamic app market.
**************************************************************************************************************************************************
For complete project video explaination and to downoad the dataset: [Click here](https://drive.google.com/drive/folders/1Bo2o9vJEHNhZI3bZdueY0adI_mag6ae8?usp=sharing)

Feel free to explore the repository to gain further insights into the code implementation, methodology, and findings.

Connect with me on [Linkedin](https://www.linkedin.com/in/vibhuti-gupta-131336232/).

Happy Learning!
**************************************************************************************************************************************************
