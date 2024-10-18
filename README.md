# Beer-Analysis-Project
This project aims to see what attributes make a highly rated beer. This project was done as part of a collage assignment for data science, but also offers a unique look on beer data from as resent as 2021
The specifics of the data used were all downloaded from Kaggle. As of 10/16/2024 the app only analyses 2 different data sets that were merged into one data set called beer_df.csv. 
The two data sets used were a list of beer and beer rankings from 2021 scraped from the website Beer Advocate, and beer recipes scraped from the website brewers’ friend from 2016. 
The backbone of the project data comes from the beer advocate data set. All the beers shown, their rankings, and attributes all originate from this dataset. 
The brewer’s friend data contains less data on beer flavor profiles but contains a much larger list of beer and beer measurement information. The beer recipe data information was averaged into beer styles and merged with the beer advocate data according to beer style. 
When merging the data, the style names from both data sets were not 1:1 with each other so I had to align the beers together using string matching scores and manually correcting incorrect matches with the closest available style on the list. 
The final product was beer_df.csv which uses the beer advocate data as an anchor and the beer style means and variance from the beer recipe data to fill in some of the missing information from the former data set.
I also had to impute some of the missing values from the beer advocate data to create beer_df.csv but most of the data from beer advocate was present so little of the data is synthetic.
One last important note; When using the beer app and it asks you to enter in a name of something, the name has to be the exact name as it appears on the table. 
If you have beer in mind and are unsure of the beer’s exact name, I suggest you enter the name into the search bar on the data table and copy the exact name of the beer from the table, or you can google the beer name and copy the exact name from the beer advocate website.
Overall, this is my first coding project, and I expect some bugs or suboptimal code in the source so keep this in mind. As of 10/16/2024 I might revisit this project to add more data but don’t get your hopes up if you plan on following this project.
