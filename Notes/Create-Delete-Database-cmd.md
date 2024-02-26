# Command use to see database present in MongoDB

show dbs;

# Command use to create new database

use <database_name>;

# Command use to delete database

db.dropDatabase();

# Switch between the databases we use:

use(keyword) database_name;

# Command use to see collection database

show collections;

# Command use to create new collection in database

db.CreateCollection('collection_name');

# Command use to delete collection

db.collection_name.drop();
