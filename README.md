# ETL_Francisco_Ian_Scotty


Project Outline:IntroOur group decided to tackle the logistics industry. We will perform an ETL process forMaxianet’s international operations. Maxianet helps brands create new revenue in foreignmarkets. We distribute various consumer goods to countries in North America, Central America,South America, Europe, Africa and Asia. Our focus is on volume and market leadership. For thisproject we will narrow our scope to Ecuador and the USA. The ETL will yield a centralized dataframe from which the company will be able to query much more effectively.

Once you have identified your datasets, perform ETL on the data. Make sure to plan anddocument the following:
●The sources of data that you will extract from.
  -United States Craft Beer Brand Data
  -Mexico Craft Beer Brand Data
●The type of transformation needed for this data (cleaning, joining, filtering, aggregating,etc).
  -Clean out N/A values by normalizing and/or setting data to 0
  -Joining the two tables
  -Web scraping
●The type of final production database to load the data into (relational or non-relational).
-MongoDB
●The final tables or collections that will be used in the production database.
-Normalized tables based on Location of Audit.
-From the United States our non
-normalized data has these columns:Submission, Date, Longitude, Latitude, Location, User, (Brand1-14): Brand,Product, Size, Measurement of Size, amount per pack, Price.
An Example of Data would be:Submission_Url"​: ​"/submissions/2546649/webview"​, ​"Date"​: ​"('12:25 PM - Wed, Feb 26,2020',)"​, ​"Lng"​: ​"-117.07549"​, ​"Location"​: ​"Baron​\u2019​s Market Rancho Bernardo"​,"Lat"​: ​"33.0238279"​, ​"Add1"​: ​"Scotty Smith"​, ​"User"​: ​"Add New Brand"​, ​"Brand_1"​:"Nova"​, ​"Product_1"​: ​"Easy Kombucha "​, ​"Size_1"​: ​"16.0"​, ​"Size1"​: ​"OZ"​, ​"size12"​: ​""​,"Price_1"​: ​"3.99"

However the brands can be up to 14 entries and varies. This is the part that will be normalizedto the Location.
From Ecuador our normalized data has these columns:Submission_Url, Date, Lng, Lat, Location Name, User, Kind of Audit, Over 10 tap lines?,You will be required to submit a final technical report with the above information and stepsrequired to reproduce your ETL process.

WorkFlow:

Task 1:-Scotty: Share with the guys an explanation of scraping the website, since it is not aseasy as normal. Share with them how you did United states, so they can reference indocument.-Upload all scripts.
Task 2: Francisco: Scrape Mexico for all submission Id’s.Task 
3: Francisco: Create Dataframe from Scrape.
Task 4: Ian, Scrape Each submission based on francisco scraping Id’sTask 
5: Scotty: Clean original againTask 6: Join (Ian)Task 
7: Scotty NormalizeTask 
8: Make Data Json file to push to Mongo Db. (All)
Task 9: Post to Mongo DB (All)Task 10: Create Word Document: (All)
