# json-language-server

This repository packages [vscode-json-languageserver](https://www.npmjs.com/package/vscode-json-languageserver) into standalone binaries that don't require Node to be installed on the user machine.

To publish a new release of the JSON language server, create a new git tag e.g. `v1.2.3` and push it. A draft release will be created automatically. Once you publish it, Zed users will download the updated language server the first time they open a JSON file.
