

![Example Image](electricity.png)



#PVPC - Home Battery Storage Analysis🏭 

##Objective🎯

PVPC is a regulated tariff for households. This tariff is calculated adding several costs to the wholesale spot (hourly) prices and hence it is a variable tariff. However these added costs are variable as well, and hence, the daily pattern of PVPC prices is not exactly the same than the SPOT prices.The objective of this notebook is to analyze the PVPC (Voluntary Price for Small Consumers) tariff data for households in Spain. The focus is on studying the daily spread of electricity prices, which is essential for evaluating the profitability of investing in home battery storage.

📋 ##Key Tasks
Set up the environment for data processing.
Curate the raw data and create a clean DataFrame.
Perform metadata analysis to understand the data.
Profile columns to gain insights into the dataset.
Answer important business questions related to electricity prices.
🗂️ Data Source
The data is obtained from the REE (Spanish Transport System Operator) API called APIDATOS.

🚀 ## Steps to Run
Ensure Hadoop is started.
Create a SparkSession.
Read data from HDFS and process it to get the final DataFrame.
Analyze the results and answer business questions.
🔍 Analysis Highlights
Explore the daily max, min, average, and spread of electricity prices.
Analyze hourly price behavior for PVPC and Spot prices.
Calculate the ratio of daily spreads for better insights.
Identify the top 5 days with extreme spreads in PVPC and Spot prices.
📊 Visualizations
The notebook includes visualizations of PVPC and Spot prices to understand their patterns and spreads.

For detailed code and in-depth analysis, please refer to the notebook. Happy analyzing! 😊
 

SOURCE OF DATA : API from REE (Spanish Transport System Operator) called APIDATOS (https://www.ree.es/es/apidatos)
