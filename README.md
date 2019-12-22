# BetterWhitelister
BetterWhitelist makes whitelisting new players way easier for private servers! This plugin uses <a href="https://github.com/DV8FromTheWorld/JDA">JDA</a> to enable automatic whitelisting via Discord. The command and messages are completly customizable.
<b>Important:</b> A server restart is required whenever you set a new bot token in the ```config.yml```.
You can find the latest releases <a href="https://github.com/Dumb-Dog-Diner-Development/betterwhitelister/releases">here</a>

Commands | Permission | Description
------------ | ------------- | -------------
```/betterwhitelist``` | ```betterwhitelist.command``` | Main command, displays available arguments if no argument is given
```/betterwhitelist help``` | ```betterwhitelist.command``` | Displays available arguments
```/betterwhitelist reload``` | ```betterwhitelist.command.reload``` | Reloads the plugin config
```/betterwhitelist whois <Minecraft User>``` | ```betterwhitelist.command.whois``` | Displays information about the Discord account <br>connected to the given Minecrat account
```/betterwhitelist enable``` | ```betterwhitelist.command``` | Enable automatic whitelisting
```/betterwhitelist disable``` | ```betterwhitelist.command``` | Disable automatic whitelisting
