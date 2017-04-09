# go-elm

Bootstrap app to get started quickly with Go + Elm application.

## Requirements

Install Elm and Go.

## Compiling

First, install the required Elm packages:

```
elm-package install
```

Then, you can build your application and the Go server that is going to serve your Elm content.

```
elm-make ./elm-src/App.elm --output static/js/app.js
go build server/server.go
```

### Running the server

```
./server
```

