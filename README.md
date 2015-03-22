# ChatServer

[![Build Status](https://travis-ci.org/scravy/ChatServer.svg)](https://travis-ci.org/scravy/ChatServer)

A simple server that distributes incoming messages to all connected clients.
Written in [Concurrent Haskell](http://research.microsoft.com/en-us/um/people/simonpj/papers/concurrent-haskell.pdf).

## Running

Install the [Haskell Platform](http://www.haskell.org/platform) first.

    git clone https://github.com/scravy/ChatServer.git
    cabal run 4000

You can specify a custom port instead of `4000`.

## Using

Once the Chat server is started, it is ready to accept connection.
You can connect for example using `netcat` (`nc`).

    nc localhost 4000



