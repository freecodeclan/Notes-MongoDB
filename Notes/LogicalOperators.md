# Logical Operators

MongoDB also provides several logical query operators that can be used to combine multiple query conditions. Here are some of the most commonly used ones:

1. `$and`: Joins two or more queries with a logical AND and returns the documents that match all the conditions.

db.collection('myCollection').find({ $and: [ { age: { $gt: 20 } }, { 'name.first': 'John' } ] });

2. `$or`: Joins two or more queries with a logical OR and returns the documents that match any of the conditions.

db.collection('myCollection').find({ $or: [ { age: { $gt: 20 } }, { 'name.first': 'John' } ] });

3. `$not`: Inverts the effect of a query expression and returns the documents that do not match the query expression.

db.collection('myCollection').find({ age: { $not: { $gt: 20 } } });

4. `$nor`: Joins two or more queries with a logical NOR and returns the documents that fail to match both conditions.

db.collection('myCollection').find({ $nor: [ { age: { $gt: 20 } }, { 'name.first': 'John' } ] });

Remember that these operators are used in the context of the `find()` method, which is used to query documents in a MongoDB collection.
