# RFC-OPEN-PATH-SYNC

Simple node module to create nested directories of a path like `mkdir -p`.

See [rfc-open-path](https://github.com/fcostarodrigo/rfc-open-path) for the asynchronous version.

DEPRECATED: See [@fcostarodrigo/open-path](https://www.npmjs.com/package/@fcostarodrigo/open-path)

## Installation

    npm install rfc-open-path-sync

## Usage

    const openPath = require('rfc-open-path-sync');

    openPath('a/b/c/d/e.f', true);

## Reference

`openPath(pathToOpen: String, fileInPath?: Boolean)`

Create nested directories of a path.

* `pathToOpen`: String with the path.
* `fileInPath`: Indicates if the last item of the path is a file.

## Development

    npm test

## License

[MIT](LICENSE.md)
