HTTP PUT is a request method used to update or replace a resource on the server with the provided data.

- **Usage**:
    - Update an existing resource on the server.
    - Completely replace the content of a resource with new data.

- **Characteristics**:
    - Entire resource representation sent in the request body.
    - Intended for [idempotent](Idempotent.md) operations, meaning multiple identical requests have the same effect as a single request.

- **Examples**:
    - Updating a user's profile information.
    - Replacing an existing document with a new version.

- **Response**: Includes [[HTTP status code]] indicating the outcome of the request and any additional data representations.

- **Security**: Ensure proper authentication and authorization mechanisms are in place to control access to PUT operations.

- **Best Practices**:
    - Use PUT requests for operations that completely update or replace existing resources.
    - Provide clear documentation on the expected format of the [[request Body]].