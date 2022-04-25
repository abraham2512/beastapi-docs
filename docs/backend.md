# Akka HTTP Endpoints


### GET /tiles/
Returns pre generated
tile or generates one on the fly.
```
curl http://127.0.0.1:8080/tiles?dataset=<dataset>&z=<Z>&x=<X>&y=<Y> 
```

### GET /files 

Return all the files in our server
```
curl http://127.0.0.1:8080/files

```

### POST /files 
Upload the file from URL into our HDFS and update metadata
in embedded SQL storage

```
```


### GET /files/{id}  
 -> Returns the details of a file
```
```

### DELETE /files/{id}
Deletes the dataset from server
```
```

![api-design](images/api-design.png)