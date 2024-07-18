# HTTP 

- n DevOps networking, HTTP (Hypertext Transfer Protocol) is a communication protocol that transmits data over the internet. It is the foundation of the World Wide Web and is responsible for how we interact with web pages.

<br>

### a. HTTP Methods

- In DevOps networking, HTTP Methods are the actions or operations performed on resources identified by URLs in the HTTP protocol. These HTTP methods specify how a client can interact with a web server to retrieve or manipulate information.

<br>

- **HTTP Request Methods** : HTTP methods are a set of requests used to communicate with a web server. The methods specify what action to perform on a resource. The most common HTTP methods are the following.

    <br>

    - ***GET :***
    retrieves a resource from the server
    
    <br>

    - **POST :**
    submits data to be processed to a specific resource
    
    <br>

    - **PUT :**
    updates a resource on the server

    <br>
    
    - **DELETE :**
    removes a resource from the server

    <br>
    
    - **PATCH :**
    partially updates a resource on the server
<br>

## b. HTTP Response Codes

- HTTP response codes are a set of standardized codes that a web server returns to the client to indicate the success or failure of an HTTP request.

<br>

- **Categories of HTTP responses :** In DevOps networking, One can group the response codes into categories that describe the type of response.

    <br>

    - ***1xx: Informational responses***
        - These codes convey the request status. They indicate the server has received the request and is currently processing it.
        - E.g., 100 Continue, 101 Switching Protocols

    <br>
    
    - ***2xx: Success responses***
        - These codes signify the server has successfully received, understood and accepted the request.
        - E.g., 200 OK, 201 Created, 204 No Content.
    
    <br>

    - ***3xx: Redirection responses***
        - These codes tell the client she needs to take further action to complete the request.
        - E.g., 301 Moved Permanently, 302 Found, 307 Temporary Redirect.
    
    <br>

    - ***4xx: Client error responses***
        - Indicate client-side errors, such as a missing or incorrect parameter.
        - E.g., 400 Bad Request, 401 Unauthorized,403 Forbidden, 404 Not Found.
    
    <br>

    - **5xx: Server error responses**
        - ndicate server-side errors, such as a server overload or internal server error.
        - E.g., 500 Internal Server Error, 503 Service Unavailable.

<br>

- These codes are often used for background communication between the client and server and are not as critical for users to be aware of. However, the browser displays error codes because they are vital for users to understand when something has gone wrong with their request.

<br>

- The below image shows what an error 403 Forbidden looks like to the user:

    <br>

    ![image](/resources_img/Networking/HTTP/Google_403_error.png)

    <br>


## c. HTTP Headers

- In DevOps networking, HTTP headers are a critical component of the HTTP protocol for exchanging data between clients and servers. They provide important information about the client, server, and content transmitted, which is essential for handling the HTTP request and response messages.

- Here are some rudimentary things to know about HTTP headers:



- An HTTP header is a piece of information that accompanies an HTTP request or response.

<br>

- It has a name-value pair separated by a colon ( : ), with one or more headers separated by a line break.

<br>

- There are four types of HTTP headers. Each of these headers serves a specific purpose in the HTTP protocol.

    <br>

    - General headers :
        
        <br>
      
      - These headers in HTTP provide general information about the message, such as the date and time of the sent message, and apply to both requests and responses.

        <br>

      - Examples include Request URL, Request Method, and Status Code.

        <br>

        ![image](/resources_img/Networking/HTTP/General_header.png)

    <br>

    - Request headers :
        
        <br>
      
      - These headers provide information about the client or the requested resource.

        <br>

      - Examples include User-Agent, Accept, and Authorization.

        <br>

        ![image](/resources_img/Networking/HTTP/Request_header.png)

    <br>

    - Response headers:

        <br>
      
      - In DevOps networking, response headers provide information about the server response or the returned resource.

        <br>

      - Examples of response headers include Content-Type, Content-Length, and Server.

        <br>

        ![image](/resources_img/Networking/HTTP/Responce_header_1.png)
        ![image](/resources_img/Networking/HTTP/Responce_Header_2.png)

    <br>

    - Entity headers:

        <br>

        - These headers describe the content of the message body.

        <br>

        - Examples include Content-Encoding, Content-Language, and Content-Disposition.
  
    <br>