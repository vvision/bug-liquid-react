# bug-liquid-react

This repository is a minimal reproductible app for issue [emdgroup-liquid/liquid/issues/495](https://github.com/emdgroup-liquid/liquid/issues/495).

To see the errors, run either ``npm run start`` or ``npm run build``.

## Error

Errors are similar to:
```bash
ERROR in ./node_modules/@emdgroup-liquid/liquid/dist/components/ld-sr-only2.js 1:0-89
Module not found: Error: Can't resolve '@stencil/core/internal/client' in '/redacted/my-app/node_modules/@emdgroup-liquid/liquid/dist/components'
Did you mean 'index.js'?
BREAKING CHANGE: The request '@stencil/core/internal/client' failed to resolve only because it was resolved as fully specified
(probably because the origin is strict EcmaScript Module, e. g. a module with javascript mimetype, a '*.mjs' file, or a '*.js' file where the package.json contains '"type": "module"').
The extension in the request is mandatory for it to be fully specified.
Add the extension to the request.
```
