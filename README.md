# [vscode-gn](https://marketplace.visualstudio.com/items?itemName=npclaudiu.vs-code-gn)

## What is GN?

From the [GN README](https://chromium.googlesource.com/chromium/src/+/master/tools/gn/README.md)
file in Chromium:

> GN is a meta-build system that generates Ninja build files
> so that you can build Chromium with Ninja.

Long story short, `GN` is similar to `cmake`, built for Chromium to replace their previous build system, `gyp`.

## What is this project about?

This repository takes the TextMate language definition for GN
as shipped with Chromium 61 and packs it as a Visual Studio
Code extension.

The language definition file `syntaxes/GN.tmLanguage` is taken
from the Chromium repository ([//src/tools/gn/misc/tm/GN.tmLanguage](https://cs.chromium.org/chromium/src/tools/gn/misc/tm/GN.tmLanguage?q=gn+tmlanguage&sq=package:chromium&l=1)),
as shipped with Chromium 61.0.3163.100 and converted to JSON
using the [TextMate Languages](https://marketplace.visualstudio.com/items?itemName=Togusa09.tmlanguage)
extension for Visual Studio Code into `syntaxes/GN.tmLanguage.json`.

## License

The file `syntaxes\GN.tmLanguage` is taken from the Chromium project
and licensed under a BSD-style license that can be found in the
LICENSE.chromium file. Everything else is licensed under a similar
BSD-style license available in the LICENSE file.

## Get in touch

* GitHub: [https://github.com/npclaudiu/vscode-gn](https://github.com/npclaudiu/vscode-gn)
* Visual Studio Marketplace: [https://marketplace.visualstudio.com/items?itemName=npclaudiu.vs-code-gn](https://marketplace.visualstudio.com/items?itemName=npclaudiu.vscode-gn)

Please feel free to contact me at `npclaudiu@gmail.com` if you
have any questions or suggestions.
