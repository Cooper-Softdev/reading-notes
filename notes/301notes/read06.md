# Reading 06

## REST

1. Who is Roy Fielding?
+ Roy Fielding is one of the persons who created HTTP. 
2. Why don’t the techniques that we use in this class work well when we need to be able to talk to all of the machines in the world?
+ Client-server architecture was not designed to scale and communicate with all the machines in the world. To scale you must use a more decentralized and therefore scalable approach.
3. What is the HTTP protocol that Fielding and his friends created?
+ Hypertext Transfer Protocol is now the standardized way to communicate between clients like browsers, and the servers over the internet. It defines how the requests and responses should be formatted so computers can all be standardized.
4. What does a GET do?
+ GET is the HTTP method to retrieve data from a server. The client send a GET request to a server and the server responds appropriately.
5. What does a POST do?
+ a POST request to submit data to a server to create a new resource or trigger an action, the opposite of a GET request. 
6. What does PUT do?
+ PUT is used to update or replace an existing resource with the provided data inside the packet. The client must send the complete representation of the resource in the request payload, whatever that means.
7. What does PATCH do?
+ PATCH is used similar to PUT but instead of sending a large packet of the complete representation of the resource, it's able to just send the specific changes to be made instead of the entire instance.

## API KEYS

I have all my API keys, one has an expiration in 21 days, though I hope that's not an issue.
