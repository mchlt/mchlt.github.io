---
layout: post
title: Paramiko SSH enhancements
---

Made some contributions to the <a href="http://www.paramiko.org/">Paramiko module</a>, which is a a Python implementation of the SSHv2 protocol. I studied the code because I wanted to do something with SSH and Python, and then quickly found I could make some useful additions to it.

### Added cupport for aes192 ciphers

Made a small change to add support for the the <pre>aes192-ctr</pre> and <pre>aes192-cbc</pre> ciphers. This made it into <a href="http://www.paramiko.org/changelog.html">version 1.16</a>.




