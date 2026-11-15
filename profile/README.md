## byo-io: bring your own I/O

Sans-I/O networking libraries in C. Each library is a small, deterministic
state machine: your application owns the socket, the clock and the event
loop, and the library tells it what to send and how long it can sleep.

| Project | Description |
|---|---|
| [libpcp](https://github.com/byo-io/libpcp) | Port Control Protocol ([RFC 6887](https://www.rfc-editor.org/rfc/rfc6887)) client |
| [libnatpmp](https://github.com/byo-io/libnatpmp) | NAT-PMP ([RFC 6886](https://www.rfc-editor.org/rfc/rfc6886)) client |

Inspired by the [sans-I/O](https://sans-io.readthedocs.io/) approach.
More at [byo-io.github.io](https://byo-io.github.io).
