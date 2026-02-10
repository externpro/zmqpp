# zmqpp dependencies

|project|license [^_l]|description [dependencies]|version|source|diff [^_d]|
|-------|-------------|--------------------------|-------|------|----------|
|<a id='zmqpp' />[zmqpp](https://zeromq.github.io/zmqpp/)|[MPL-2.0](https://github.com/zeromq/zmqpp/blob/develop/LICENSE 'Mozilla Public License 2.0')|high-level binding for libzmq [deps: _libzmq_]| |[upstream](https://github.com/zeromq/zmqpp 'github.com/zeromq/zmqpp')|  [patch]|
|<a id='libzmq' />[libzmq](https://zeromq.org/)|[MPL-2.0](http://wiki.zeromq.org/area:licensing 'Mozilla Public License 2.0')|high-performance asynchronous messaging library [deps: _libsodium_]|[xpv4.3.4.4](https://github.com/externpro/libzmq/releases/tag/xpv4.3.4.4 'release')|[repo](https://github.com/externpro/libzmq 'github.com/externpro/libzmq') [upstream](https://github.com/zeromq/libzmq 'github.com/zeromq/libzmq')|[diff](https://github.com/externpro/libzmq/compare/v4.3.4...xpv4.3.4.4 'github.com/externpro/libzmq/compare/v4.3.4...xpv4.3.4.4') [patch]|
|<a id='libsodium' />[libsodium](https://doc.libsodium.org/)|[ISC](https://doc.libsodium.org/#license 'Internet Systems Consortium License, functionally equivalent to simplified BSD and MIT licenses')|library for encryption, decryption, signatures, password hashing and more|[xpv1.0.18.233](https://github.com/externpro/libsodium/releases/tag/xpv1.0.18.233 'release')|[repo](https://github.com/externpro/libsodium 'github.com/externpro/libsodium') [upstream](https://github.com/jedisct1/libsodium 'github.com/jedisct1/libsodium')|[diff](https://github.com/externpro/libsodium/compare/aa099f5e82ae78175f9c1c48372a123cb634dd92...xpv1.0.18.233 'github.com/externpro/libsodium/compare/aa099f5e82ae78175f9c1c48372a123cb634dd92...xpv1.0.18.233') [auto]|

![deps](xprodeps.svg 'dependencies')

Dependency version check: all 2 parent-manifest versions match pinned versions.

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
