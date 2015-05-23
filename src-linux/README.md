LFO COINS, when fully developed, WILL BE SCRYPT-POS/POI coins, and be accepted in every community on the globe.
V1.0 is ICO, V2.0 is POS acquisition, or fork, and V3.0 is POI integration at public launch. All three phases are working orders in themeselves. Each version addition serves their foundational priveledges, and are not bound in rules by themselves. In other words, all three are a work in progress for perfection.

LFO integration/staging tree
================================

http://coin.whatcomcountylfo.com

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Litecoin Developers

What is Local Family Owned?
----------------

LFO is a lite version of Bitcoin, similiar in nature to LITECOIN, using scrypt as a proof-of-work algorithm.
 - 7 minute block targets
 - subsidy halves in 750k blocks (~3.6years)
 - ~40,000,000.00 total coins

The rest is the same as Bitcoin.
 - 24 coins per block
 - 2016 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Litecoin client sofware, see http://www.litecoin.org.

License
-------

Litecoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------
The LFO COIN will be developed by the PoS (Proof of Stake) and PoI (Proof of Integrity) standards.
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Litecoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion (if they haven't already) on the
[mailing list](http://sourceforge.net/mailarchive/forum.php?forum_name=bitcoin-development).

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/bitcoin/bitcoin/tags) are created
regularly to indicate new official, stable release versions of Litecoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./litecoin-qt_test
    
    

