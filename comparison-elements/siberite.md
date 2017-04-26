# Siberite - https://github.com/wavii/darner
simple leveldb backed message queue server


## Description
Siberite is a simple leveldb backed message queue server
(twitter/kestrel, wavii/darner rewritten in Go).

Siberite is a very simple message queue server. Unlike in-memory servers such as redis, Siberite is designed to handle queues much larger than what can be held in RAM. And unlike enterprise queue servers such as RabbitMQ, Siberite keeps all messages out of process, using goleveldb as a persistent storage.


## License
- Apache 2.0
    - [@siberiteLicense]


## Development status
- Stale
    - Last version: 0.2.0 on 2013-03-18 [@siberiteRepository]
- Experimental
    - [@siberiteRepository]


## Server Platforms
- OSX
    - [@siberiteRepository]
- Linux
    - [@siberiteRepository]


## Protocol
- memcached
