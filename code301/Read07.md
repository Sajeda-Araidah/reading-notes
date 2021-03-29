# (REST)  Representational state transfer 
is a software architectural style which uses a subset of HTTP. It is commonly used to create interactive applications that use Web services. A Web service that follows these guidelines is called RESTful. Such a Web service must provide its Web resources in a textual representation and allow them to be read and modified with a stateless protocol and a predefined set of operations. This approach allows interoperability between the computer systems on the Internet that provide these services. REST is an alternative to, for example, SOAP as way to access a Web service.

"Web resources" were first defined on the World Wide Web as documents or files identified by their URLs. Today, the definition is much more generic and abstract, and includes every thing, entity, or action that can be identified, named, addressed, handled, or performed in any way on the Web. In a RESTful Web service, requests made to a resource's URI elicit a response with a payload formatted in HTML, XML, JSON, or some other format. For example, the response can confirm that the resource state has been changed. The response can also include hypertext links to related resources. The most common protocol for these requests and responses is HTTP. It provides operations (HTTP methods) GET, HEAD, POST, PUT, PATCH, DELETE, CONNECT, OPTIONS and TRACE.


# SuperAgent
SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!

 `request`

  ` .post('/api/pet')`

  ` .send({ name: 'Manny', species: 'cat' })`

   `.set('X-API-Key', 'foobar')`

   `.set('Accept', 'application/json')`

   `.then(res => {`

    `  alert('yay got ' + JSON.stringify(res.body));`

 `  });`


 # GET requests
The .query() method accepts objects, which when used with the GET method will form a query-string. The following will produce the path /search?query=Manny&range=1..5&order=desc.

 `request`

  ` .get('/search')`

  ` .query({ query: 'Manny' })`

  ` .query({ range: '1..5' })`

   `.query({ order: 'desc' })`

   `.then(res => {`

   `});`

# POST / PUT requests
A typical JSON POST request might look a little like the following, where we set the Content-Type header field appropriately, and "write" some data, in this case just a JSON string.

  `request.post('/user')`

  `.set('Content-Type', 'application/json')`

    `.send('{"name":"tj","pet":"tobi"}')`

   ` .then(callback)`

    `.catch(errorCallback)`

Since JSON is undoubtedly the most common, it's the default! The following example is equivalent to the previous.

 ` request.post('/user')`
   ` .send({ name: 'tj', pet: 'tobi' })`
    `.then(callback, errorCallback)`

# What is an API? (Application Programming Interface)
API is the acronym for Application Programming Interface, which is a software intermediary that allows two applications to talk to each other. Each time you use an app like Facebook, send an instant message, or check the weather on your phone, you’re using an API.


![Pic](API-page-graphic.png)