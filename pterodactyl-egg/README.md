# Pterodactyl Egg - DeepslateMC

Import this egg into your Pterodactyl panel. It uses Java 21 and will download `DeepslateMC.jar` during installation from the provided URL.

Variables:
- `SERVER_JAR` - default `DeepslateMC.jar`
- `DOWNLOAD_URL` - fixed download URL for the server jar
- `MC_SERVER_NAME` - sets the MOTD in `server.properties`

Startup command:

java -Xms128M -XX:MaxRAMPercentage=95.0 -Dterminal.jline=false -Dterminal.ansi=true -jar {{SERVER_JAR}}
