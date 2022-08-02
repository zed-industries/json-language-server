# json-language-server

This repository packages [vscode-json-languageserver](https://www.npmjs.com/package/vscode-json-languageserver) into standalone binaries that don't require Node to be installed on the user machine.

To publish a new release of the JSON language server, run:

```bash
script/build
```

Then, create a new GitHub release with the generated binaries.