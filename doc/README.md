Hinka Core
=====================

Setup
---------------------
[Hinka Core](https://www.hinka.tech/) is the original Hinka client and it builds the backbone of the network. However, it downloads and stores the entire history of Hinka transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run Hinka on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/hinka-qt (GUI, 32-bit) or bin/32/hinkad (headless, 32-bit)
- bin/64/hinka-qt (GUI, 64-bit) or bin/64/hinkad (headless, 64-bit)

### Windows

Unpack the files into a directory, and then run hinka-qt.exe.

### OSX

Drag Hinka-Qt to your applications folder, and then run Hinka-Qt.

### Need Help?

* Ask for help on [BitcoinTalk](https://bitcointalk.org/index.php)
* Join one of our Discord groups [Hinka Discord Groups](https://discord.gg/4pqx94D).

Building
---------------------
The following are developer notes on how to build Hinka on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources

* Discuss on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=4491298.0) .
* Join the [Hinka-Dev] Discord groups [Hinka Discord Groups](https://discord.gg/4pqx94D).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
