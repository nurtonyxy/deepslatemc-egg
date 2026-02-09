# Pelican Egg - DeepslateMC

This folder contains a simple Pelican-compatible egg manifest and install script.
Use `egg.yml` when importing into Pelican.

Notes:
- Uses Java 21 by default.
- The install script downloads `DeepslateMC.jar` from the URL you provided.
- Adjust variables `JAR` and `MEMORY` if needed before importing to Pelican.
- `DOWNLOAD_URL` is the fixed jar download path.
- `MC_SERVER_NAME` sets the MOTD in `server.properties`.

Startup command:

java -Xms128M -XX:MaxRAMPercentage=95.0 -Dterminal.jline=false -Dterminal.ansi=true -jar {{JAR}}
