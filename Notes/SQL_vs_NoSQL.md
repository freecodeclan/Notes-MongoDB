# **Difference b/w SQL and NoSQL**

SQSQL and NoSQL are two types of database management systems, each with their own strengths and weaknesses. Here are some of the key differences:

1. **Data Structure**: SQL databases are table-based, meaning they store data in rows and columns, much like an Excel spreadsheet. This makes them a good fit for applications that require multi-row transactions with complex querying and stringent requirements. NoSQL databases, on the other hand, are document-based, key-value pairs, graph databases or wide-column stores. This makes them highly flexible and suitable for hierarchical data storage.

2. **Scalability**: SQL databases are typically scaled by enhancing the horsepower of the machine (vertical scaling), while NoSQL databases are designed to expand horizontally, meaning they can be spread across more servers easily (horizontal scaling).

3. **Schema**: SQL databases require that you use a predefined schema to determine the structure of your data before you work with it. In contrast, NoSQL databases are schema-less, meaning you can create documents without having to first define their structure.

4. **ACID Properties (Atomicity, Consistency, Isolation, Durability)**: SQL databases follow ACID properties which guarantee that transactions are processed reliably. NoSQL databases follow the Brewers CAP theorem (Consistency, Availability, Partition tolerance) which allows for flexible transaction processing.

5. **Complexity of Queries**: SQL databases are good for complex queries as they have a powerful query language. On the other hand, NoSQL databases are not as good for complex queries because the query capabilities are designed to be simpler to ensure the database can scale horizontally.

6. **Language**: SQL databases use SQL (structured query language) for defining and manipulating the data, which is very powerful. In NoSQL database, queries are focused on a collection of documents. Sometimes it is also called as UnQL (Unstructured Query Language).
