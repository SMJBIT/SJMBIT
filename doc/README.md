SJMBIT 0.8.2 BETA 
====================

Copyright (c) 2009-2013 SJMBIT Developers

Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](http://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.


Intro
---------------------
SJMBIT is a free open source peer-to-peer electronic cash system that is
completely decentralized, without the need for a central server or trusted
parties.  Users hold the crypto keys to their own money and transact directly
with each other, with the help of a P2P network to check for double-spending.


Setup
---------------------
[SJMBIT-Qt](http://sjmbit.org/en/download) is the original SJMBIT client and it builds the backbone of the network. However, it downloads and stores the entire history of SJMBIT transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

### Unix

You need the Qt4 run-time libraries to run SJMBIT-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/sjmbit-qt (GUI, 32-bit)
- bin/32/sjmbitd (headless, 32-bit)
- bin/64/sjmbit-qt (GUI, 64-bit)
- bin/64/sjmbitd (headless, 64-bit)



### Windows

Unpack the files into a directory and run sjmbit-qt.exe.

### Need Help?

* See the documentation at the [SJMBIT Wiki](https://en.sjmbit.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#sjmbit](http://webchat.freenode.net?channels=sjmbit) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=sjmbit).
* Ask for help on the [SJMBITTalk](https://sjmbittalk.org/) forums.

Building
---------------------
- [SJMBIT-Qt Readme](readme-qt.md)
- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-msw.md)

Development
---------------------
- [Coding Guidelines](coding.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/sjmbit/doxygen/)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)

Other Pages
---------------------
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)