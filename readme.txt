How Web Works Exercise

What is HTTP? 
  Hyper Text Transfer Protocol is the set of rules that describes how data is requested and exchanged
	between clients and servers.
  
What is a URL? 
  A Uniform Resource Locator is an address that points to some data...text, images, files, etc.

What is DNS? 
  Domain Name System is a system that converts human language names into IP addresses.

What is a query string? 
  A query string is a specific pattern of characters usually starting with a '?' which is 
  sent with a web request and that can be parsed by the server as keys and values.
  
What are two HTTP verbs and how are they different? 
  GET - Is a request to the server to retrieve data to
	be used by the browser and has no side-effect on the server.
	POST - Is a request to the server that also creates a change on the server.
  
What is an HTTP request? 
  An HTTP request is a request from a client to a server that follows HTTP request rules and format
	(such as requesting specific code-language, human-language, and including client address).
  
What is an HTTP response? 
  An HTTP response is a return from the server to the client which contains the data from the request
	(such as the page HTML and CSS).
  
What is an HTTP header? 
  Give a couple examples of request and response headers you have seen.
	An HTTP header describes the nature of the transmission (request or response) and includes things like URLs, addresses, and statuses.
	A Request header will include the requested types of code-language, human-language, requestor's address, encoding type.
	A Response header will include things like the returned content-type, content-length, date, and server.
  
What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
	1. The browser uses DNS to resolve an ip address
	2. The browser creates and sends an HTTP request to that ip
	3. The server receives the request and returns an HTTP response based on the request (returning the page's HTML)
	4. The browser constructs the page out of the HTML and sends any additional requests needed (retrieving CSS, scripts, images, etc.) to complete the page.
