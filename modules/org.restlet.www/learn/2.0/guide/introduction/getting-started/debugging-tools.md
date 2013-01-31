Debugging tools
===============

Introduction
============

As a set of pure Java library, the Restlet framework can easily be
debugged in your favorite IDE. All the source code is available, making
debugging session even easier by going inside the Restlet code if
necessary.

A good way to start a debugging session is to put a breakpoint inside
the handle() method or inside the constructor of your Resource subclass.
Think also about turning one the access and application
[loggings](http://web.archive.org/web/20111207161545/http://wiki.restlet.org/docs_2.0/13-restlet/275-restlet/311-restlet/101-restlet.html "Logging").

Tools
=====

Regarding protocol debugging, we recommand the you install tools such
as:

-   [cURL](http://web.archive.org/web/20111207161545/http://curl.haxx.se/)
    : command line HTTP client for Unix
-   [WireShark](http://web.archive.org/web/20111207161545/http://www.wireshark.org/)
    : advanced network analyzer working at the IP or TCP or HTTP levels
-   [Poster](http://web.archive.org/web/20111207161545/http://code.google.com/p/poster-extension/)
    : FireFox extension to test RESTful Web applications
-   [Netcat](http://web.archive.org/web/20111207161545/http://netcat.sourceforge.net/)
    : swiss-army knife for TCP/IP.
-   [tcpmon](http://web.archive.org/web/20111207161545/https://tcpmon.dev.java.net/):
    Java utility that monitors a TCP connection.
-   etc.
