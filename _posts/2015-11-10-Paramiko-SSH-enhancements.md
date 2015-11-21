---
layout: post
title: Paramiko SSH enhancements
---

Made some contributions to the <a href="http://www.paramiko.org/">Paramiko module</a>, which is a a Python implementation of the SSHv2 protocol. I studied the code because I wanted to do something with SSH and Python, and then quickly found I could make some useful additions to it.

### Added support for aes192 ciphers

Made a small <a href="https://github.com/paramiko/paramiko/pull/604">change</a> to add support for the the `aes192-ctr` and `aes192-cbc` ciphers. This made it into <a href="http://www.paramiko.org/changelog.html">version 1.16</a>.

### Added support for ecdsa 384 and 521 bit key authentication 

Made a larger <a href="https://github.com/paramiko/paramiko/pull/611">contribution</a> by enhancing the existing <abbr title="Elliptic Curve Digital Signature Algrithm">ECDSA</abbr> class that could only handle the 256 size keys, so it can now handle all three commonly used sizes ecdsa-sha2-nistp384 and ecdsa-sha2-nistp521 key authentication.






