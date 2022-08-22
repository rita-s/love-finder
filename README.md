# 💌 How to find love? 
<img src="https://github.com/rita-s/love-finder-/blob/master/images/project_photo.png" alt="Project Photo" title="Project Photo" width="30%">

## Extract - Transform - Load Pipeline Project to prepare data for analysis of the most popular dating apps & dating strategies.

## 📝 Project Description
### You are single and are looking for love.
In XXI century, in the times of COVID-19 global pandemic and frequent lockdowns, chances are you would consider using a dating site / app. Which one will you go for? Which app has most users? Which has the best rating? What attributes people look for in their “second – half”? Does your age matter? How many people of your age are going to use the app? How big chances do you have to be successful? 

### The lockdown is off, and you can finally meet!
How to make a good impression and secure your second date? Should you even try to do that? Maybe being sincere is the best strategy? What traits of yours will bring you success / failure?

### To answer above questions, building an ETL pipeline is useful to make the data ready for the analysis.

## 💼 ETL Report
Extract - Original Data Sources:
* Two unrelated datasets from Kaggle were used: “Speed dating” and “Dating apps reviews” - both datasets were in CSV form
* Dating Advice website was scrapped for “Dating sites with most users” - website converted into html template for the ease of use

Transform:
* CSV files were cleaned and filtered to remove everything that is not relevant (e.g. data from earlier period than 2020, unnecessary columns, missing values etc.) by using Python and pandas
* Beautiful Soup was used to perform webscrapping

Load:
* Data was loaded into the Mongo Database
* MongoDB was chosen as the data is not related, so there is no reason to use relational database such as e.g., PostgreSQL.

## 📚 References:
1. 24 Dating Sites With the Most Users: https://www.datingadvice.com/online-dating/dating-sites-with-the-most-users
2. Speed Dating Analysis: https://www.kaggle.com/datasets/somesh24/speeddating
3. Dating Apps Reviews 2017-2022: https://www.kaggle.com/datasets/sidharthkriplani/datingappreviews


