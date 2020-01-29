# MongoDB

## MongoDB in Docker
```
$ docker run -p 27017:27017 -v ~/mongodbproject:/data/db --name mongodb mongo:latest
$ docker exec -it mongodb bash
```
## Inside Docker container
```
$ mongo
show dbs
use <databasename>
db.<table>.insert({})
db.<table>.find({})
exit
```