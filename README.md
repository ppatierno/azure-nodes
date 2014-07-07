# Microsoft Azure nodes for Node-RED

This project provides a set of nodes for [Node-RED](http://nodered.org/) that makes it easy to interact with Microsoft Azure Services.

## Documentation

The official documentation is available in the related [Wiki](https://github.com/ppatierno/azure-nodes/wiki) pages.

Current version supports the following Microsoft Azure Services.

Service Bus

1. Sending and receiving messages to/from a queue;
2. Sending messages to a topic and receiving messages from subscription;

## Installation

The library is based on official [Microsoft Azure SDK for Node.js](https://github.com/Azure/azure-sdk-for-node). You need to install this SDK to work with Azure-Nodes. The simple way to do it is use Node Package Manager (NPM) and install ["azure" module] (https://www.npmjs.org/package/azure).

After this, you can copy library files (*.js and *.html) under "nodes" folder of Node-RED installation.

## Author

Azure-Nodes is a creation of [Paolo Patierno](http://mvp.microsoft.com/en-us/mvp/Paolo%20Patierno-5000734)

## Copyright and license

Copyright 2014 Paolo Patierno under [the Apache 2.0 license](LICENSE).
