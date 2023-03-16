# Tourist

HBase is an open-source, column-oriented database management system (DBMS) that is designed to handle large volumes of structured data. It is built on top of Apache Hadoop, which provides HBase with the ability to store and manage massive amounts of data across distributed clusters of commodity hardware.

HBase is a NoSQL database that provides real-time read/write access to large datasets. It is commonly used in applications that require fast and random read/write access to very large datasets, such as social networks, online advertising, financial services, and web analytics.

In this Tourism table there are three columns named Details, Bank details and Accommodation info containing three rows basically

![nosql ass2 pic 1](https://user-images.githubusercontent.com/123860326/225751544-e3c4f36c-8356-482a-8b1f-cf978f9a6359.jpg)

In the first row I updated the values of row no 01 by changing their days of planning, Then In the second row I inserted the branch info in the Bank details column using put keyword. finally I deleted the last row's Accommodation by the type of room using delete keyword.

![nosql ass1 pic 2](https://user-images.githubusercontent.com/123860326/225751682-5ecafeb8-13ff-4758-b7dc-8861e7721336.jpg)

To make the above operation I used the following keywords:

         put- put keyword is used to insert and update the values of the family in the table.

         scan- scan keyword is used to display the entities of the table we have created.

         get-  get keyword is used to read the values of the table.

         delete- delete keyword is used to delete the value as well as the table.
         
 Pictorial representation of CRUD operation in Tourism database are attached in the issues file(3 files).
         
In conclusion, column-family databases are a powerful tool in the world of data management, and their popularity is only expected to grow as organizations continue to generate and collect more and more data.

