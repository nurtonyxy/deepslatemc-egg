# Pterodactyl Egg - DeepslateMC

Import this egg into your Pterodactyl panel. It uses Java 21 and will download `DeepslateMC.jar` during installation based on the selected version.

Variables:
- `SERVER_JAR` - default `DeepslateMC.jar`
- `MC_VERSION` - version folder used to build the download URL
- `MC_SERVER_NAME` - sets the MOTD in `server.properties`

Startup command:

java -Xms128M -XX:MaxRAMPercentage=95.0 -Dterminal.jline=false -Dterminal.ansi=true -jar {{SERVER_JAR}}
