# ASP.Net-Web-Core-API
This repository tracks my journey of learning ASP.NET Core Web API. It includes hands-on projects, experiments, and practice exercises as I work through backend development concepts such as REST APIs, controllers, routing, database integration, authentication, and API design.

# DAY-01

# Topics covered today.

# API
# Servers
# Client 
# HTTP and HTTPS
# Request and Response 
# URL
# JSON
# HTTP Methods
# Status Code
# Project Structure 



# What is an API ?
An API is a way for different applications to communicate with each other. It acts as a bridge between a client and a server, allowing the client to request data or perform actions, and the server to send back the appropriate response.
For example: For example, when a mobile app shows user data, it doesn't access the database directly. It sends a request to an API, and the API returns the required data from the server.


# What is a Server ?
A server is a system that receives requests from clients, processes those requests, and sends back the appropriate response. It can provide data, run business logic, access databases, and serve resources to applications such as websites, mobile apps, or APIs.


# What is a Client ?
A client is any application, browser, or device that requests data or services from a server. It sends a request to the server and then receives the response back.


# What is HTTP and HTTPS ? 
HTTP is the set of rules that allows a client and server to communicate with each other. HTTPS does the same thing, but it adds encryption to secure the data being transferred between them.

HTTP
Example = http://example.com 

HTTPS
Example = https://example.com


# What is Request and Response ?
A request is when a client, like a browser or mobile app, asks the server for some data or asks it to perform an action. A response is what the server sends back after processing that request, such as data, a success message, or an error message.


# What is a URL ? 
A URL is basically the address of a resource on the internet. It tells the client where to send the request and what resource it wants to access.


# What is JASON ?
JSON (JavaScript Object Notation) is a lightweight format used to store and exchange data between applications. It organizes data as key-value pairs, making it easy for both humans and machines to read and understand. APIs commonly use JSON to send and receive data.
{
  "id": 1,
  "name": "Affan",
  "age": 22
}


# What are HTTP methods ?
HTTP methods are actions that a client can request a server to perform on a resource. They define what operation should be carried out, such as retrieving data, creating new data, updating existing data, or deleting data.

Main HTTP Methods
GET = Retrieve data
POST = Create new data
PUT = Update existing data
DELETE = Remove data


# What is a Status Code ?
A status code is a number sent by the server in the response to indicate the result of a client's request. It tells the client whether the request was successful, failed, or if some other action is needed.

Common Examples
200 OK = Request was successful.
201 Created = A new resource was created successfully.
400 Bad Request = The request was invalid.
401 Unauthorized = Authentication is required.
404 Not Found = The requested resource was not found.
500 Internal Server Error = Something went wrong on the server.


# What is Project Structure ?
Project structure refers to how a project's files, folders, and components are organized. A good project structure helps keep the code clean, maintainable, and easy to navigate, making it easier for developers to understand and work on the application.

Controllers/
Models/
Services/
Data/
Program.cs
appsettings.json
