Mcoin Core
=============

Setup
---------------------
Mcoin Core is the original Mcoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Mcoin transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Mcoin Core, visit [mcoin.org](https://mcoin.org).

Running
---------------------
The following are some helpful notes on how to run Mcoin Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/mcoin-qt` (GUI) or
- `bin/mcoind` (headless)

### Windows

Unpack the files into a directory, and then run mcoin-qt.exe.

### macOS

Drag Mcoin Core to your applications folder, and then run Mcoin Core.

### Need Help?

* See the documentation at the [Mcoin Wiki](https://mcoin.info/)
for help and more information.
* Ask for help on [#mcoin](http://webchat.freenode.net?channels=mcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=mcoin).
* Ask for help on the [McoinTalk](https://mcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Mcoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Mcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [McoinTalk](https://mcointalk.io/) forums.
* Discuss general Mcoin development on #mcoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=mcoin-dev).

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
