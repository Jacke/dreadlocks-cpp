# Dreadlocks: runtime deadlock detection using bloom-filters
Implementation of [this](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.137.6175&rep=rep1&type=pdf) algorithm in C++ using [this](https://libbloom.codeplex.com/) Bloom filter library.

P.S. I have modified code in ```bloom_filter.hpp```, because there was a bug in copy constructor: there was no default initialization of ```bit_table``` pointer which caused to segmentation fault.
