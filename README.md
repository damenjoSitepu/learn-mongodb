# Documentation For Learning Mongo DB

> [!NOTE]
> Last Update: `Mon, 14 Aug 2023`

| Command / Method | Used For |
| --------------- | --------------- |
| `show dbs` | Showing list of your databases |
| `show collections` | showing list of your collections from certain database |
| `db.dropDatabase()` | drop your database / delete it|
| `db.nameOfTable.find()` | showing all of your table data ( records in mongo call as document ) | 
| `db.nameOfTable.insertOne({})` | insert one document to the collections |
| `db.nameOfTable.insertMany({})` | insert more than one document to the collections |
| `db.nameOfTable.find({})` | If you fill the find() method with an argument as object, the data will be searched as match as the key and value that you write within it |
| `db.nameOfTable.find().skip()` | Skipping one or more rows base on argument that you've been inputted |
| `db.nameOfTable.find().sort()` | Sorting the collections result base on object that you've been inputted on the `sort()` argument |
| `db.nameOfTable.find().limit()` | Limits your collection result base on number of rows as first argument on the `limit()` method |
| `-1`: Descending, `1`: Ascending | Additional notes for `sort()` functionality |
| `db.nameOfTable.find({},{})` | The first argument of `find()` method contains object that will matched on the list of collections, and the second argument was referred to the what are columns that you want to show as the collection results |