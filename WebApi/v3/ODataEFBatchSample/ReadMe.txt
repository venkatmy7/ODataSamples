ODataEFBatchSample
-----------------

This sample shows how to use request batching in Web API 2 OData with transactions using 
Entity Framework and datajs. Batching is a Web API feature that allows a customer to pack 
several API requests and send them to the Web API service in one HTTP request and receive
a single HTTP response with the response to all their requests. This way, the client can 
optimize calls to the server and improve the latency and scalability of its service.

For more information about request batching support check:
http://blogs.msdn.com/b/webdev/archive/2013/11/01/introducing-batch-support-in-web-api-and-web-api-odata.aspx
http://aspnetwebstack.codeplex.com/wikipage?title=Web%20API%20Request%20Batching&referringTitle=Specs

This sample is provided as part of the OData WebApi sample repository at
https://github.com/OData/ODataSamples