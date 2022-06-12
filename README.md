# Day02-assignment
Write a blog on Difference between HTTP1.1 vs HTTP2
Ans:  
INTRODUCTION:

    The Hypertext Transfer Protocol, or HTTP, is an application protocol that has been the de facto standard for communication on the World Wide Web since its invention in 1989. From the release of HTTP/1.1 in 1997 until recently, there have been few revisions to the protocol. 
    
ABOUT HTTP1.1 vs HTTP2

    HTTP  Hyper Text Transfer Protoco developed by Timothy Berners-Lee in 1989 as a communication standard for the World Wide Web, HTTP is a top-level application protocol that exchanges information between a client computer and a local or remote web server.HTTP1 loads a single request for every TCP connection, while HTTP2 avoids network delay by using multiplexing. HTTP is a network delay sensitive protocol in the sense that if there is less network delay, then the page loads faster.
    
High level Differences between HTTP/2 and HTTP/1.1:

    HTTP2 is binary, instead of textual
    HTTP2 is fully multiplexed, instead of ordered and blocking
    HTTP2 uses header compression to reduce overhead
    HTTP2 allows servers to “push” responses proactively into client caches    
    
RELIABILITY AND USES:

HTTP1.1:
   
    Works on the textual format. Client sends a text-based request to a server. .It compresses data by itself.
    Its time to load and send even a single pictures is comparitively very very less when compares to the previous version.
    The main advantage of using http1.1 is its more reliable because its acknowlegding each and every data.
    For examples: Online money tranfer, emails etc
    
HTTP2:
  
    Works on the binary protocol. 
    Its time to load and send even a single pictures is comparitively very very less when compares to the http1.1.
    The main advantage of using http2 is its more time saving.But itnwas not completlely implemented
    The http2 is under still in progress not fully implemented.


2.Write a blog about objects and its internal representation in Javascript

 
 About Objects:
 
    An object is a standalone entity, with properties and type. It has an entity having state and behavior (properties and method). For example: car, pen, bike, chair, glass, keyboard, monitor etc. JavaScript is an object-based language. Java is a heavily object-oriented programming language. When you do work in Java, you use objects to get the job done. You create objects, modify them, move them around, change their variables, call their methods, and combine them with other objects.
    
Internal representaion of objects:

   Objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. objects in JavaScript may also be created using the constructors, Object Constructor or the prototype pattern. we have to follow the syntax's to create objects.   
   
For example: 
 
   Syntax:  var <object-name> = {key1: value1, key2: value2,... keyN: valueN};
   let bike = {name: 'SuperSport', maker:'Ducati', engine:'937cc'};
   let student = (name: 'AAA', rollno: '000');  
    
    
    
    
    
    
