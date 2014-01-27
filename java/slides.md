!SLIDE subsection
# WebSocket and Java

!SLIDE small bullets incremental
# JSR-356

* WebSocket API for Java
* Spec completed May 2013 (part of Java 7)
* No Java EE 7 servers yet
* However Tomcat, Jetty support it

!SLIDE small bullets incremental
# Before JSR-356

* Pre-existing support in Tomcat/Jetty/Caucho/Grizzly
* All complete re-writes after JSR-356
* jWebSocket -- higher level channels, events<br>built on Netty/Mina/Jetty/Tomcat
* Kaazing -- commercial,<br>higher-level messaging (JMS, AMQP, XMPP)

!SLIDE small bullets incremental
# After JSR-356

* Convergance of APIs across Servlet containers
* Theoreticlaly not tied to Servlet API
* Will other servers implement it?
* What does it even mean<br>for higher level APIs (jWebSocket/Kaazing)?

!SLIDE small bullets incremental
# Practically Speaking

* JSR-356 will be in all Java 7 servers
* So it's important to a majority of developers
* Java ecosystem however is wider--<br>other WebSocket servers
* Also with higher level messaging<br>WebSocket APIs are not what apps use

!SLIDE small bullets incremental
# Current Status by Server

* Tomcat 8 (at RC10) + backport to Tomcat 7.0.47+<br><em>(pre-existing Tomcat 7 support removed)</em>
* Jetty 9 new (native) WebSocket implementation<br>Jetty 9.1 adds JSR-356 layer
* Glassfish 4 with Tyrus WebSocket engine
* WildFly/Undertow (currently 8.0 CR1)

