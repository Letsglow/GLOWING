Glow integration/staging tree
================================

http://www.letsglowcoin.com

Copyright (c) 2018 Glow Developers

What is Glow?
----------------

Glow is a lite version of Bitcoin using scrypt as a proof-of-work algorithm with 
eventual switch to POE.

Name: Glow
Ticker: GLO
Algorithm: POW Scrypt/POE at designated Block
Block Reward: 50
Maturity: 20 Blocks
Transaction Confirmations: 6 Blocks
Max Supply: 24,705,882
Halving : 210,000
RPC port: 35080
P2P port: 35079
Premine: 3705882 (15%) (10% for Glow Fund / 5% to When Lambo Fund)


Check out our software at wwww.letsglowcoin.com

License
-------

Glow is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Devs are independently working on their own trees and then will submit pull requests to 
fix issues and implement new features.

For minor changes, our developers will pull update. If the community wants to
release a more substantial update, the community will decide collectivelly.

The `master` branch is regularly updated and tested to the most stable version.
[Tags](https://github.com/glow-project/glow/tags) 


Testing
-------

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./glow-qt_test

