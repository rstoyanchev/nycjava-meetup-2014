!SLIDE subsection

# WebSocket Apps<br>in Java and Spring
## Rossen Stoyanchev
## [@rstoya05](https://twitter.com/rstoya05)

!SLIDE small center
# What is WebSocket?

!SLIDE small center
# Sockets have been around

!SLIDE small center
# Longer than our careers

!SLIDE small center
# `java.net.Socket`
<br>
# `@since JDK 1.0`

!SLIDE small center
# What is a __"Web"__Socket?

!SLIDE small center
# Have you ever had to
# display "live" data?

!SLIDE small center
# ... in a browser

!SLIDE small center
# Uses cases range
<br>
## Simple: breaking news, chat
## Advanced: financial, games, collaboration

!SLIDE small bullets incremental
# Have we done it before?

* Flash
* ActiveX
* Server-Sent Events
* XHR long polling
* XHR streaming
* etc......

!SLIDE small bullets incremental
# WebSocket Protocol

* [RFC 6455](http://tools.ietf.org/html/rfc6455)
* Finalized December 2011

!SLIDE small bullets incremental
# "Web"Socket in a nutshell

* HTTP handshake request
* Underlying TCP socket remains open
* __Bi-directional__ communication
* Thin layer over TCP --<br>split byte stream into messages

!SLIDE small bullets incremental
# W3C WebSocket API

* Candidate recommendation since Sep 2012
* Supported in most browsers
* Except on IE < 10 !
* We'll come back to this (don't leave yet)


