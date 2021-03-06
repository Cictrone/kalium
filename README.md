# kalium - Java binding to the Networking and Cryptography (NaCl) library

A Java binding to [Networking and Cryptography](http://nacl.cr.yp.to/) library by [Daniel J. Bernstein](http://cr.yp.to/djb.html). All the hard work of making a portable NaCl API version was done by [Frank Denis](https://github.com/jedisct1) on [libsodium](https://github.com/jedisct1/libsodium) and kalium was totally inspired by [Tony Arcieri's](https://github.com/tarcieri) work with [RbNaCl](https://github.com/cryptosphere/rbnacl).

## Requirements

* JDK 6 or [higher](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [Apache Maven](http://maven.apache.org/guides/getting-started/)

## Installation

### libsodium

kalium is implemented using [jnr-ffi](https://github.com/jnr/jnr-ffi) to bind the shared libraries from [libsodium](https://github.com/jedisct1/libsodium). For a more detailed explanation, please refer to [RbNaCl's documentation](https://github.com/cryptosphere/rbnacl/blob/master/README.md).

OS X users can get libsodium via [homebrew](http://mxcl.github.com/homebrew/) with:

    brew install libsodium

### kalium installation

Add as a [Maven dependency](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22org.abstractj.kalium%22%20AND%20a%3A%22kalium%22) at your project.

### FAQ

#### Is Android supported?
  No.

#### Would be nice to have some documentation. Do you have some?

  Look at the libsodium docs, they are self explanatory. Or, contribute with docs.

#### I'm experiencing some issues on Windows. Do you have any idea?

  I'm sorry but I'm completely clueless about Windows environment, but if you have any suggestions or PR changes. They will be more than welcome.

### Notes

kalium is a work in progress, feedback, bug reports and patches are always welcome.

[![Build Status](https://travis-ci.org/abstractj/kalium.png?branch=master)](https://travis-ci.org/abstractj/kalium)
[![Build status](https://ci.appveyor.com/api/projects/status/github/abstractj/kalium?branch=master&svg=true)](https://ci.appveyor.com/project/abstractj/kalium/branch/master)
