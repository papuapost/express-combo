## Contributing Code to `modown-static`

- The main source files are located under `lib/`.
- Unit tests are located under `tests/units/*`.
- Examples are located under `examples/`.

To run the unit tests (with coverage by default):

    npm test

To generate the API docs under `build/apidocs`:

    ./scripts/gendocs.sh
    open ./build/apidocs/index.html
