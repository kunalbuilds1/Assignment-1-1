Assignment 1.1 — How a Website Works
1. How a Website Works

When a user types a URL (Uniform Resource Locator) into a web browser such as Google Chrome, the browser acts as a client and sends a request to a web server using HTTP (Hypertext Transfer Protocol) or HTTPS (Hypertext Transfer Protocol Secure). HTTP is a protocol used to transfer data between a client and a server, while HTTPS provides secure, encrypted communication. The server receives the request, processes it, and may communicate with a database to retrieve the required information. After processing the request, the server sends a response containing resources such as HTML, CSS, JavaScript, and images. The browser receives these resources, interprets them, and displays the website on the screen. This process is known as the request-response cycle. A static website displays fixed content that usually remains the same for every visitor, whereas a dynamic website can display changing content based on user input, database information, or other conditions.

2. Basic Roles
Browser: Software such as Google Chrome that requests, receives, and displays website content.
Client: The user's device or application that sends requests to a server.
Server: A computer or software system that processes requests and sends responses.
Database: A system that stores and manages information used by a website.
3. HTTP and HTTPS
HTTP: Hypertext Transfer Protocol, used for communication between a browser and a web server.
HTTPS: Hypertext Transfer Protocol Secure, which encrypts communication to help protect data from interception.
4. Request-Response Cycle
The user enters a URL into the browser.
The browser locates the server for the requested website.
The browser sends an HTTP or HTTPS request to the server.
The server processes the request and may retrieve information from a database.
The server sends a response to the browser.
The browser processes the received resources and displays the webpage.
5. Difference Between Static and Dynamic Websites
Static Website	Dynamic Website
Displays fixed content.	Content can change according to user input or data.
Usually uses HTML and CSS, with optional JavaScript.	May use server-side programming and databases.
Often simpler and faster to host.	May require more processing and infrastructure.
Example: a simple informational webpage.	Example: an online shopping website.
6. Chrome DevTools Network Tab

To inspect website requests:

Open Google Chrome and visit https://example.com.
Right-click the webpage and select Inspect.
Select the Network tab in Chrome DevTools.
Reload the page by pressing Ctrl + R.
Observe the requests, status codes, resource types, and loading times.
Take a screenshot showing the Network tab and the list of requests.

Screenshot: Insert your screenshot of the Chrome DevTools Network tab here.

Conclusion

A website works through communication between a browser and a server using HTTP or HTTPS. The server may interact with a database to provide the required information, and the browser processes the response to display the webpage. Chrome DevTools helps developers inspect network requests and understand how websites load.