# go.smantic.dev/websocket

[![GoDoc](https://godoc.org/go.smantic.dev/websocket?status.svg)](https://godoc.org/go.smantic.dev/websocket)

WebSocket is a [Go](http://golang.org/) implementation of the
[WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol.

---

### Documentation

* [API Reference](https://pkg.go.dev/go.smantic.dev/websocket?tab=doc)
* [Chat example](https://github.com/smantic/websocket/tree/master/examples/chat)
* [Command example](https://github.com/smantic/websocket/tree/master/examples/command)
* [Client and server example](https://github.com/smantic/websocket/tree/master/examples/echo)
* [File watch example](https://github.com/smantic/websocket/tree/master/examples/filewatch)

### Status

 WebSocket package provides a complete and tested implementation of
the [WebSocket](http://www.rfc-editor.org/rfc/rfc6455.txt) protocol. The
package API is stable.

This project is a fork of gorilla/websocket.   
No feature development will be done on this package, only security issues and critical fixes.  
If you would like to raise an issue please contact me at tyler@smantic.dev  

### Installation

    go get go.smantic.dev/websocket

### Protocol Compliance

The WebSocket package passes the server tests in the [Autobahn Test
Suite](https://github.com/crossbario/autobahn-testsuite) using the application in the [examples/autobahn
subdirectory](https://github.com/smantic/websocket/tree/master/examples/autobahn).

