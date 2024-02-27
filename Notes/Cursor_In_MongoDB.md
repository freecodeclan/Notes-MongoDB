# What is Cursor ?

A cursor in MongoDB is a pointer to the result set of a query. When you execute a query, MongoDB returns a cursor object. This cursor object contains the first batch of the query results. You can then iterate over the cursor to retrieve the remaining documents in the result set.

Cursors are handy because they allow you to process documents one by one, which can be especially useful when dealing with huge collections where loading everything at once might not be practical or efficient.

# Cursor Methods

In MongoDB, there are several methods that can be used with cursors to manipulate and handle the data returned from a query. Here are some of the most commonly used cursor methods:

1. `next()`: This method is used to get the next document in the result set.

2. `hasNext()`: This method is used to check if there are more documents in the result set.

3. `forEach()`: This method applies a JavaScript function to each document in a cursor.

4. `count()`: This method returns the count of documents in the cursor.

5. `limit()`: This method constrains the size of a cursor’s result set.

6. `skip()`: This method skips over the specified number of documents from the query results.

7. `sort()`: This method sorts the documents in the cursor.

8. `toArray()`: This method returns an array that contains all documents returned by the cursor.

9. `close()`: This method manually closes the cursor.
