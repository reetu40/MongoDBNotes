* does not have fixed schema and data is denomalized
* so mongodb can we used for projects that are evolving and data requirements are not set yet
* less relations better efficiency in fetching data
* they are good for read or write heavy apps

MONGO DB offerings
>on permise
>atlas
>Stich is serverless offering

Mongo Shell -you can run commands like show dbs will shows dbs in the shell

Bigger Picture
![alt text](image.png)


**********************************************************************
CRUD(CREATE/UPDATE/UPDATE/DELETE)

DATABASE HAS MULTIPLE COLLECTIONS and which has different documents 
![alt text](image-1.png)
db.version()
show dbs
db.comments.find({"name":"John Bishop"}).count();
****************************
JSON vs BSON(Binary JSON)
JSON is converted into BSON by the drivers so that its efficient storage
