# FullstackdevelopmentImporting the http module: The http module is a built-in Node.js module that allows you to create an HTTP server.

Creating the server: The http.createServer() method takes a callback function that is executed every time a request is made to the server. This function has two parameters:

req: Represents the incoming request.
res: Represents the response that you will send back to the client.
Setting the response header: You set the Content-Type to text/plain to specify that the response will be plain text.

Handling routes: The switch statement checks the req.url property to determine which route was requested. For each route (/home, /about, and /contact), the server responds with a different message. If the URL doesn’t match any of the defined routes, a 404 Not Found response is sent.

Defining the port: The server listens on a specified port (default is 3000). You can access the server using http://localhost:3000.

Starting the server: The server.listen() method starts the server, and a message is logged to the console indicating that the server is running.
