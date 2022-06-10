# consume-api-rest-javascript

# Waht is a REST API?
- An API (Application Program Interface) is the way the backend communicates with the frontend through an interface.

- Rest means (Representational State Transfer) it is used to make this communication through HTTP where we receive the information from the API through JSON.

# Communication flow between users, frontend and backend.
- Server Side Rendering (SSR): It is the communication flow in which the user makes a request, it reaches the backend and returns a visual response in HTML.

# Single Page Application (SPA)
- That exists thanks to JavaScript allows us this way of making requests to an API and bringing information to the HTML without having to reload the page from scratch.

# Endpoints and Query Parameters.
- An endpoint is a digital location through which an API receives requests to access a resource on the server. Typically it is a URL that provides the location of a specific resource.

# what are HTTP status codes?

1XX -> Affirmed Answers.
2XX -> Satisfactory Answers.
3XX -> Re-directions.
4XX -> Client error.
5XX -> Server error.

# Authentication.
- It consists of identifying who each one is. You don't know what permissions a person has, you don't know what that person can or can't do.

# Authorization.
- It is the one that tells us what permissions each person has, that is, if a person wants to go to the fridge to eat a cake, it is the one that says, wait, do you have permission to open the fridge? the cake.

# HTTP methods.

- Get: read data from server (read only).
- Head: retrieve data from headers (read only).
- Post: send data to server.
- Put/Patch: save data on the server.
- Delete: delete server data.

# What are HTTP Headers?

- HTTP Headers are the central part of HTTP requests and responses and convey information about the client's browser, the requested page or the server.
Headers are KEY: value schemas that contain information about the HTTP request and the browser. Here are also the data of the.

# HTTP headers.
- Content Type
- Authorization
- Cookies
- Location

# Header of Content Type.
- Application
- Audio
- Image
- Multipart
- Text
- Video
- VND

# Image
- image/gif
- image/jpeg
- image/png
- image/x-icon
- image/svg + xml

# Multipart
- multipart/mixed
- multipart/alternative
- multipart/related
- multipart/form-data

# Text
- text/csc
- text/csv
- text/html
- text/plain
- text/xml

# Video
- audio/mpeg
- audio/x-mx-wma
- audio/vnd.rn-realaudio
- audio/x-wav

# VND
- application/vnd.ms-excel
- application/vnd.ms-powerpoint
- application/msword

# Axios JS libraries to consume API's
## http clients
- Axes
- Fetch.js
- node-fetch (for node.js)
- request (for node.js)

# Properties from fetch

### Modes
- Cors
- No-cors
- Same-origin

### Cache
- Default
- No-store
- Reolad
- No-cache
- Force-cache
- Only-if-cache

### Redirect
- Follow
- Error
- Manual

## Graph QL
- Empowered clients
- All request on the same endpoint

## Web Sockest
- leave the "tunnel open"
- useful for real-time applications ("instantaneous" communication)

## Web 3.0
- Dapps: decentralized applications