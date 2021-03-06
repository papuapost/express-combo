Contributing Code to `express-combo`
----------------------------------

This components follows the same contribution model used by [Mojito][], you can
review the [Contributing-Code-to-Mojito file][] for more details.

Please be sure to sign our [CLA][] before you submit pull requests or otherwise contribute to `express-combo`. This protects `express-combo` developers, who rely on [express-combo's BSD license][].

[express-combo's BSD license]: https://github.com/yahoo/express-combo/blob/master/LICENSE.md
[CLA]: http://developer.yahoo.com/cocktails/mojito/cla/
[Mojito]: https://github.com/yahoo/mojito
[Contributing-Code-to-Mojito file]: https://github.com/yahoo/mojito/wiki/Contributing-Code-to-Mojito

Dev mode installation
---------------------

- The main source files are located under `lib/`.
- Unit tests are located under `tests/units/*`.
- Examples are located under `examples/`.

To install the dependencies:

    npm install

To run the unit tests (with coverage by default):

    npm test

To generate the API docs under `build/apidocs/index.html`:

    rm -rf ./build/apidocs && mkdir -p ./build/apidocs
    npm run docs

To lint the app lib folder:

    npm run lint
