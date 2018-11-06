# 🔌 Pyrogram Plugins

> A collection of Pyrogram plugins made by the community

[Pyrogram Smart Plugins](//docs.pyrogram.ml/resources/SmartPlugins) allow users to create and easily share modular framework's components with minimal boilerplate code. This repository is meant to collect awesome Pyrogram plugins.

## Use Plugins

- Create a new folder in your working directory (e.g.: "plugins").
- [Download](https://github.com/pyrogram/plugins/archive/master.zip) and copy the desired plugin(s) into your "plugins" folder.
- Enable plugins in your Client by telling Pyrogram to search on your folder with `plugins_dir="plugins"`:
  ```python
  from pyrogram import Client

  Client("my_account", plugins_dir="plugins").run()
  ```

[**More details**](https://docs.pyrogram.ml/resources/SmartPlugins#using-smart-plugins)

## Add Plugins

- Understand how [Smart Plugins](//docs.pyrogram.ml/resources/SmartPlugins) work.
- Create an awesome plugin.
- Open a new [Pull Request](https://github.com/pyrogram/plugins/compare) to propose your plugin.
- Make sure you add a proper license and your name to it. Also edit the readme to add the plugin in the list below.

## Plugins Collection

Name | Description | Usage
:--- | :--- | :---
[**Haste**](plugins/haste) <br> by [delivrance](//github.com/delivrance) | Upload text to hastebin.com and send its link | Reply to a group chat text message with `!haste`
