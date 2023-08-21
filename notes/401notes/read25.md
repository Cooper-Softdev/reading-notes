# Reading

## Questions

### What makes an API RESTful?

  - Uses standard HTTP methods (GET, POST, PUT, DELETE).
  - Stateless, meaning each request from a client contains all the information needed to process the request.
  - Organized around "resources", where each resource is identified by a specific URI (Uniform Resource Identifier), not sure how this functions in real world use yet.
  - Provides a uniform interface, making it predictable therefore easier to clients to use.
  - Can use multiple representations (like XML and JSON) to communicate with the client.

### Benefits and Downsides to using GraphQL

**Benefits**:

  - Allows clients to specify exactly what data they need, reducing over-fetching or under-fetching of data.
  - Enables clients to get all the data they need in a single request.
  - Strongly typed, ensuring the client gets what it expects.
  - Evolves without versioning, allowing for continuous API evolution.

**Downsides***:
  - Complexity: Can be more complex to set up compared to REST.
  - Performance issues: If not implemented correctly, it can lead to performance bottlenecks.
  - Learning curve: Developers need to learn a new query language.

### Describe Serverless to a 301 student

  Serverless isn't really "server-less" its more like "NonDedicated Server"...
  So you've made your react app, it's on netlify and you have a mongoDB connected to it. All of a sudden your app becomes insanely popular.
  That netlify hosting service is going to crash and start sending out 404s because of all the traffic it can't handle, you haven't built
  server scaling into your back-end. Scaling is a huge endeavor that the smart people at amazon, microsoft, and IBM have figured out and can
  do that for you for a small fee. So if you've deployed your mongoDB and Netlify and then transfer that into AWS, Azure, Google or IBM services
  you can let your app scale as much as it wants because they have the overhead and servers all over the world to push your backend logic or the
  database data to the user. You get charged for the actual usage not the idle time of the server because it sits in a low power state if it gets no
  requests, then spins up quickly and starts working immediately. All those weird edge cases in server management get accounted for under the hood 
  at whatever platform you chooe to use and your users get a better user experience because they've got no delays or weird quirks when using your app.
