---
layout: default
title: tinyPack
---

tinyPack provides data compression algorithms for TinyOS.

It seems that most data compression algorithms require several
kilobytes of memory to achieve useful compression. TinyPack is
aimed at data compression algorithms that require at most hundreds
of bytes. Currently two variants of
[LZSS](http://en.wikipedia.org/wiki/Lempel–Ziv–Storer–Szymanski)
have been implemented. If you know of other existing data
compression implementations for sensor networks, or algorithms
worth implementing please let me know.

Download
--------

The [source](https://github.com/mtancret/tinyPack) is freely
available. It is licensed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
