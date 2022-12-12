https://github.com/ashuppal/reading-notes

**Readings: CRUD**

Status Codes Based On REST Methods

In your own words, describe what each group of status code represents:

100’s = These are informational status codes which indicates that the request was received and understood. 
        It is issued on a provisional basis while request processing continues. It alerts the client to wait for a final response. 
200’s = These are the success codes. They tell the client that its request was accepted
300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. 
400’s = These are the client error codes. They are all about invalid requests a client sent to a server.
500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers.
          
What is a status code 202?
This code tells the client that the request was valid, but its processing will finish sometime in the future. 
          
What is a status code 308?
This tells the client to use another URL to access the resource and not use the current URL anymore.
          
What code would you use if an update didn’t return data to a client?
204 No Content
  
What code would you use if a resource used to exist but no longer does?
404 (Not Found) 
  
What is the ‘Forbidden’ status code?
403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

**Build A REST API With Node.js, Express, & MongoDB**
  
What is middleware?

Mongoose middleware are functions that can intercept the process of the init , validate , save , and remove instance methods.
  
What does app.use(express.json()) do?
This is a built-in middleware function in Express. It parses incoming requests with JSON payloads and is based on body-parser.
  
What does the /:id mean in a route?
Route parameters are named URL segments that are used to capture the values specified at their position in the URL

What is the difference between PUT and PATCH?(https://www.geeksforgeeks.org)
PUT is a method of modifying resources where the client sends data that updates the entire resource.
PATCH is a technique for transforming the resources when the client transmits partial data that will be updated without changing the whole data.
  
How do you make a default value in a schema?
You can make a default value in a schema by adding your schema's defaults to a MongoDB $setOnInsert operator.
                                              
What does a 500 error status code mean?
500 erroe status means that the server encountered an unexpected condition that prevented it from fulfilling the request.
  
What is the difference between a status 200 and a status 201?
200: “Everything is OK.” This is the code that is delivered when a web page or resource acts exactly the way it's expected to. 
201: “Created.” The server has fulfilled the browser's request, and as a result, has created a new resource.            
                                              
##Things I want to know more about
Indepth understanding of MongoDB
                                              
