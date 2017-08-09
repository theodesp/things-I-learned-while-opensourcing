# things-I-learned-while-opensourcing
Things I've learned while open-sourcing. Experience from the trenches.

## Getting started

This project is a collection of valuable knowledge topics I've accumulated while contributing to opensource projects. I've laid
down a table for each project I've contribute and made some useful remarks.

[binaryornot](https://github.com/audreyr/binaryornot)
---
* Checking if a file is binary is not a trivial job. One has to perform a series of heuristic checks to see if a file is considered
binary. See [link](http://eli.thegreenplace.net/2011/10/19/perls-guess-if-file-is-text-or-binary-implemented-in-python/)
* Python has a libary called [chardet](http://chardet.readthedocs.io/en/latest/usage.html) that detects with a certain probability the encoding of a file.
* In general if a file containes a high ratio or non printable chars or some certain null bytes it is considered binary but not all the times.


### Contributing

If you like this project and you would like to share your valuable knowledge you can clone/for the project and Submit a PR.

Licence

MIT © Theo Despoudis
