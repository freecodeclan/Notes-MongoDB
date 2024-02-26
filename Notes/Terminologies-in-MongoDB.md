# Terminologies used in MongoDB

Sure, here are some key terminologies used in MongoDB:

1. **Document**: A record in MongoDB is called a document, which is a data structure composed of field and value pairs. MongoDB documents are similar to JSON objects.

2. **Collection**: A group of MongoDB documents. It is the equivalent of an RDBMS table. A collection exists within a single database.

3. **Database**: A physical container for collections. Each database gets its own set of files on the file system. A single MongoDB server typically has multiple databases.

4. **Field**: A name-value pair in a document. A document has zero or more fields. Fields are analogous to columns in relational databases.

5. **Embedded Documents**: Documents that are nested inside other documents. MongoDB supports hierarchical relationships between documents.

6. **Primary Key**: A primary key is a unique identifier for a document. In MongoDB, the primary key is the `_id` field.

7. **Replica Set**: A group of MongoDB instances that maintain the same data set. Replica sets provide redundancy and high availability.

8. **Sharding**: A method for distributing data across multiple machines. MongoDB uses sharding to support deployments with very large data sets and high throughput operations.

9. **Index**: A special data structure that stores a small portion of the data set’s data in an easy-to-traverse form. The index stores the value of a specific field or set of fields, ordered by the value of the field as specified in the index.

10. **Cursor**: A pointer to the result set of a query. Clients can iterate through a cursor to retrieve results.

11. **BSON**: BSON (Binary JSON) is a binary representation of JSON-like documents. MongoDB uses BSON to store documents and make remote procedure calls.

12. **GridFS**: A specification for storing and retrieving files that exceed the BSON-document size limit of 16MB.

13. **Aggregation**: Operations that process data records and return computed results. MongoDB provides a rich set of aggregation operations, such as grouping by a specified key and evaluating a variety of accumulator expressions.

14. **MongoDB Management Service (MMS)**: A powerful web tool that provides you with visibility into your MongoDB deployment with monitoring, backup, and point-in-time recovery.
