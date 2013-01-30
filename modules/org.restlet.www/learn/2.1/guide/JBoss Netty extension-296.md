JBoss Netty extension
=====================

Introduction
============

This connector is based on the [JBoss
Netty](http://web.archive.org/web/20101212040923/http://www.jboss.org/netty)
open-source web server.

Description
===========

This connector supports the following protocols: HTTP and HTTPS.

The list of supported specific parameters is available in the javadocs:

-   [Netty common
    parameters](http://web.archive.org/web/20101212040923/http://www.restlet.org/documentation/snapshot/jse/ext/org/restlet/ext/netty/NettyServerHelper.html)
-   [HTTP specific
    parameters](http://web.archive.org/web/20101212040923/http://www.restlet.org/documentation/snapshot/jse/ext/org/restlet/ext/netty/HttpServerHelper.html)
-   [HTTPS specific
    parameters](http://web.archive.org/web/20101212040923/http://www.restlet.org/documentation/snapshot/jse/ext/org/restlet/ext/netty/HttpsServerHelper.html)

For additional details, please consult the
[Javadocs](http://web.archive.org/web/20101212040923/http://www.restlet.org/documentation/2.0/jse/ext/org/restlet/ext/netty/package-summary.html).

Usage example
=============

HTTPS
-----

For general information on Netty HTTPS/SSL configuration, please read
[this
document](http://web.archive.org/web/20101212040923/http://www.jboss.org/file-access/default/members/netty/freezone/guide/3.1/html/architecture.html#d0e2074).
For configuration of the connector in a Restlet component, you will need
to set some of the HTTPS parameters listed above, for example:

    Server server = myComponent.getServers().add(Protocol.HTTPS, 8183);
    server.getContext().getParameters().add("keystorePath", "<your-path>");
    server.getContext().getParameters().add("keystorePassword", "<your-password>");
    server.getContext().getParameters().add("keyPassword", "<your-password>");

[Comments
(0)](http://web.archive.org/web/20101212040923/http://wiki.restlet.org/docs_2.1/13-restlet/28-restlet/296-restlet.html#)

Comments
[Hide](http://web.archive.org/web/20101212040923/http://wiki.restlet.org/docs_2.1/13-restlet/28-restlet/296-restlet.html#)
\
There are no comments.

Add a comment

Please log in to be able to add comments.