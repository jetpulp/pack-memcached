# pack-memcached

Shinken configuration pack for Memcached

This pack monitor memcache memory consumption, hit rate, connection and rate for all method (GET, DELETE, ...)

## Monitoring scripts

In the libexec folder you'll find the memcached.pl script writted by William Leibzon and released under GPL.

## Install

To install, simply get it from shinken.io: `shinken install memcached`.

_memcached.pl_ requires the *Cache::Memcached* library from CPAN. You can also install the version provided by your package manager. On Ubuntu/Debian system, that package is called `libcache-memcached-perl`.
