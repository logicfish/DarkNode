DarkNode
========

Unofficial TOR Server Bundle (tor+node.js)

Quick-and-dirty darknet web server using node-js over tor.  Serves static files from a folder, or create apps using express (or any node apps).

This does not proxify node, it simply creates a hidden service in Tor and exposes the http and optionally https ports, mapping them to the ports defined in node.
Both node and Tor must be running for the hidden service to function.

