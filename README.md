# SamuelZNewton-E-Ink

This VS Code extension provides 1 color theme designed for use with E-Ink or other monochrome displays.  It still makes some use of color to increase usability in environments where color is available.  I have mainly created it for my own use, so it has mainly been tested with Python (the language I've used most frequently recently).  I've tried to generalize it to work well with other languages, but I can't promise it will work well everywhere.

## Install

You can install this extension using a .vsix file or by copying the code to the right place.

### Install from VSIX

1. Download the .vsix file from the latest release (on the [releases](https://github.com/samuelznewton/e-ink-vscode/releases) page).
2. Open VS Code.
3. Open the command palette (try `Ctrl+Shift+P`).
4. Type `Install from VSIX` and press enter to choose the appropriate command.
5. Select the VSIX file you downloaded earlier.

(Alternatively, if you're handy with the command line, try `code --install-extension <filepath>`.)

### Install from source code

For reasons I don't understand, this hasn't been working for me lately.  Hopefully it'll work for you.  If you're concerned about safety, the VSIX file is just a zip file with text files inside.  You can open it up and read it.  Or, you can [build a new VSIX from source](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#packaging-extensions) yourself.  You'll need to install [VSCE](https://github.com/microsoft/vscode-vsce) to do that.

The source code can be downloaded and copied to your VS Code extensions directory:

- Windows: `%USERPROFILE%\.vscode\extensions`
- macOS: `~/.vscode/extensions`
- Linux: `~/.vscode/extensions`

Ensure the extension gets its own directory within that directory (e.g. this README should be located at `.../.vscode/extensions/samuelznewton-e-ink/README.md`).

## Guiding principles

In general...

- Unrecognized text is unformatted.
- Comments are light gray.
- Words defined by the language are bold.
- Objects and variables are italic.
- Variables are blue.
- Functions are purple.
- Classes, types, and other namespaces are bold, italic, and green.
