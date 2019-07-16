# vanillacord

a patcher for vanilla to allow for bungeecord's ip-forwarding

requires [java 1.7+](http://java.com/download)

usage: 
open command line and navigate to the folder you downloaded vanillacord to, then run

`java -jar vanillacord.jar <mojang's server jar file name>`

download vanilla server file [here](https://mcversions.net), choose your server version and click on "server jar" button

the patched jar will be placed in the same folder as vanillacord.jar file, with a "-bungee" suffix after

unlike spigot you do not need to set your server to offline mode. the online-mode setting in server.properties will only be used for commands (e.g. whitelist) when looking up uuid's

remember to firewall your server like you do with Spigot. this forces the server into offline mode and allows ip/uuid faking if it isn't correctly secured. http://www.spigotmc.org/wiki/firewall-guide/

# building
requires java dev kit

open command line and navigate to the folder you cloned this repo into, then run
`gradlew build`
