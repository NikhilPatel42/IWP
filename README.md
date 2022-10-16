# IWP
IWP Proj

some basic operations
CRUD

start mongosh on terminal

enter the following to create a darabase, create a collection within the database
incase, you're importing a json file   
use the following  
`mongoimport --db <database-name> --collection <collection-name> --file <path/to/file.json> --jsonArray -u <your-username> -p <your-password> --authenticationDatabase admin`

for querying use find() 
```
use <database-name>
db.createCollection(<collecion-name>, field: <type>...)
db.find()
```
