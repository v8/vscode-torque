# V8 Torque Language Support

This extension adds language support for [the Torque language used in V8](https://v8.dev/docs/torque).
This is not an officially supported Google product.

### Language server

The language server is not built by default. To build the language server manually:

```
cd <v8 checkout>
autoninja -C <output dir> torque-language-server
```

The default directory where the extension looks for the executable is "out/x64.release",
but the absolute path to the executable can be configured with the `torque.ls.executable`
setting.
