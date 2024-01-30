 PART I:
 EDA & Data Preprocessing on Google App Store Rating Dataset.
 Domain:Mobile device apps
 Context:
 The Play Store apps data has enormous potential to drive app-making businesses to success. However, many
 apps are being developed every single day and only a few of them become profitable.  It is important for
 developers to be able to predict the success of their app and incorporate features which makes an app
 successful. Before any such predictive-study can be done, it is necessary to do EDA and data-preprocessing on
 the apps data available for google app store applications.  From the collected apps data and user ratings from
 the app stores, let's try to extract insightful information

 Questions:
Min required Android Version.
 1. Import required libraries and read the dataset.
 2. Check the first few samples, shape, info of the data and try to familiarize yourself with different features.
 3. Check summary statistics of the dataset. List out the columns that need to be worked upon for model
 building.
 4. Check if there are any duplicate records in the dataset? if any drop them.
 5. Check the unique categories of the column 'Category', Is there any invalid category? If yes, drop them.
 6. Check if there are missing values present in the column Rating, If any? drop them and and create a new
 column as 'Rating_category' by converting ratings to high and low categories(>3.5 is high rest low)
 7. Check the distribution of the newly created column 'Rating_category' and comment on the distribution.
 8. Convert the column "Reviews'' to numeric data type and check the presence of outliers in the column and
 handle the outliers using a transformation approach.(Hint: Use log transformation)
 9. The column 'Size' contains alphanumeric values, treat the non numeric data and convert the column into
 suitable data type. (hint: Replace M with 1 million and K with 1 thousand, and drop the entries where
 size='Varies with device')
 10. Check the column 'Installs',  treat the unwanted characters and convert the column into a suitable data type.
 11. Check the column 'Price' , remove the unwanted characters and convert the column into a suitable data type.
 12. Drop the columns which you think redundant for the analysis.(suggestion: drop column 'rating', since we
 created a new feature from it (i.e. rating_category) and the columns 'App', 'Rating' ,'Genres','Last Updated',
 'Current Ver','Android Ver' columns since which are redundant for our analysis)
 13. Encode the categorical columns.
 14. Segregate the target and independent features (Hint: Use Rating_category as the target)
 15. Split the dataset into train and test.
 16. Standardize the data, so that the values are within a particular range.
     PART II:
 Data Visualization on Honey Production dataset using seaborn
 and matplotlib libraries.
 Domain:Food and agriculture
 Context:
 In 2006, a global concern was raised over the rapid decline in the honeybee population, an integral component
 to American honey agriculture. Large numbers of hives were lost to “Colony-Collapse-Disorder”, a
 phenomenon of disappearing “worker-bees” causing the remaining “hive-colony” to collapse. Speculation
 around the cause of this disorder points to hive-diseases and pesticides harming the pollinators, though no
 overall consensus has been reached. Twelve years later, some industries are observing recovery but the
 American honey industry is still largely struggling. The U.S. used to locally produce over half the honey it
 consumes per year. Now, honey mostly comes from overseas, with 350 of the 400 million pounds of honey
 consumed every year originating from imports. This dataset provides insight into honey production supply and
 demand in America by state from 1998 to 2012.
 Objective:
 The Goal is to use Python visualization libraries such as seaborn and matplotlib to investigate the data and get
 some useful conclusions

Questions:
1. Import required libraries and read the dataset.
 2. Check the first few samples, shape, info of the data and try to familiarize yourself with different features.
 3. Display the percentage distribution of the data in each year using the pie chart.
 4. Plot and Understand the distribution of the variable "price per lb" using displot, and write your findings.
 5. Plot and understand the relationship between the variables 'numcol' and 'prodval' through scatterplot, and
 write your findings.
 6. Plot and understand the relationship between categorical variable 'year' and a numerical variable
 'prodvalue' through boxplot, and write your findings.
 7. Visualize and understand the relationship between the multiple pairs of variables throughout different years
 using pairplot and add your inferences. (use columns 'numcol', 'yield percol', 'total prod', 'prodvalue','year')
 8. Display the correlation values using a plot and add your inferences. (use columns 'numcol', 'yield percol',
 'total prod', 'stocks', 'price per lb', 'prodvalue'
