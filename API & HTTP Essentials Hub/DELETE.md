HTTP DELETE is a request method used to remove a resource from the server.

- **Usage**:
    - Delete an existing resource from the server.
    - Irreversible operation, as it permanently removes the resource.

- **Characteristics**:
    - No [[request Body]] is typically included.
    - Intended for [[idempotent]] operations.

- **Examples**:
    - Deleting a user account.
    - Removing a file from a server.

- **Response**: Includes [[HTTP status code]] indicating the outcome of the request.

- **Security**: Implement proper [authentication](Authentication.md) and [authorization](Authorization.md) checks to prevent unauthorized deletion of resources.

- **Best Practices**:
    - Use DELETE requests judiciously, as they permanently remove data.
    - Require additional confirmation for critical delete operations to prevent accidental data loss.