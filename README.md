# Netflix-Movies-and-TV-Shows-Clustering-using-KNN

We all watch a lot of TV shows. Who doesn’t love to spend some free time on the
weekend?

Many online streaming services offer a large number of TV shows, which are at our disposal to watch, at the price of a subscription cost. The major online streaming
services across the world are Netflix, Prime Video, Hulu, and Disney+.

Netflix is an American technology and media services provider and production company headquartered in Los Gatos, California. Netflix was founded in 1997 by Reed
Hastings and Marc Randolph in Scotts Valley, California. 

The company’s primary business is its subscription-based streaming service, which offers online streaming of a library of films and television series, including those produced in-house. Their most successful algorithm, Netflix Recommendation Engine (NRE), is made up of algorithms which filter content based on each individual user profile. 

The engine filters over 3,000 titles at a time using 1,300 recommendation clusters based on user preferences. It’s so accurate that 80% of Netflix viewer activity is driven by personalized recommendations from the engine.


In this project, we'll do:

1. Exploratory Data Analysis
2. Understanding what type content is available in different countries
3. Is Netflix has increasingly focusing on TV rather than movies in recent years.
4. Clustering similar content by matching text-based features
 
The given dataset contains a large number of TV shows from the Netflix streaming
services. Regarding, the features, the dataset contains:

12 columns and 7787 rows. The 12 Variables are as follows:

1. show_id : Unique ID for every Movie / Tv Show
2. type : Identifier - A Movie or TV Show
3. title : Title of the Movie / Tv Show
4. director : Director of the Movie
5. cast : Actors involved in the movie / show
6. country : Country where the movie / show was produced
7. date_added : Date it was added on Netflix
8. release_year : Actual Releaseyear of the movie / show
9. rating : TV Rating of the movie / show
10. duration : Total Duration - in minutes or number of seasons
11. listed_in : Genere
12. description: The Summary description

Netflix is a popular entertainment service used by people around the world. In this
project, we will explore the Netflix dataset through visualizations, graphs using python
libraries and clustering model building.

As the first step, performed data exploration over the first dataset. Data exploration
consists of reading data, checking data types of data, a summary of data, and the shape
of the data.

The second step was checking and handling null / missing values in the dataset and got
more than 3000 null / missing values. Then started with the data cleaning process by
removing outliers from the dataset, using the fillna method to fill missing data in the
dataset.

The third step was performing Exploratory Data Analysis (EDA) on the dataset.
Exploratory Data Analysis is a process of examining or understanding the data and
extracting insights or main characteristics of the data.

Types of EDA are:

Univariate Analysis - analysis of a single variable
Bivariate Analysis - analysis of exactly two variables
Multivariate Analysis - analysis of dependent variable and multiple independent
variables

After performing EDA on the given dataset, I have concluded some inferences:

1) The largest count of movies is made with the 'TV-MA' rating. "TV-MA" is a rating assigned
by the TV Parental Guidelines to a television program that was designed for mature
audiences only.
2) Highest number of movies released in Netflix was in the year 2017 and 2018
3) Highest number of Tv shows released in Netflix was in the years 2018, 2019, and 2020.
4) The months of October, November, December and January had the largest number of films
and television series released.
5) In the given years we have seen in the month of Feb, may less movies was released so
producer can release on this months
6) There are about 70% movies and 30% TV shows on Netflix.

The fourth step was changing categorical variables into numerical by feature reduction and feature engineering by one hot encoding.

The fifth step was model building using clustering model.

The sixth step was testing k-means clustering model.

The seventh step was plotting word cloud to check frequent words used in description, cast, and many more categories of movies/show.

The eighth step was concluding the project
