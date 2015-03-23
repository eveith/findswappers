Find Swappers
=============

Introduction
------------

`findswappers` is a Perl script that scans the `/proc` directory under linux
to find processes that use the swap space, and lists them in order of the
amount of swap used.

Installation
------------

findswappers is distributed as a Perl module. The installation procedure is
the same as with any other Perl Module:

    perl Makefile.PL
    make
    make test
    make install

LICENSE
-------

This program and its source code is distributed under the same license as Perl
5 iteslf.
