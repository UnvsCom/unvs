UNVS 
=============

<b>PLEASE NOTE THIS IS STILL A HIGHLY EXPERIMENTAL PROJECT. 
----------------
WE ARE STILL IN DEVELOPMENT STAGES. USE AT YOUR OWN RISK. WE ACCEPT NO LIABILITY IN ANY INSTANCE & NO GUARANTEE NOR WARRANTY IS PROVIDED. DEVELOPED FOR ENTERTAINMENT - USE IT FOR FUN !</b>

https://UNVS.com

Copyright (c) 2009-2014 Bitcoin Developers.
 
Copyright (c) 2011-2014 Litecoin Developers.  

Copyright (c) 2023 UNVS Developers.

What is UNVS?
----------------

UNVS is a lite version of Bitcoin using scrypt as a proof-of-work algorithm POW (also a fork of Litecoin).
 - 2.5 minute block targets
 - subsidy halves in 525,450 blocks (~2.5 years)
 - ~98 million total coins
 - 50 coins per block
 - 576 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the UNVS client software, see https://UNVS.com/Wallet

License
-------

UNVS is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT

Development process
-------------------

We are continually developing in-house with our own team, but we also receive assistance from freelance developers and community driven support.

We are still in the early stages. Bug fixes, patches and such like will be rolled out in stages. Use our services for FUN & Entertainment only !

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the UNVS
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/unvs-project/unvs/tags) are created
regularly to indicate new official, stable release versions of UNVS.

Testing
-------

Testing and code review is a continual task. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money. Again, we stress.. Only use this project for FUN !

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./unvs-qt_test

