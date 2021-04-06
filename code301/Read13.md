# Sending Form Data 
![Pic](https://i2.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/01/HTML-Form.jpg?fit=1920%2C1080&ssl=1)



## Client/server architecture
the web uses a client/server architecture that can be summarized as follows. a client (usually a web browser) sends a request to a server (most of the time a web server like Apache, **Nginx**, **IIS**, **Tomcat**, *-etc**.), using the HTTP protocol. The server answers the request using the same protocol.

![pic](https://madooei.github.io/cs421_sp20_homepage/assets/client-server-1.png)

An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.

## On the client side: defining how to send the data
The <form> element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button. The two most important attributes are action and method.

### The action attribute
The action attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page ,Example :

```<form action="https://example.com">```


### The method attribute
The method attribute defines how data is sent. The HTTP protocol provides several ways to perform a request; HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method


#### The GET method
The ```GET``` method is the method used by the browser to ask the server to send back a given resource

#### The POST method
The ```POST``` method is a little different. It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result." If a form is sent using this method, the data is appended to the body of the HTTP request.