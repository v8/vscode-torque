# V8 Torque Language Support

This extension adds language support for the V8 project internal language
[V8 Torque](https://v8.dev/docs/torque).
This is not an officially supported Google product.

## Language server

The language server is not built by default. To build the language server manually:

```
cd <v8 checkout>
autoninja -C <output dir> torque-language-server
```

The default directory where the extension looks for the executable is `out/x64.release`,
but the absolute path to the executable can be configured with the `torque.ls.executable`
setting.

## Installation instructions

Open [Visual Studio Code](https://code.visualstudio.com/). Press `Ctrl+Shift+X` or `Cmd+Shift+X` to open the Extensions pane. Find and install the “V8 Torque Language Support” extension. Alternatively, install the extension from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=v8-torque.vscode-torque). Open any `.tq` file in VS Code. The extension is now activated!
