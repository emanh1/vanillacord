
A patcher for vanilla to allow for bungeecord's ip-forwarding

Usage: java -jar vanillacord.jar <minecraft version/mojang's server jar file name>

The patched jar will be placed in the out sub-folder once completed.

Unlike spigot you do not need to set your server to offline mode. The online-mode setting in server.properties will only be used for commands (e.g. whitelist) when looking up uuid's

Remember to firewall your server like you do with Spigot. This forces the server into offline mode and allows ip/uuid faking if it isn't correctly secured. http://www.spigotmc.org/wiki/firewall-guide/
