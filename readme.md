LibGBA - CPP
============

What is it?
-----------

It's a C++ library for GBA homebrew development. Focused on better API and
abstraction, so programmers can focus more on game logic and call functions for
effects instead of thinking in a too low-level way.

Requirements
------------

A lot of statements are being written with C++11/14/17 features, so, the
requirements are:

- GCC 7.1 or above;
- DevKitPro (to compile for GBA ARMv4 ISA and ARM7TDMI processor).

To-Do's
-------

1. Allow non-Read-Only graphics API (currently all data must be `const`/in ROM,
   or else we couldn't have bitmaps bigger than 32KB).

Bibliography
------------

There are two main contributions for the knowledge necessary to make this
library: one is the greatly well explained tutorials [TONC by J
Vijn](http://www.coranac.com/tonc/text/toc.htm) (which I really want to thank
him for making it), and the other is the great [GBA Techical Manual by Martin
Korth](http://problemkaputt.de/gbatek.htm).