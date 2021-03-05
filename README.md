# [3.14159.in](https://3.14159.in/)

A colourised rendering of the digits of pi. Each digit 0-9 has an assigned colour, and is laid out from top left to bottom right.

* Built using high-precision `BitInt`-based computation of the digits of pi, based on the Taylor Series expansion, as [implemented by Andrew Jennings](http://ajennings.net/blog/a-million-digits-of-pi-in-9-lines-of-javascript.html).
* Can be computationally intensive if you have a large window on a high-res screen. 
* Visually inspired by various other similar implementations.
* Single HTTP request - everything's inlined into the HTML. Why? Well, why not?
* ~1.5kb for everything, gzipped but without minification.
* What is build tooling?
