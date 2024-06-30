# playstore_app_analysis

The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Each app (row) has values for category, rating, size, and more. Another dataset contains customer reviews of the android apps. Explore and analyse the data to discover key factors responsible for app engagement and success.

## Problem Statement

1. What is the distribution of the Rating, Size, and Price columns?
2. What is the distribution of the categorical columns in the Play Store dataset?
3. Is there any relationship between the number of Installs and the Rating, Size, or Reviews?
4. What is the average rating for each app category, and how do installs vary across different categories?
5. Do apps that update frequently have more installs?
6. Which type of app has more installs (free or paid), and which has the highest number of ratings and average size?
7. Which size range has the maximum number of installs and the highest average rating?
8. What are the top 20 apps having the most installs, the highest price, and the largest size?
9. Which categories of apps generate the most revenue, and which specific apps are the top revenue earners in these categories?
10. How does the number of apps vary across different categories over time?
11. How have app sizes and prices changed over time?
12. How does content rating affect the number of installs and price?
13. What is the distribution of Sentiment, Sentiment Polarity, and Sentiment Subjectivity?
14. What is the average Sentiment Polarity and Sentiment Subjectivity for each category?

## Variable discription

1. **App**: The name of the application.
2. **Category**: The category to which the app belongs (e.g., "GAME", "PRODUCTIVITY").
3. **Rating**: The average user rating of the app on a scale of 1 to 5.
Reviews: The number of user reviews the app has received.
4. **Size**: The size of the app
5. **Installs**: The number of times the app has been installed
6. **Type** : Indicates whether the app is free or paid ("Free" or "Paid").
7. **Price**: The price of the app (e.g., "0" for free apps, otherwise the price in a given currency).
8. **Content Rating**: The age group for which the app is appropriate (e.g., "Everyone", "Teen").
9. **Genres**: The genres of the app
10. **Last Updated**: The date when the app was last updated.
11. **Current Ver**: The current version of the app (e.g., "1.0.1").
12 **Android Ver**: The minimum required Android version to run the app (e.g., "4.1 and up").
13. **Translated_Review:** This column contains user reviews that have been translated into a common language to facilitate sentiment analysis and comparison.
14. **Sentiment:** This column indicates the overall sentiment of the review. It typically has categorical values such as "Positive," "Negative," or "Neutral," representing the general tone of the user's feedback.
15. **Sentiment_Polarity:** This column contains numerical values that quantify the sentiment polarity of the review. The values typically range from -1 to 1, where: -1 indicates very negative sentiment, 0 indicates neutral sentiment
and 1 indicates very positive sentiment.
16. **Sentiment_Subjectivity:** This column contains numerical values that quantify the subjectivity of the review. The values typically range from 0 to 1, where: 0 indicates a completely objective review (based on facts) and 1 indicates a completely subjective review (based on personal opinions)

## Data Visualisation
### 1. **What is the distribution of the Rating, Size, and Price columns?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/f7bed148-b7b7-4a1b-9b07-bfa0d5a8e797)

### 2. **What is the distribution of the categorical columns in the Play Store dataset**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/22958eee-eb88-425f-a264-d63c60e455db)

### 3. **Is there any relationship between the number of Installs and the Rating, Size, or Reviews?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/6746af91-5659-4acc-a9f2-7f1212bde46b)

### 4. **What is the average rating for each app category, and how do installs vary across different categories?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/817d3956-efff-4498-b614-a0d294cf6dfc)

### 5. **Which size range has the maximum number of installs and the highest average rating?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/e5cdefbf-e9ae-4c89-87f3-58eaa407504a)

### 6. **What are the top 20 apps having the most installs, the highest price, and the largest size?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/5af2bada-ad04-4a04-8f33-41c9953973b5)

### 7. **Which categories of apps generate the most revenue, and which specific apps are the top revenue earners in these categories?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/3fbed96b-cb35-4880-9590-321d07f568c6)

### 8. **How does the number of apps vary across different categories over time?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/6a4d4069-04d2-4d76-a2b6-404f2032d029)

### 9 **How have app sizes and prices changed over time?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/88c43b6e-cfbf-418b-b233-a0e806a0ca8f)

### 10 **What is the distribution of Sentiment, Sentiment Polarity, and Sentiment Subjectivity?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/023635c5-4955-4275-a0d5-cb6e49d214cf)

### 11 **What is the average Sentiment Polarity and Sentiment Subjectivity for each category?**
![image](https://github.com/AbhinavNautiyal123/playstore_app_analysis/assets/164336356/765949f1-3532-4cc6-b76d-3e77ce49e5b9)


## **Solution to Business Objective**

1. **Keep Ratings High**

  -   **Aim for Ratings**: Ensure your app has a rating between 4.0 and 4.5 by regularly improving it based on user feedback.
2. **Optimize App Size**

  -  **Stay Small**: Keep your app size under 20 MB for easy downloads. If necessary, go up to 60-80 MB but no more.

3. **Use Free Apps to Attract Users**

  -  **Free with Extras**: Offer your app for free and make money through ads, in-app purchases, or subscriptions.

4. **Target Popular Categories**

  -  **Focus on Popular Types:** Develop apps in the Family and Games categories since they are highly popular and growing.

5. **Keep Users Happy**

  -  **Good Experience:** Make sure users are satisfied by fixing issues quickly and adding new features regularly.

6. **Aim for High Revenue Categories**

  -  **Target Revenue:** Create apps in the Lifestyle and Games categories, which tend to make the most money.

7. **Boost Install Rates**

  -  **Get More Reviews:** Encourage users to leave positive reviews to attract more installs.

  -  **Regular Updates:** Update the app regularly to keep it running smoothly and retain user interest.

8. **Address Negative Feedback**

  -  **Fix Problems:** Pay attention to negative feedback and make improvements to address user concerns.

  -  **Engage with Users:** Respond to user comments and show that you are working to improve the app.

9. **Use Targeted Marketing**

  -  **Smart Advertising:** Advertise your app to the right audience based on their preferences and habits.

10. **Stand Out**'

  -  **Unique Features:** Add unique features that make your app different from others.
  -  **User-Friendly Design:** Ensure your app is easy and enjoyable to use.


## **Conclusion**

**High User Satisfaction**: Most apps are rated between 4.0 and 4.5, indicating high user satisfaction. Apps with high ratings also tend to have the highest number of installs.

**App Size and Downloads**: Smaller apps (0-20 MB) are more accessible and easier to download, leading to higher adoption rates. However, apps in the 60-80 MB size range tend to have the highest average installs, suggesting that users are willing to download larger apps if they offer valuable features.

**Free vs Paid Apps**: Free apps dominate the market in terms of number and downloads. They attract a larger user base, which can be monetized through in-app advertisements, subscriptions, or purchases.

**Genre Popularity**: The Family, Games, and Tools categories have the most apps and highest installs. These categories show strong user engagement and satisfaction.

**Revenue Insights**: The Lifestyle, Family, and Game categories generate the highest revenue. High-priced, niche apps and popular games are top revenue generators.

**Sentiment Analysis**: Most user reviews are positive, with a notable portion of negative sentiments. Categories like Food & Drink and Health & Fitness have the highest average sentiment polarity, while Maps & Navigation and News & Magazines have lower polarity.
















