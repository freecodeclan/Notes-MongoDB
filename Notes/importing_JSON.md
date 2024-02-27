# Import json in MongoDB

To import a JSON file into MongoDB, you can use the `mongoimport` command-line tool that comes with MongoDB. Here's an example of how you can use it:

mongoimport myFile.json -d myDatabase -c myCollection

In this command:

- `myDatabase` is the name of the database you want to import into.
- `myCollection` is the name of the collection you want to import into.
- `myFile.json` is the path to the JSON file you want to import.

This command will import the JSON data in `myFile.json` into the `myCollection` collection in the `myDatabase` database.

Please note that the JSON file should contain one valid JSON object per line. If your JSON file is an array of objects, you might need to preprocess it to have one object per line without commas at the end of the lines.

Also, `mongoimport` needs to be run from your system's command line, not the MongoDB shell.

If you're using MongoDB Atlas (MongoDB's cloud service), `mongoimport` might not be the best tool for the job, as it's not recommended for data import on Atlas clusters. Instead, you can use MongoDB's Compass GUI or the `mongorestore` utility.
