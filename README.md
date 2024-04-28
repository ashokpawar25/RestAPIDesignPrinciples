# Rest API Design Practices
Following are some REST API Design practices which we should follow .

## Good Practices

1. **Use Noun**: Use noun in url instead of verb.
2. **Use pluralized noun**: Use pluralized nouns to represent resources in API endpoints.
3. **Utilize HTTP Methods**: Use appropriate HTTP methods to perform actions on resources.
4. **Proper Status Codes**: Return appropriate HTTP status codes to indicate the status of the request.
5. **Input Validation**: Ensure data integrity and security by validating input data.
6. **Use hyphens for readability**: We can enhance URL readability by adding hyphens between words to separate elements.
7. **Error Handling**: Provide clear and informative error messages in case of errors.
8. **Pagination**: Implement pagination for endpoints returning large data sets.

## Bad Practices

1. **Misusing HTTP Methods**: Avoid using GET requests for data modification operations.
2. **Providing Wrong Status Code**: Provide accurate communication between client and server by returning appropriate HTTP status codes
3. **Poor Error Handling**: Ensure error messages are clear and actionable.
4. **Inconsistent Naming Conventions**: Maintain consistency in naming conventions.
5. **Overuse of Query Parameters**: Maintain API clarity and simplicity by limiting the number of query parameters.
6. **Not Providing Input validations**: Not providing input validations may fail working of an API's.
7. **No Pagination**: Implement pagination for endpoints with large data sets.
