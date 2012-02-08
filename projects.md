# Projects:

C framework for easier (callback-oriented) TCP communication,
along with RPC client&server implementation for a proprietary
protocol (not unlike Lisp S-Exprs, or JSON-RPC). Unfortunately
locked in to customer.

Documentation extraction tool. (Not unlike Doxygen or javadoc.)
Extracts doc from source comments and creates a HTML page
hierarchy.

Build tool (inspired by imake). Preprocessor that acts as
a frontend to make and allows to state what sources there
are, not (just) how to treat them.

Java framework for implementing CRUD applications by just
giving a database table description and a layout (tabular
view plus entry fields); done ad-hoc during implementing
an application using it. Some bells and whistles, like
looking up status code translations in secondary tables,
and incrementally fetching data. (This was back in the
early days of java.)

Log-oriented file system, specifically designed to store
audio streams (essentially <int,blob> tuples) and to survive
random reboots without needing a file system check. Moderate
performance tuning.

A framework (in C) for allowing servers to run on multiple
machines to achieve redundancy. Including a layer on the
client side, the service can fail over to another host
even while API invocations from clients are underway.

Implement an audit log server and its connection to the
service being audited, using OpenSSL for connection
security.

Involvement in some parts of the implementation of a
japanese GPRS equivalent, network-side.

A custom package management system, designed on top of
an application execution framework, and to work with its
configuration files.

[Private] A railway simulation program, including
hooking up some real model signals to it.
