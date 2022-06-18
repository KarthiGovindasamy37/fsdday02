Difference between HTTP1.1 vs HTTP2

HTTP - Hypertext Transfer Protocol is used to make client-server communication. By using http user sends the request to the server and the serversends the response to the client.http1.1 was developed in 1997 and http2 was devloped in 2015.


HTTP1.1:
         In http1.1 a keep alive heade is send with a first request.so whenever the client sends request to the server a tcp connection is made.when the second request is made that request is also using the same header.so all the requests are using the same header that make delay in getting response because whenever a new request made all the older requests are processed.it works on textual format.
         
         
HTTP2 :      
       http2 works on spdy potocol.it converts all the textual messages into binary format.it uses HPACK to split data from header and compress the header.it uses one tcp connection to multiple requests.the server sends all the files like CSS & JS without the request of the client using the PUSH frame.
       
       
Objects and its internal representation in Javascript


                                                      Objects holds many values in the form of key:value pair.these key value pairs are called as property name and property value respectively.we can parse the object by using object.property name syntax or object["property name"] syntax.
