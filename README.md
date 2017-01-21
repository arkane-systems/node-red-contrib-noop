# node-red-contrib-noop

A Node-RED node that does nothing whatsoever. More specifically:

* It copies its input to its output unchanged.
* If there is no output, it discards its input silently.
* If there is no input... well, it does nothing.

Apart from obscure placeholder purposes, its single function is in simplifying many-to-many connections by providing a central node to route through, rather than needing a complex mesh of connections that would be easy to lose errors in.
