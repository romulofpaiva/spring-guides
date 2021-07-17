# RESTful Web Service

This “Hello, World” RESTful web service was created with Spring as described at [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/).

The builded service accept HTTP GET requests at http://localhost:8080/greeting.

It will respond with a JSON representation of a greeting, as the following listing shows:

{"id":1,"content":"Hello, World!"}

You can customize the greeting with an optional name parameter in the query string, as the following listing shows:

http://localhost:8080/greeting?name=User

The name parameter value overrides the default value of World and is reflected in the response, as the following listing shows:

{"id":1,"content":"Hello, User!"}
