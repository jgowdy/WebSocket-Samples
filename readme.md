#WebSocket Samples
This repository is a collection of WebSocket samples for .NET 4.5

##Getting Started
To be able to compile and run you will need the [Windows 8 developer preview](http://msdn.microsoft.com/en-us/windows/apps/br229516). Detailed instructions on the setup process are [here](http://www.paulbatum.com/2011/09/getting-started-with-websockets-in.html).

##Included Samples

### ASP.NET WebSocket Echo
The AspNetWebSocketEcho sample is a simple WebSocket echo server implemented using an IHttpHandler. Includes [annotated source](http://paulbatum.github.com/WebSocket-Samples/AspNetWebSocketEcho/).

### HttpListener WebSocket Echo
The HttpListenerWebSocketEcho sample is another echo sample but this one is a binary streaming echo using WinRT as the client and HttpListener as the server.

### WCF Echo
Yet another echo sample, this one is the WCF version of the AspNetWebSocketEcho.

### ASP.NET Chat
The AspNetChat sample demonstrates using the Broadcast method on WebSocketCollection for implementing a simple chat server.

### WCF NetHttpBinding
The WCFNetHttpBinding sample demonstrates traditional WCF service based development using the new NetHttpBinding. This binding uses WebSockets automatically when used with a duplex contract (i.e. a contract that has a callback contract).

##Other Samples
If you are looking for the samples that Stefan and I demonstrated in our [BUILD 2011 talk](http://channel9.msdn.com/Events/BUILD/BUILD2011/SAC-807T), these have their own repositories:

* [BUILD 2011 WebSocket Chat Samples](https://github.com/paulbatum/BUILD-2011-WebSocket-Chat-Samples)
* [Push Frenzy](https://github.com/paulbatum/PushFrenzy)