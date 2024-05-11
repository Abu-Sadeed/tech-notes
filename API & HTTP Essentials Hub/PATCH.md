 HTTP PATCH is a request method used to partially update a resource on the server with the provided data. Unlike [PUT](PUT.md), which replaces the entire resource, PATCH applies partial modifications.

- **Usage**:    
    - Modify specific fields or properties of an existing  resource.
    - Partially update the content of a resource.

- **Characteristics**:
    - Partial resource representation sent in the [[request body]], containing only the fields to be updated.
    - Intended for partial updates and is not required to be [[idempotent]].

- **Examples**:
    - Updating the status or attributes of an entity.
    - Modifying specific fields of a user profile.

- **Response**: Includes [[HTTP status code]] indicating the outcome of the request and any additional data representations.

- **Security**: Apply appropriate [[authentication]] and [[authorization]] controls to restrict access to PATCH operations.

- **Best Practices**:
    - Use PATCH requests for partial updates to resources.
    - Provide clear documentation on the expected format of the request body and the fields that can be modified.