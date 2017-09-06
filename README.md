# RESTfulAPI
Handle CRUD for an item 

Base url: localhost:3000/api

Requests:
to list all items(bears) from database
GET 
  url: localhost:3000/api/bears 
 
to add item 
POST 
  url: localhost:3000/api/bears
  data: 
  {
	  "name": "demo"
  }
  response:
  {
    "message": "Bear created!"
  }
  
to view details of item as per particular id:
GET
  url: localhost:3000/api/bears/:bear_id
 
to update details of item as per particular id:
PUT
  url: localhost:3000/api/bears/:bear_id
  response:
    {
      "message": "Bear updated!"
    }

to delete details of item as per particular id:
DELETE
  url: localhost:3000/api/bears/:bear_id
  response:
    {
      "message": "Bear deleted!"
    }
