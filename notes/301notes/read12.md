# Reading

##Status Codes Based On REST Methods

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

Why do we need to pull our MongoDB database string out of our server and put it into our .env?
What is middleware?
What does app.use(express.json()) do?
What does the /:id mean in a route?
What is the difference between PUT and PATCH?
How do you make a default value in a schema?
What does a 500 error status code mean?
What is the difference between a status 200 and a status 201?
