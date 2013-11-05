LevelDB
=======

Fork of http://code.google.com/p/leveldb

Original docs:

* [README] (README)
* [LICENSE] (LICENSE)
* [AUTHORS] (AUTHORS)
* [NEWS] (NEWS)
* [TODO] (TODO)
* [API] (doc/index.html)

Changes
-------

This fork differs from the official version of leveldb as follows:

* Installation is supported by the makefile.

Installation
------------

First, build the library with:
  
    make

Then, LevelDB can be installed using
  
    sudo make install
  
The install target in the Makefile is as described in issue #138 on the google tracker: http://code.google.com/p/leveldb/issues/detail?id=138.

You can set the following env vars before running `make` if you prefer different installation locations:
  
  * PREFIX (default is /usr/local)

  * LIBDIR (default is $PREFIX/lib)

  * INCLUDEDIR (default is $PREFIX/include)
