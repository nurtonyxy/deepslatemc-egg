# Pelican Egg - DeepslateMC

This folder contains a Pelican-compatible egg manifest in PTDL v2 YAML.
Pelican can import Pterodactyl eggs using either JSON or YAML. Use `egg.yml` from this folder or `pterodactyl-egg/egg.json`.

Notes:
- Uses Java 21 by default.
- The install script downloads `DeepslateMC.jar` from a URL built with `MC_VERSION`.
- Variables: `SERVER_JAR` (jar filename), `MC_VERSION` (version folder), `MC_SERVER_NAME` (sets the MOTD in `server.properties`).

Startup command:

java -Xms128M -XX:MaxRAMPercentage=95.0 -Dterminal.jline=false -Dterminal.ansi=true -jar {{SERVER_JAR}}
