# Simple HTTP Server

This Java program sets up a basic HTTP server that listens on port 8000 and responds with a simple message when accessed.

## Usage

1. **Compile the Code**: Compile the `SimpleHttpServer.java` file using `javac SimpleHttpServer.java`.

2. **Run the Server**: Execute the compiled class using `java SimpleHttpServer`.

3. **Access the Server**: Open a web browser or use a tool like cURL to access `http://localhost:8000/` to see the response.

## Description

The program uses the `com.sun.net.httpserver` package to create an HTTP server instance and define a custom handler to respond to incoming HTTP requests.

## Code Structure

- `SimpleHttpServer.java`: Contains the main class `SimpleHttpServer` and a nested class `MyHandler` that implements the `HttpHandler` interface to handle HTTP requests.

## Dependencies

This program relies on Java SE API and does not require any additional dependencies.

## Note

This is a basic example to demonstrate setting up an HTTP server in Java. For production use or more complex scenarios, consider using frameworks like Spring Boot or Apache Tomcat.

