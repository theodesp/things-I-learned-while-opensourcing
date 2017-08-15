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

[Inversify](https://github.com/inversify/InversifyJS)
---
* Inversion of control is more than having a map of keys and objects. Often you need more customization.
* Inversify.js has a really good project structure for Typescript apps.
* [Reflect-Metadata](https://www.npmjs.com/package/reflect-metadata) Can be used to add additional meta properties to parameters or classes
* Decorators can be usefull for adding metadata properties in a seemless way.
* Its important to have a good PULL_REQUEST_TEMPLATE, CONTRIBUTING and ISSUE_TEMPLATE to our projects.
* [Appveyor](https://www.appveyor.com/) is really cool CI for Windows.

[Cookiecutter](https://github.com/audreyr/cookiecutter)
---
* [Click](http://click.pocoo.org/5/) is as really cool package for creating beautiful command line interfaces.
* [Jinja Templates](http://jinja.pocoo.org/) has really cool features for debugging and sandboxing.
* [pytest](https://docs.pytest.org/en/latest/) is the defacto testing framework for python.
* Pytest with --cov reporting does not work well with PyCharm.
* You can pass a custom environmnent to [Popen](https://docs.python.org/2/library/subprocess.html#popen-constructor)
* Windows accepts only strings for env variables. Use os.pathsep to enable crossplatform separators.

[angular-es6-mobx-flux-example](https://github.com/theodesp/angular-es6-mobx-flux-example)
---
* Angular 1.5+ versions introduced Lifecycle Hooks and Components [Link](https://toddmotto.com/angular-1-5-lifecycle-hooks). so its really easy to write clean angular code that resembles React Components.
* ES6 in Angular 1 is not so bad. We can leverage the power of Mobx to have a very scalable applications without having to learn another framework.

[Cache Line](https://github.com/theodesp/cache-line)
---
* [Node Gyp](https://github.com/nodejs/node-gyp) Can be used to write native applications in C/C++ and reference them in Node.
The only problem is that [Node C++ Documendation](https://nodejs.org/api/n-api.html) is not very good.

[Kyt-starter](https://github.com/theodesp/kyt-starter)
---
* [Kyt](https://github.com/NYTimes/kyt) Is a very versatile foundation for building webpack apps. Its one of the easiest tools to use.

[fetch-future](https://github.com/theodesp/fetch-future)
---
* *Futures* are one of the best alternatives to Promises [See why](https://github.com/fluture-js/Fluture/wiki/Comparison-to-Promises) as they are composable and cancelable.

## Contributing
If you like this project and you would like to share your valuable knowledge you can clone/for the project and Submit a PR.

## Licence

MIT © Theo Despoudis
