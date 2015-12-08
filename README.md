libircppclient
==============
An easy-to-use IRC-client interface based on Boost.asio to send and receive data from IRC servers.

About
-----
* License: zlib License
* Bug reports: [https://github.com/Tmplt/libircppclient/issues](Github issues)

Design Goals
------------
* An easy library to connect to IRC servers and send data back and forth.
* Small but useful; do one thing and do it well.
* Full compliance with [RFC2813](https://tools.ietf.org/html/rfc2813) (or maybe [IRCv3](http://ircv3.net/) is a better idea?.
* Thread-safe and whatever C++ libraries should be.

TODO
----
- [ ] It compiles!
- [ ] Add Travis CI
- [ ] Add basic support
  - [ ] Connect to the server (and keep the connection alive)
  - [ ] Join channels
  - [ ] Send messages
- [ ] Full RFC2813/IRCv3 compliance
- [ ] Extensive documentation and code commenting.
- [ ] No "holy shit what was he thinking writing this code?"

Non-goals
---------
* Colour decoding/encoding

Dependencies
------------
* Boost.asio (tested with 1.59.0)
