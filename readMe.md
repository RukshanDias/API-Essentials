# API Essentials

-   API - Application Programming Interface. Interface between 1 piece of software to another.
-   Mostly use JSON language.
-   ![](imgs/how_API_works.png)
-   API will call (request) a certain end-point, and receive information as response.
-   The endpoint will be defined as a url.

### API URLs

-   API url will be used as the endpoint to access the information.
-   <img src="imgs/api_url_structure.png" width="500">
-   2 types of parameters:
    1. Path parameter
    2. Query parameter

#### Query Parameters

-   Set of key-value parameter attached at the end of url to filter out information.
-   Starts with '**?**'
-   For multiple queries use '**&**'
-   Example:
    -   <img src="imgs/query_parameter_example.png" width="500">
    -   1st parameter: **color**. 2nd parameter: **sort**.
-   Use cases of URL parameters::
    -   <img src="imgs/url_parameter_use-cases.png" width="400">

### API Request Methods

1. **GET**: retrieve data
2. **POST**: send data
3. **PUT**: update data
4. **DELETE**: delete data
5. **PATCH**: partial update data

### Types of API Architectures ([view](https://www.youtube.com/watch?v=4vLxWqE94l4))

1. **REST**: Stateless communication over HTTP using CRUD operations.
2. **GraphQL**: Query language for flexible data retrieval with a single endpoint.
3. **SOAP**: Protocol for structured data exchange via XML over HTTP or SMTP.
4. **gRPC**: High-performance RPC framework using Protocol Buffers for efficient communication.
5. **WebSocket**: Full-duplex communication for real-time data transfer.
6. **WebHook**: Real-time client updates over HTTP.

<img src="imgs/API architectures.gif" width="400">

---
