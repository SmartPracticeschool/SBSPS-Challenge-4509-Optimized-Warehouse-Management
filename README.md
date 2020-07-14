"# SBSPS-Challenge-4509-Optimized-Warehouse-Management"
 
Title: Optimized Warehouse Management of Perishable Goods for a Food Delivery Company
Description: A food delivery service has to deal with a lot of perishable raw materials which makes it all, the most important factor for such a company is to accurately forecast daily and weekly demand. Too much inventory in the warehouse means more risk of wastage, and not enough could lead to out-of-stocks - and push customers to seek solutions from your competitors. The replenishment of majority of raw materials is done on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance,
Expected Solutions: Machine Learning Model to predict the demand of goods for the next 10 weeks or in the future Mobile / Web Application to Interact with ML Model deployed on IBM Cloud
Technologies & Tools: Python 3, IBM Watson Studio, IBM Cloud 
References: 
1. https://www.kaggle.com/kannanaikkal/food-demand-forecasting
2. https://www.altexsoft.com/blog/demand-forecasting-methods-using-machine-learning/

For Website:
1. Download the Website folder
2. Open your IBM Node-Red Dashboard
3. Import the home.json, feedback.json and uibuilder.json flows in Node-Red
4. Open the uibuilder Node in UIBuilder Flow
5. Open the "home.html" file from the "UIBuilder" folder existing in the "Website" folder.
6. Select "Edit Source Files" button and click on button "New"
7. Create new file with name "home.html"
8. Copy paste the "home.hmtl" file from the UIBuilder folder to the newly created "home.html" file in uibuilder node
9. Repeat the steps 5 to 8 and create files "sentiment.html", "dashboard.html", "chatbot.html" also.
10. For database, Install the DB2 Service on IBM Cloud
11. Create new service credentials from the Service Credentials Tab on the DB2 page.
12. Go to "Manage" Tab and open Console.
13. Open your Schema and Create Table with Table Name as "FEEDBACK"
14. Add Columns "NAME, EMAIL,PHONE, SUBJECT, SOCIALTONE, EMOTIONTONE" with DATATYPE as VARCHAR, LENGTH as 32 and NULLABLE as N.
15. Add Tone Analyzer Service to your IBM Cloud
16. From your Cloud Foundry Apps go to IBM Node-Red Application and in Connections Create a new connection of Tone Analyzer
16. Open the FEEDBACK Node in Feedback flow.
17. Edit the Database Credentials according to the newly created credentials.
18. Deploy the flows
19. Open Link "https://node-red-aftnm.eu-gb.mybluemix.net/uibuilder/home.html"  
								OR 
	Open URL according to your NodeRed URL and add '/uibuilder/home.html' to the URL.
20. The entire website is ready and working on your webpage

The catboost_1(1).csv is the final Prediction File generated after testing the ML Model.

The video explains the complete project
The PPT gives all the details of the project and is to be used for the final presentation.