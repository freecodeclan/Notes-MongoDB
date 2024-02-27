# Projection

Projection in MongoDB is a way to select only the necessary data rather than selecting the whole data of a document. If a document has 5 fields and you need to show only 3, then select only 3 fields from them. This is called projection.

For example, consider the following query:

# db.collection('myCollection').find({}, { name: 1, age: 1, id: 0 })

To include specific field we use prejection with a value 1.

And, to exclude specific field we use prejection value 0.
