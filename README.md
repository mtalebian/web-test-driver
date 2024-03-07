# web-test-driver

Web Test Driver provides services for web-based test automation.

## APIs

### POST /driver/curl

Executes a web requests. If filename is specified saves response content to the file, otherwise returns response content as string.

-   Payload:
    -   **url**: string,
    -   **method**: "GET" | "POST" | "PUT" | "DELETE"
    -   **Data**: string
    -   **contentType**: string
    -   **proxyUrl**: string
    -   **fileName**: string
    -   **overwrite**: string
    -   **headers**: [ {"key": "value"} , ...]
    -   **cookies**: [ {"key": "value"} , ...]

*   Response:
