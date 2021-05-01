# LiteBot Mod Extension

This repo serves as a basic boilerplate to create an extension for [LiteBot-Mod](https://github.com/iDarkLightning/litebot-mod)

There is also another boilerplate available which includes boilerplate code for creating a carpet extension
as well. This can be found [here](https://github.com/iDarkLightning/litebot-mod-extension/tree/with-carpet).

The primary purpose of an extension is to hook into when the before and after of
a command on [LiteBot](https://github.com/iDarkLightning/LiteBot) being executed.
The extension can also be used to dispatch custom events to LiteBot.

After creating a new repo with this as a template, simply edit build.gradle and mod.json to suit your needs.
You should also replace any instance of "litebotextension" with your own mod ID.

The "mixins" object can be removed from mod.json if you do not need to use any mixins.

For further information on developing with Fabric, check out the [Fabric Wiki](https://fabricmc.net/wiki/doku.php)
