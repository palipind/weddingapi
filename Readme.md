##Steps to build and run  
  1. Run mvn clean install.  
  2. Export the generated .war file to the webapps folder of the host server.  
  3. Start the server.  

##Wedding API

###Wedding    
Get   
Method : GET  
API : `http://localhost:8080/weddingApi/rest/wedding/get/{id}`  

Query   
Method : GET  
API : `http://localhost:8080/weddingApi/rest/wedding/query`

###Device Token  
Add   
Method : POST  
API : `http://localhost:8080/weddingApi/rest/deviceToken/add`  
BODY :  
`{  
    "deviceToken": "token_here",  
    "weddingId": "wedding_id_here"  
}`

Delete
Method : POST
API : `http://localhost:8080/weddingApi/rest/deviceToken/delete`
BODY :
`{
    "deviceToken": "device_token_here"
}`

###Wedding Event
Get
Method : GET
API : `http://localhost:8080/weddingApi/rest/weddingEvent/query/weddingId/{id}`


