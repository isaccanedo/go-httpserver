# Simple HTTP Server

So simple, almost no reasons to commit.

## Prerequisites

[Go](http://golang.org/dl/)


## Get and install

    go get github.com/isaccanedo/go-httpserver
    go install github.com/isaccanedo/go-httpserver

## Run

Once installed, run via:

    httpserver

Defaults to current directory for HTML, optional `-web` param for
HTML dir location.

Defaults to 8085 for port, optional `-port` param for port.

Example (redundant, since these are the defaults)

    httpserver -port 8085 -web .
