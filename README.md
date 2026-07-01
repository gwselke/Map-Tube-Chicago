A Map::Tube implementation for the Chicago L network.

This module allows to find the shortest route between any two given tube or
tram stations in Chicago. Since many stations in Chicago having the same name
are in fact different stations, this module disambiguates these names by
attaching the parenthesized line name. This also applies to stations of the
same name where an interchange is possible but requires a walk checking out
from one station and checking in at another (of the same name).

All interesting methods are provided by the role Map::Tube.

To build this module, use the classical steps:

* perl Makefile.PL
* make
* make test
* make install

(If you are using Srawberry Perl under Windows, you may want to replace "make"
with "gmake".)
