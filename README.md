#Purpose

Debian package for **node.js** v0.8.14 *armel* for *ARMv5t kirkwood*. This kind of **ARM processor** take place in Seagate Dockstar, PlugComputer, ...

#Setup

Copy .deb file on your device, and :

> `dpkg -i nodejs_0.8.14~squeeze_armel.deb

#How I built it ?

I've unpacked [Chris Lea] .deb files for **node.js** and **npm** packages, replaced **node** binary and then rebuild the package.

[Chris Lea]: https://launchpad.net/~chris-lea/+archive/node.js/ "node.js ppa repository"
