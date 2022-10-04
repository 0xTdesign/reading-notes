# Class 7

Readings: REST



Who is Roy Fielding?

Roy Thomas Fielding is an American computer scientist, one of the principal authors of the HTTP specification and the originator of the Representational State Transfer architectural style.

Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?


What is the HTTP protocol that Fielding and his friends created?

fielding and seven webmasters started the Apache Group to redesign and maintain the public domain HTTP server

What does a GET do?

It uses to request data from a specified recourse 

What does a POST do?
Post is used to send data to a server. To create/ Update the resource. The data sent to the sever post is stored in the request body of HTTP request.

What does PUT do?

PUT is used to send data to a server. To create/update a resource. The difference between post and put are the request are IDEMPODNT. That is, calling the same put request multiple time will always produce the same result. In contrast, calling a post request repeatedly has side effects creating the same resource multiple times.

What does PATCH do?

PATCH is a method used to apply partially modifications resource.

Did you get your API key?

