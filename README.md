# VSCode syntax highlighting for CCS

For CCS details, see https://github.com/hellige/ccs and https://github.com/hellige/ccs-cpp

## Installation

* Install and configure https://code.visualstudio.com/ if you don't already have it.
* Download the extension (ex: `vsc-ccs-extension-0.0.3.vsix`) and install with:
  * `code --install-extension vsc-ccs-extension-0.0.3.vsix` or
  * Open the extension manager in VSCode, click the `...` in the upper right
    corner, select "Install from VSIX..."
* On "older" versions of VSC, copy/clone the contents of this directory into
  your `<home>/.vscode/extensions` folder and restart VSCode.

## Packaging
* https://code.visualstudio.com/api/working-with-extensions/publishing-extension
`npm install @vscode/vsce`
`./node_modules/.bin/vsce package`
