HTTP POST is a request method used to submit data to be processed to a specified resource. It often results in the creation of a new resource on the server.

- **Usage**:
    - Create a new resource on the server.
    - Submit data to be processed by the server.

- **Characteristics**:
    - Parameters sent in the [request body](Request%20Body.md).
    - Used for non-[idempotent](Idempotent.md) operations, meaning multiple identical requests may have different outcomes.

- **Examples**:
    - Creating a new user account.
    - Submitting a form with user input data.
    - Uploading a file to a server.

- **Response**: Includes [[HTTP status code]] indicating the outcome of the request and any additional data representations.

- **Security**: Protect sensitive data by using HTTPS encryption for POST requests.

- **Best Practices**:
    - Use POST requests for operations that create or modify server-side resources.
    - Validate user input to prevent security vulnerabilities like injection attacks.