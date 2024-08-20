# XaeroServerMap
### Adds automatic world map selection for servers when utilizing Xaero's Map mods.
This project would not be possible without [ChristopherHaws](https://github.com/ChristopherHaws/mc-xaero-map-spigot). If you would like to support the project, you can sponsor ChristopherHaws [here](https://github.com/sponsors/ChristopherHaws). He did all the heavy lifting, I have simply updated the plugin for my personal needs.

This plugin will enable [Xaero's Minimap](https://chocolateminecraft.com/minimap2.php) and [Xaero's World Map](https://chocolateminecraft.com/worldmap.php) to automatically select the correct world map when joining a different server on the same network. This can be useful on server networks where you may change servers often.

There are no configuration files or permissions, simple add the plugin to your server, restart your server, and your world maps will begin to function seamlessly!
<br /><br />

## How to Compile

```bash
# Test gradle to ensure your environment is acceptable.
./gradlew test
```
```bash
# Build plugin jar file; The destination directory for the plugin file will be `<Project Location>\build\libs\`.
./gradlew build
```

This plugin was designed to be reliable and lightweight. It does not use any non-public APIs.
Please report any issues, and I will see what I can remedy.