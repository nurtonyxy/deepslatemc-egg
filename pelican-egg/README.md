# Pelican Egg - DeepslateMC

This folder contains a Pelican-compatible egg manifest in PTDL v2 YAML.
Pelican can import Pterodactyl eggs using either JSON or YAML. Use `egg.yml` from this folder or `pterodactyl-egg/egg.json`.

Notes:
- Uses Java 21 by default.
- The install script downloads `DeepslateMC.jar` from `DOWNLOAD_URL`.
- Variables:
  - `SERVER_JAR` (jar filename)
  - `DOWNLOAD_URL` (fixed jar download path)
  - `MC_SERVER_NAME` (sets the MOTD in `server.properties`)

Startup command:

java -Xms128M -XX:MaxRAMPercentage=95.0 -Dterminal.jline=false -Dterminal.ansi=true -jar {{SERVER_JAR}}
