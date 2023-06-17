# How-Web-Works-Exercise

1- What is HTTP?
    Hypertext Transfer Protocol its how the browsers and server communicate

2- What is a URL? 
    Uniform Resource Locator it's a reference to a web resource that specifies its location on a computer network and a mechanism for retrieving it, it's frequency associated with HTTP request.

3- What is DNS?
    Domain Name System, take the hostname and translate it to IP address and vice versa

4- What is a query string?
    Part of a URL which assigns values to specified parameters.


5- What are two HTTP verbs and how are they different?
    GET:  Requests using GET should only retrieve data.
    POST: often causing a change in state or side effects on the server.

6- What is an HTTP request?
     the call that the client/browser makes to the web server

7- What is an HTTP response?
    The client sends its request to the server. Upon receiving the request, the server sends back an HTTP response message (hheader plus a body if it is required). The body of this message is typically the requested resource, although an error message or other information may also be returned.

8- What is an HTTP header? Give a couple examples of request and response headers you have seen.
    request Header
      Hostname, Date, Language, Cookies
    response Header
      Content Type, Date/time, cookies, Any caching information.

9- What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
    make request to IP address with headers the server send response then the browser display that response.
