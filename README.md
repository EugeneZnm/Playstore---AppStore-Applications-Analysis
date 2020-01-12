# Playstore---AppStore-Applications-Analysis
The main aim of the project is to find mobile app profiles that are profitable for the App Store and Google play markets. 
The analysis is to enable the making of data driven decisions with respect to the kind of applications to build,from an 
economic standpoint. The target applications to be built are largely free to to download and install with their main revenue streams being in app ads. 
This means that the revenue for any given application is mostly influenced by the number of users that use an application. 
The goal of the poject is to analyse data to help developers understand what kinds of appls are likely to attract more users.

## Language Used: 
- Python
## Environment
- Jupyter Notebook

## Opening and Exploring the Data

As of September 2018, there were approximately 2 million iOS apps available on the App Store, and 2.1 million Android apps on Google Play.

Collecting data for over four million apps requires a significant amount of time and money, so we'll try to analyze a sample of data instead. To avoid spending resources with collecting new data ourselves, we should first try to see whether we can find any relevant existing data at no cost. Luckily, these are two data sets that seem suitable for our purpose:

- [A data set](https://www.kaggle.com/lava18/google-play-store-apps)containing data about approximately ten thousand Android apps from Google Play. You can download the data set directly from [this link](https://dqcontent.s3.amazonaws.com/350/googleplaystore.csv).

- [A data set](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps) containing data about approximately seven thousand iOS apps from the App Store. You can download the data set directly from [this link](https://dqcontent.s3.amazonaws.com/350/AppleStore.csv).

# Removing Non-English Apps

Removal of applications that are not Enlgish based. The ord() function was used to eliminate characters of a corresponding numerical value higher than the maximum 127 in the ASCII

# Determination of Most Common Apps By Genre

Determining the kinds of apps that are more attractive to users by finding out the most common genres in both markets.

Building Frequency Tables for the prime_genre column of the App_Store dataset and Genre and Category columns of the Google Play dataset

Tasks:
- Generation of Frequency tables that show percentages
- Creation of a function used to display the percentages in descending order

# Examination of the frequency table for prime_genre column of the App Store dataset

59% of the applications are games, 7.5% are Entertainment focused, 5% are photo and video applications with education and social networking having 3.8% and 3.1% respectively.

Most of the free English applications in the App Store are dominated by applications designed for games, entertainment, photo and video, social networking and shopping.

However this is indicative only of the supply of applications across genres and not of their demand by users across the genres, in the App Store.

#Determination of Most Popular Apps by Genre on App Store

This can be discovered by calculating the average number of installs for each app genre. In the google play data set, the figures are found in the Installs column. However in the App Store data, the data is missing but we can use user ratings to determine popularity.

# Determination of Most Popular Apps by Genre on Google Play

Getting a clear picture about genre popularity of applications in the Google Play Store.

# Conclusion

The project was centered around analysing data about the App Store and Google Play mobile apps with the goal of recommending an app profile that can be profitable for both markets.

The conclusion was that taking a popular book (perhaps a more recent book) and turning it into an app could be profitable for both the Google Play and the App Store markets. The markets are already full of libraries, so we need to add some special features besides the raw version of the book. This might include daily quotes from the book, an audio version of the book, quizzes on the book, a forum where people can discuss the book, etc.
