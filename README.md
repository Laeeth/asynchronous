[![Build Status](https://travis-ci.org/dcarp/asynchronous.png?branch=master)](https://travis-ci.org/dcarp/asynchronous)

This module provides infrastructure for writing single-threaded concurrent code using coroutines, multiplexing I/O access over sockets and other resources, running network clients and servers, and other related primitives.

*It starts as a port of python 3 [asyncio library](https://docs.python.org/3/library/asyncio.html).*

[API Reference](http://dcarp.github.io/asynchronous/index.html)

Implementation status:

1. Timers (done)
2. Futures, Tasks (done)
3. Sockets (done)
4. Streams (done)
5. Subprocesses (not implemented)
6. Locks and semaphores (done)
7. Queues (done)
