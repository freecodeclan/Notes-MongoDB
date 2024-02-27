# insert Documents in MongoDB

To insert documents into a MongoDB collection, you use the insertOne() or insertMany() methods, depending on whether you're inserting one document or multiple documents at a time.

**Insert One Document**

To insert a single document into a collection, you use the insertOne() method. Here's the basic syntax:

**db.collectionName.insertOne({ key1: value1, key2: value2, ... })**

Example : db.users.insertOne({ name: "John", age: 30, email: "john@example.com" })

**Insert Many Documents**

To insert multiple documents into a collection, you use the insertMany() method. The documents are provided as an array.

**db.collectionName.insertMany([ { document1 }, { document2 }, ... ])**

Example : db.users.insertMany([
{ name: "Alice", age: 25, email: "alice@example.com" },
{ name: "Bob", age: 35, email: "bob@example.com" }
])

**Note** : To display data we use

**db.<colection_name>.find()**
