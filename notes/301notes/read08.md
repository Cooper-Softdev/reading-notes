# Reading

## API Design Best Practices

What does REST stand for?
+ Representational State Transfer
REST APIs are designed around a ____.
+ REST APIs are designed around a resource
What is an identifier of a resource? Give an example.
+ A specific Uniform Resource Identifier points to specific resource... https://adventure-works.com/orders/1
What are the most common HTTP verbs?
+ GET
+ POST
+ PUT
+ PATCH
+ DELETE
What should the URIs be based on?
+ Nouns (the resource) and not verbs (the operations on the resource)
Give an example of a good URI.
+ https://adventure-works.com/orders
What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
+ A chatty API requires a client to make a large number of small requests to get data. This is generally not good and causes higher latency.
What status code does a successful GET request return?
+ Code 200
What status code does an unsuccessful GET request return?
+ Code 404, or 400 if request was malformed
What status code does a successful POST request return?
+ Code 201
What status code does a successful DELETE request return?
+ Code 200 with included message body, 204 if action has been enacted and no information is returned

## Things to know more about

1. How can we still get that sweet sweet Reddit API data without the API stuff? Webscraping?
