# 🔌 Pyrogram Plugins

> A collection of Pyrogram plugins made by the community

## Getting Started

[Pyrogram Smart Plugins](//docs.pyrogram.ml/resources/SmartPlugins) allow users to create modular framework's components with minimal boilerplate code. This repository is meant to collect awesome Pyrogram plugins.

### Use Plugins

- Create a new folder in your working directory (e.g.: "plugins").
- Copy the desired plugin(s) into the "plugins" folder.
- Enable plugins in your Client with `plugins_dir="plugins"`:
  ```python
  from pyrogram import Client

  Client("my_account", plugins_dir="plugins").run()
  ```

**More details**: [Smart Plugins](//docs.pyrogram.ml/resources/SmartPlugins)

### Create Plugins

bla bla bla

## Plugins Collection

Name | Description | Usage
:--- | :--- | :---
[**Haste**](plugins/haste) <br> by [delivrance](//github.com/delivrance) | Upload text to hastebin.com and send its link | Reply to a group chat text message with `!haste`
