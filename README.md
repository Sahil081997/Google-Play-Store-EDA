# Google-Play-Store-EDA
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Creating business insights by performing EDA on Google Playstore Data set using Pandas, Numpy, Matplotlin, Seaborn in Python.

Conclusion
In this project of analyzing play store applications, we have worked on several parameters which would help AlmaBetter to do well in launching their apps on the play store.

In the initial phase, we focused more on the problem statements and data cleaning, in order to ensure that we give them the best results out of our analysis.

AlmaBetter needs to focus more on:

Developing apps related to the least categories as they are not explored much. Like events and beauty.
Most of the apps are Free, so focusing on free app is more important.
Focusing more on content available for Everyone will increase the chances of getting the highest installs.
They need to focus on updating their apps regularly, so that it will attract more users.
They need to keep in mind that the sentiments of the user keep varying as they keep using the app, so they should focus more on users needs and features.
Challenges & Future Work
Our major challenge was data cleaning.
13.60% of reviews were NaN values, and even after merging both the dataframes, we could not infer much in order to fill them. Thus we had to drop them.
The merged data frame of both play store and user reviews, had only 816 common apps. This is just 10% of the cleaned data, we could have given more valuable analysis, if we had atleast 70% - 80% of the data available in the merged dataframes.
User Reviews had 42% of NaN values, which could have been used for developing an understanding of the category wise sentiments, which would help us to fill 13.60% NaN values of the Reviews column.
There is so much more which can be explored. Like we have current version, android version available which can be explored in detail and we can come out with more analysis where we can tell how does these things effect and needs to be kept in mind while developing app for the users.
We can explore the correlation between the size of the app and the version of Android on the number of installs.
Machine learning can help us to deploy more insights by developing models which can help us interpret even more better. We have left this as future work as this is something where we can work on.
