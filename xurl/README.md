# xurl plugin

> [xurl](https://github.com/xdevplatform/xurl) plugin for [proto](https://github.com/moonrepo/proto)

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add xurl "source:https://raw.githubusercontent.com/davearel/proto-plugins/main/xurl/plugin.toml" --global
proto install xurl
```

### Per-project install

```shell
proto plugin add xurl "source:https://raw.githubusercontent.com/davearel/proto-plugins/main/xurl/plugin.toml"
proto pin xurl latest --resolve
```

## What is `xurl`?

A curl-like command-line tool for interacting with the [X API](https://docs.x.com/x-api/introduction) (formerly Twitter), with built in OAuth 1.0a and OAuth 2.0 authentication.

See [xdevplatform/xurl](https://github.com/xdevplatform/xurl#xurl---a-curl-like-cli-tool-for-the-x-api) for further details.
