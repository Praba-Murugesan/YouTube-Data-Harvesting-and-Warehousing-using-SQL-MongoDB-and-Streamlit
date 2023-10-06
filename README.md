# YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit

**Introduction**

This project aims to develop a user-friendly Streamlit application that utilizes the Google API to extract information on a YouTube channel, stores it in a MongoDB database, migrates it to a SQL data warehouse, and enables users to search for channel details and join tables to view data in the Streamlit app.

**Workflow**

    **Data Collection**
      1.The first step is to collect data from the YouTube. This can be done using the YouTube Data API. 
      2.The API and the Channel ID (Extracted from the Channel Page) is used to retrieve channel details, videos details and comment details. 
      3.I have used the Google API client library for Python to make requests to the API and the responses are Collected as a Dictionary (Data Collection).
      
    **Loading(Storing) the Collected Data to MongoDB**
      1.Once the Data Collection is done, store it in MongoDB, which is a NoSQL Database. MongoDB is a great choice for handling unstructured and semi-structured data.
      
    **Data Migration to SQL**
      1.After Loading all the data into MongoDB, it is then migrated/transformed it to a structured MySQL as data warehouse.
      2.Then used SQL queries to join the tables in the SQL data warehouse and retrieve data for specific channels based on the user input.
      
    **Data Analysis and Data Visualization**
      1.With the help of SQL query, I have got many interesting insights about the youtube channels.
      2.Finally, the data retrieved from the SQL is displayed using the Streamlit Web app. Streamlit is a Python library that can be used to create interactive web applications. 
      3.We will use Streamlit to create a dashboard that allows users to visualize and analyze the data. 
      4.Also used Plotly for the Data Visualization to create charts and graphs to analyze the data.

**Tools and Technologies used**

•	Python
•	MongoDB
•	MySQL
•	YouTube Data API
•	Streamlit
•	Pandas
•	Plotly
**Conclusion**
Overall, this approach involves building a simple UI with Streamlit, retrieving data from the YouTube API, storing it in a MongoDB datalake, migrating it to a SQL data warehouse, querying the data warehouse with SQL, and displaying the data in the Streamlit app. This approach can be used to identify trends, make predictions, and improve decision-making.
