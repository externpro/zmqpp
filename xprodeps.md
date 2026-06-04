# zmqpp dependencies

|project|license [^_l]|description [dependencies]|version|source|diff [^_d]|
|-------|-------------|--------------------------|-------|------|----------|
|<a id='zmqpp' />[zmqpp](https://zeromq.github.io/zmqpp/)|[MPL-2.0](https://github.com/zeromq/zmqpp/blob/develop/LICENSE 'Mozilla Public License 2.0')|high-level binding for libzmq [deps: _libzmq_]| |[upstream](https://github.com/zeromq/zmqpp 'github.com/zeromq/zmqpp')|  [patch]|
|<a id='libzmq' />[libzmq](https://zeromq.org/)|[MPL-2.0](http://wiki.zeromq.org/area:licensing 'Mozilla Public License 2.0')|high-performance asynchronous messaging library [deps: _libsodium_]|[xpv4.3.5.2](https://github.com/externpro/libzmq/releases/tag/xpv4.3.5.2 'release')|[repo](https://github.com/externpro/libzmq 'github.com/externpro/libzmq') [upstream](https://github.com/zeromq/libzmq 'github.com/zeromq/libzmq')|[diff](https://github.com/externpro/libzmq/compare/v4.3.5...xpv4.3.5.2 'github.com/externpro/libzmq/compare/v4.3.5...xpv4.3.5.2') [patch]|
|<a id='libsodium' />[libsodium](https://doc.libsodium.org/)|[ISC](https://doc.libsodium.org/#license 'Internet Systems Consortium License, functionally equivalent to simplified BSD and MIT licenses')|library for encryption, decryption, signatures, password hashing and more [deps: _Threads_]|[xpv1.0.22.2](https://github.com/externpro/libsodium/releases/tag/xpv1.0.22.2 'release')|[repo](https://github.com/externpro/libsodium 'github.com/externpro/libsodium') [upstream](https://github.com/jedisct1/libsodium 'github.com/jedisct1/libsodium')|[diff](https://github.com/externpro/libsodium/compare/1.0.22...xpv1.0.22.2 'github.com/externpro/libsodium/compare/1.0.22...xpv1.0.22.2') [auto]|
|<a id='Threads' />[Threads](https://cmake.org/cmake/help/latest/module/FindThreads.html)|[LGPL-2.1-or-later](https://spdx.org/licenses/LGPL-2.1-or-later.html 'GNU Lesser General Public License v2.1 or later')|Finds and determines the thread library of the system for multithreading support|[xpv1.0.4](https://github.com/externpro/Threads/releases/tag/xpv1.0.4 'release')|[repo](https://github.com/externpro/Threads 'github.com/externpro/Threads')|[diff](https://github.com/externpro/Threads/compare/v0...xpv1.0.4 'github.com/externpro/Threads/compare/v0...xpv1.0.4') [bin]|

![deps](xprodeps.svg 'dependencies')

Dependency version check: all 3 parent-manifest versions match pinned versions.

|diff  |description|
|------|-----------|
|patch |diff modifies/patches existing cmake|
|intro |diff introduces cmake|
|auto  |diff adds cmake to replace autotools/configure/make|
|native|diff adds cmake but uses existing build system|
|bin   |diff adds cmake to repackage binaries built elsewhere|
|fetch |diff adds cmake and utilizes FetchContent|

[^_l]: see [SPDX License List](https://spdx.org/licenses/ '') for a list of commonly found licenses
[^_d]: see table above with description of diff
