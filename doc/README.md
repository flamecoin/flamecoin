Flamecoin Core
=============

Setup
---------------------
Flamecoin Core is the original Flamecoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Flamecoin transactions depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few minutes to a few hours or more.

To download Flamecoin Core, visit [flamecoin.co](https://flamecoin.co).

Running
---------------------
The following are some helpful notes on how to run Flamecoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/flamecoin-qt` (GUI) or
- `bin/flamecoind` (headless)

### Windows

Unpack the files into a directory, and then run flamecoin-qt.exe.

### OS X

Drag Flamecoin-Core to your applications folder, and then run Flamecoin-Core.

### Need Help?

* Visit the offical website [Flamecoin.co](https://flamecoin.co/)

Building
---------------------
The following are developer notes on how to build Flamecoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Flamecoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/flamecoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [Flamecoin Forums](https://flamecoin.co/forum/)
* Discuss general Flamecoin development on #development on Discord. If you are not in the discord server, [join here.](https://discord.gg/jVzzxju)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
