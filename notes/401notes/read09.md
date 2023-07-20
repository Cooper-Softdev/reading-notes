# Reading

## High-level HTTP

1. The five steps in the HTTP Request Lifecycle are:

- DNS Lookup: The client needs to resolve the domain to an IP address. This is done through a DNS lookup.
- TCP Connection: The client establishes a TCP connection with the server. This is done through a process known as the TCP/IP three-way handshake.
- Send HTTP Request: The client sends an HTTP request to the server. This request includes the method (GET, POST, etc.), the path, and the HTTP version, along with headers and sometimes a body.
- Server Handles Request and Sends Response: The server processes the request, generates a response, and sends it back to the client. The response includes a status code, headers, and a body.
- Close or Reuse Connection: Depending on the "Connection" header in the response, the client either closes the connection or keeps it open for further requests.

2. The two things the client needs before it can make an HTTP Request are:

- The IP address of the server: This is obtained through a DNS lookup.
- A TCP connection to the server: This is established through a process known as the TCP/IP three-way handshake.

3. The four-way handshake is a process used to terminate a TCP connection. It involves four steps:

- The client sends a FIN packet to the server to indicate that it has finished sending data.
- The server acknowledges the FIN packet with an ACK packet.
- The server then sends its own FIN packet to the client to indicate that it has finished sending data.
- The client acknowledges the server's FIN packet with an ACK packet. After this, the connection is fully terminated.

## Java HTTP requests

1. True or False: When making an HTTP request, you MUST follow any redirect returned by the request. Back up your answer.
- False. Following redirects is optional when making an HTTP request. In the context of the HttpUrlConnection class in Java, redirects can be handled manually. The setInstanceFollowRedirects() method can be used to enable or disable automatically following redirects for a specific connection. By default, this behavior is enabled. However, when a request returns a status code 301 or 302, indicating a redirect, the Location header can be retrieved and a new request can be created to the new URL.

2. Which built-in Java class can be used to perform an HTTP request?
- The built-in Java class HttpUrlConnection can be used to perform an HTTP request.

3. What HTTP status codes represent a successful response? A redirect? A client error?
- Successful response: HTTP status codes in the 200-299 range represent a successful response, with 200 being the standard response for successful HTTP requests.
- Redirect: HTTP status codes in the 300-399 range represent redirects, with 301 and 302 being commonly used for Moved Permanently and Found (Moved Temporarily), respectively.
- Client error: HTTP status codes in the 400-499 range represent client errors, with 404 for Not Found and 403 for Forbidden being among the most common.
