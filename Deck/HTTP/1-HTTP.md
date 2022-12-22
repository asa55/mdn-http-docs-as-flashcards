##

Hypertext Transfer Protocol (HTTP) is an application-layer protocol for transmitting hypermedia documents, such as

%

HTML

##

HTTP was designed for communication between `_____` browsers and `_____` servers, but it can also be used for other purposes.

%

HTTP was designed for communication between **web** browsers and **web** servers, but it can also be used for other purposes.

##

HTTP follows a classical `_____` model, with a client opening a connection to make a request, then waiting until it receives a response.

%

HTTP follows a classical **client-server** model, with a client opening a connection to make a request, then waiting until it receives a response.

##

HTTP is a `_____` protocol, meaning that the server does not keep any data (state) between two requests.

%

HTTP is a **stateless** protocol, meaning that the server does not keep any data (state) between two requests.

##

Caching is very important for fast

%

Web sites

##

How HTTP Cookies work is defined by

%

RFC 6265

##

When serving an HTTP request, a server can send a `Set-Cookie` HTTP `_____` with the response. The client then returns the cookie's value with every request to the same server in the form of a Cookie request `_____`. The cookie can also be set to expire on a certain date, or restricted to a specific domain and path.

%

When serving an HTTP request, a server can send a `Set-Cookie` HTTP **header** with the response. The client then returns the cookie's value with every request to the same server in the form of a Cookie request **header**. The cookie can also be set to expire on a certain date, or restricted to a specific domain and path.

##

`_____` HTTP requests are HTTP requests for resources from a different domain than the domain of the resource making the request. For instance, an HTML page from Domain A (http://domaina.example/) makes a request for an image on Domain B (http://domainb.foo/image.jpg) via the img element.

%

**Cross-site** HTTP requests are HTTP requests for resources from a different domain than the domain of the resource making the request. For instance, an HTML page from Domain A (http://domaina.example/) makes a request for an image on Domain B (http://domainb.foo/image.jpg) via the img element.

##

Web pages today very commonly load cross-site resources, including CSS stylesheets, images, scripts, and other resources. `_____` (`_____`) allows web developers to control how their site reacts to cross-site requests.

%

Web pages today very commonly load cross-site resources, including CSS stylesheets, images, scripts, and other resources. **Cross-Origin Resource Sharing** (**CORS**) allows web developers to control how their site reacts to cross-site requests.

##

HTTP Client `_____` are a set of response headers that a server can use to proactively request information from a client about the device, network, user, and user-agent-specific preferences. The server can then determine which resources to send, based on the information that the client chooses to provide.

%

HTTP Client **Hints** are a set of response headers that a server can use to proactively request information from a client about the device, network, user, and user-agent-specific preferences. The server can then determine which resources to send, based on the information that the client chooses to provide.

##

HTTP Message `_____` are used to describe a resource, or the behavior of the server or the client. `_____` fields are kept in an IANA registry. IANA also maintains a registry of proposed new HTTP message `_____`.

%

HTTP Message **Headers** are used to describe a resource, or the behavior of the server or the client. **Header** fields are kept in an IANA registry. IANA also maintains a registry of proposed new HTTP message **headers**.

##

HTTP Status Response Codes indicate whether a specific HTTP request has been successfully completed. Responses are grouped in five classes:

- `_____`
- `_____`
- `_____`
- `_____`
- `_____`

%

- informational responses
- successful responses
- redirections
- client errors
- and servers errors

##

CSP directives, the Content-Security-Policy response header fields, allows website administrators to control resources the user agent is allowed to `_____` for a given page. With a few exceptions, policies mostly involve specifying server origins and script endpoints.

%

CSP directives, the Content-Security-Policy response header fields, allows website administrators to control resources the user agent is allowed to **load** for a given page. With a few exceptions, policies mostly involve specifying server origins and script endpoints.
