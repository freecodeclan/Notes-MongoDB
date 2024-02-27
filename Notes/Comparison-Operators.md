# Comparison Operators

MongoDB provides several comparison query operators that can be used to compare the value of fields in your documents. Here are some of the most commonly used ones:

1. `$eq`: Matches values that are equal to a specified value.

2. `$gt`: Matches values that are greater than a specified value.

3. `$gte`: Matches values that are greater than or equal to a specified value.

4. `$lt`: Matches values that are less than a specified value.

5. `$lte`: Matches values that are less than or equal to a specified value.

6. `$ne`: Matches all values that are not equal to a specified value.

7. `$in`: Matches any of the values specified in an array.

8. `$nin`: Matches none of the values specified in an array.

For example, if you want to find all documents in a collection where the age is greater than 20, you would use the `$gt` operator like this:

db.collection('myCollection').find({ age: { $gt: 20 } });

And if you want to find all documents where the age is either 20 or 25, you would use the `$in` operator like this:

db.collection('myCollection').find({ age: { $in: [20, 25] } });

Remember that these operators are used in the context of the `find()` method, which is used to query documents in a MongoDB collection.
