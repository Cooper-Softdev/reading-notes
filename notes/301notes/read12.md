# Reading

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:

- 100’s = The request was received by the server
- 200’s = The request was received and is being processed, it did not fail... yet.
- 300’s = Redirect code, the request information is somewhere else and the server is requesting it.
- 400’s = Client side error, this should happen if there's a syntax error, no code 100 will show.
- 500’s = Server side error, request information is missing or a problem locating the information. Or more?

2. What is a status code 202?
  - The request was accepted and is currently being processed.
4. What is a status code 308?
  - Indiactes that the request resource has been permanently moved to a new location.
6. What code would you use if an update didn’t return data to a client?
  - If an update didn't return data, but the process succesfully completed you would use 204.
8. What code would you use if a resource used to exist but no longer does?
  - Status 410 is used for missing resources and intentionally removed data.
10. What is the ‘Forbidden’ status code?
  - 403 is forbidden status code, server can process request but the client requesting is not allowed.

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  - So the user can't find my API code and run my bills up.
3. What is middleware?
  - Middleware are functions that are between request and response that can modify the requests or responses.
5. What does app.use(express.json()) do?
  - This parses incoming reqeusts that contain JSON and builds it into something readable, then puts it into a req.body object to be placed in the application.
7. What does the /:id mean in a route?
  - /:id is a route for a URL that allows for a request to be made to a specific location in a database... I think?
9. What is the difference between PUT and PATCH?
  - PUT replaces existing resources and PATCH makes changes to parts of a resource without replacing it.
11. How do you make a default value in a schema?
  - Put the word `default` inside the schema definition before you define the schema.
13. What does a 500 error status code mean?
  - A server error of some sort, information is missing or the server can't access it other than a client permission problem.
15. What is the difference between a status 200 and a status 201?
  - 200 is that the request has gone through succesfully, and 201 indicated that a new resource has been created as a result of the request. Like adding information from a PUT request.

### Things to know more about

+ How do we fix a failed status code and run it again, do our requests need loops? or does CORS/Axios take care of that?
