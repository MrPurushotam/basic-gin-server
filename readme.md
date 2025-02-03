Basic Go server with gin. Learning Goooo
To run the code locally clone the repo navigate to basic-gin-server directory run following command 
`go get .`
`go run .`

now you can access follwing routes 
GET /albums 
GET /albums/:id (id is a string for ex "1","2")
POST /albums (post a json object with id,title,artist,price where price if of type flot)