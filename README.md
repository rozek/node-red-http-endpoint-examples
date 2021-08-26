# node-red-http-examples #

This collection of HTTP(S)-related [Node-RED](https://nodered.org/) examples (with matching [Postman](https://www.postman.com/) Collections for testing) is mainly intended for my students, but parts of it might also be of more general interest

### Recommended Extensions ###

Independent of a specific Node-RED use case, the following extensions might be useful:

* node-red-contrib-components
* node-red-contrib-actionflows
* node-red-contrib-https

## Examples ##

As usual, the examples in this repository start small and simple, but become increasingly complex up to complete small applications. Their specification is stored in JSON format and may easily be imported into a Node-RED workspace. Preferrably, you should open a separate tab and insert the examples there.

### trivial HTTP(S) Server ###

The [first example](examples/trivial-http-server.json) is just to illustrate how easy it can be to implement a web service with Node-RED.

![](examples/trivial-http-server.png)

Import the source, "deploy" and ...
