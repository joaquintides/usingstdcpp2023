using std::cpp 2023
-------------------

Presentation from Joaquín Mª López Muñoz at [using std::cpp 2023](https://eventos.uc3m.es/93418/detail/using-std-cpp-2023.html)
and associated material.

[![Presentation video](https://img.youtube.com/vi/Rg8MZ5pJIJA/mqdefault.jpg)](https://youtu.be/Rg8MZ5pJIJA)


* [More than a rehash](https://github.com/joaquintides/usingstdcpp2023/raw/main/More%20than%20a%20rehash.pdf):
Boost 1.81 (Dec 2022) released `boost::unordered_flat_map`, a hashmap (unordered associative
container in C++ parlance) that relies on open addressing and SIMD techniques to provide
extremely high performance. In this talk, Joaquín will invite you to look under
`boost::unordered_flat_map`'s hood with him and learn about this container's data structure,
its key design elements and how it compares with other top-performance C++ hashmaps both in
theory and in practice. The talk finishes with a teaser on concurrent hashmaps arriving as
part of your Boost update later this year.
* Boost.Unordered [repo](https://github.com/boostorg/unordered/) and [docs](https://www.boost.org/libs/unordered/).
* [Benchmarks](https://github.com/boostorg/boost_unordered_benchmarks).
* [Code](https://github.com/joaquintides/boost_unordered_flat_map_stats) used to calculate
statistical properties of `boost::unordered_flat_map` and `absl::flat_hash_map`. 
