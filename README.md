## Mobile Game Analytics
### Business Questions 
--- 
#### 1. Short Description of the Data set 
The database contains three datasets: account, account_date_session, and iap_purchase. 
* **Account** dataset:
    * The ‘account’ table includes user profiles, including users’ unique account ID, datetime they created a game account, country code, devices they used, and some other relevant information.
    * According to the dataset, there are 112 792 users, of which 107 users have country information missing. The country information is important for sales by geography analysis. 
*	**Account_date_session** dataset:
    *	The dataset contains the number of sessions for the users for the days they have been active. The session does not count when the user created an account.
    *	There is no abnormal about the dataset. 
*	**iap_purchase** dataset:
    *	The dataset contains in-app purchases by users.
    *	There are 2 paying users that are missing geographic information. Luckily, they only made up 20 euros purchase. 
#### 2. Analyzing the Daily Active Users (DAU)
* The chart depicts the Daily Active Users (DAU) and its components—new users and returning users—over a specified time period. Notably, there is a significant surge in DAU from the start of the year until mid-February 2016. 
* The reason for the sudden decrease in the DAU might be: 
   -	Technical issues.
   -	Game updates or changes 
   -	User burnout or fatigue.
![Daily Active Users](./images/DAU-Analysis.png)
#### 3. Revenue Split by Country

![Daily Active Users](./images/revenue-split-by-country.png)

* In 2016, the total revenue amounted to $45,518.62. The dataset exhibits no abnormalities. Notably, the range of in-app purchases spans from a minimum of 36 cents to a maximum of $40, demonstrating a diverse range of transaction values within the dataset.
   -	The United States leads in revenue with an impressive $13,148. This can be attributed to the widespread popularity of mobile gaming in the country and the large user base.
   -	China follows closely with a substantial revenue of $11,650. The Chinese gaming market continues to be a major player in the global industry, driven by a massive population and a growing appetite for mobile games.

#### 4. Users by Country

![Daily Avtive Users](./images/user-by-country.png)

-	China leads with a massive user base of 38,044k, underscoring the immense popularity and widespread adoption of the mobile game in the Chinese market.
-	The USA follows with a substantial user count of 11,533k, reflecting the strong engagement of the American audience with Supercell’s mobile game.
-	Turkey contributes significantly with a user base of 5,060, indicating a noteworthy presence and engagement within the Turkish gaming community.
-	France has a considerable user count of 4,843, showcasing a robust player base and the game's appeal in the French market.
-	Russia follows closely with a user count of 4,055, signifying active participation and interest in the mobile game within the Russian gaming landscape.
-	South Korea maintains a substantial user base of 2,817, reflecting the game's popularity in a country known for its avid gaming culture.



