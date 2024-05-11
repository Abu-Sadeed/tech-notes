REST is an architectural style for designing networked applications, emphasizing statelessness, uniform resource identifiers (URIs), and standard HTTP methods.

- **Key Principles**:
    - **Statelessness**: Each request from a client to the server must contain all the necessary information for the server to understand and fulfill it. The server does not store client state between requests.
    - **Client-Server Architecture**: Separation of concerns between client and server, allowing them to evolve independently.
    - **Uniform Interface**: Resources are uniquely identifiable through URIs, and interactions are performed using standard HTTP methods ([GET](GET.md), [POST](POST.md), [PUT](PUT.md), [DELETE](DELETE.md), [PATCH](PATCH.md)).
    - **Cacheability**: Responses can be cached to improve performance.
    - **Layered System**: Clients interact with the server without needing to know the underlying implementation details, promoting scalability and encapsulation of concerns.

- **Components**:
    - **Resources**: Any information that can be named and addressed, typically exposed as URIs.
    - **HTTP Methods**:
        - **GET**: Retrieve a resource.
        - **POST**: Create a new resource.
        - **PUT**: Update an existing resource.
        - **DELETE**: Remove a resource.
    - **Headers**: Additional information sent with the request or response, such as content type or authentication tokens.
    - **Status Codes**: HTTP status codes indicate the outcome of a request (e.g., 200 for success, 404 for not found, 500 for server error).

- **URL Structure**:
    - **Resource Endpoint**: /api/resource
    - **Resource Identifier**: /api/resource/{id}

- **Content Types**:
    - **JSON (application/json)**: Lightweight and widely supported for data interchange.
    - **XML (application/xml)**: More verbose than JSON but still used in some contexts.

- **Authentication**:
    - **API Keys**: Unique identifiers passed with API requests for authentication.
    - **OAuth**: Standard protocol for authorization, allowing third-party applications to access user data without sharing passwords.

- **Response Formats**:
    - **JSON**: Commonly used due to its simplicity and compatibility with JavaScript.
    - **XML**: Offers more structure but is often considered more verbose than JSON.

- **Testing Tools**:
    - **Postman**: Popular API testing tool for sending requests and inspecting responses.
    - **cURL**: Command-line tool for making HTTP requests.

- **Documentation**:
    
    - Comprehensive documentation is crucial for developers to understand how to use the API, including endpoint descriptions, request parameters, and response formats.

- **Security Measures**:
    - **SSL/TLS Encryption**: Secure communication between client and server.
    - **Input Validation**: Preventing injection attacks and ensuring data integrity.
    - **Rate Limiting**: Preventing abuse and ensuring fair usage of the API.

- **Best Practices**:
    - **Consistent Naming Conventions**
    - **Versioning**
    - **Input Validation**
    - **Error Handling**