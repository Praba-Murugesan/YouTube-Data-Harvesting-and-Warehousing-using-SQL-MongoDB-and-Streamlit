# ![image](https://github.com/Praba-Murugesan/YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit/assets/137065152/173e4b1e-33db-4247-ba83-13648155f01c)
YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit-GUVI Capstone Project

**Demo Video Link**

[https://youtu.be/BzZEgfaDbqM](https://www.youtube.com/watch?v=BzZEgfaDbqM)

**Introduction**

    This project aims to develop a user-friendly Streamlit application that utilizes the Google 
    API to extract information on a YouTube channel, stores it in a MongoDB database, migrates 
    it to a SQL data warehouse, and displaying the data in the Streamlit app.

**Workflow**

    Data Collection:
  
      1.The first step is to collect data from the YouTube using the YouTube Data API. 
      2.The API and the Channel ID (Extracted from the Channel Page) is used to retrieve channel details, 
        videos details and comment details. 
      3.I have used the Google API client library for Python to make requests to the API and the responses 
        are Collected as a Dictionary (Data Collection)
        
    Loading(Storing) the Collected Data to MongoDB:
  
      1.Once the Data Collection is done, store it in MongoDB, which is a NoSQL Database great choice for 
      handling unstructured and semi-structured data.
      
    Data Migration to SQL:
  
      1.After Loading all the data into MongoDB, it is then migrated to a structured MySQL data warehouse.
      2.Then used SQL queries to join the tables and retrieve data for specific channels.
      
    Data Analysis and Data Visualization:
  
      1.With the help of SQL query, I have got many interesting insights about the youtube channels.
      2.Finally, the data retrieved from the SQL is displayed using the Streamlit Web app.
      3.Streamlit is used to create dashboard that allows users to visualize and analyze the data. 
      4.Also used Plotly for the Data Visualization to create charts and graphs to analyze the data.


**Flow Diagram**

![image](https://github.com/Praba-Murugesan/YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit/assets/137065152/9857a6a0-291f-4e85-872e-05ef06560599)
    

**Tools and Technologies used**

•	Python
•	MongoDB
•	MySQL
•	YouTube Data API
•	Streamlit
•	Pandas
•	Plotly


**Streamlit User Interface**

Home Page option menu:

![image](https://github.com/Praba-Murugesan/YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit/assets/137065152/9837b8af-fd99-4833-bdbb-f075d1c6d6ad)

Loading Channel Data to MongoDB:

![image](https://github.com/Praba-Murugesan/YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit/assets/137065152/1ae24db2-4365-422c-a9cc-32e45ef56544)

Data Migration to SQL:

![image](https://github.com/Praba-Murugesan/YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit/assets/137065152/05073574-9b30-4487-9bb9-d4cb94f6c088)

Data Analysis:

![image](https://github.com/Praba-Murugesan/YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit/assets/137065152/3bf5895f-7da1-4a40-80fd-61f2d4918a2e)

Data Visualization:

![image](https://github.com/Praba-Murugesan/YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit/assets/137065152/978a76f8-6ac5-4cc2-89df-5201011cbbdc)


**Conclusion**

    Overall, this approach involves building a simple UI with Streamlit, retrieving data from the 
    YouTube API, storing it in a MongoDB datalake, migrating it to a SQL data warehouse, querying 
    the data warehouse with SQL, and displaying the data in the Streamlit app. This approach can be 
    used to identify trends, make predictions, and improve decision-making.




