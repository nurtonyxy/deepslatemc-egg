# Pelican Egg — DeepslateMC

This folder contains a simple Pelican-compatible egg manifest and install script.

Notes:
- Uses Java 21 by default.
- The install script downloads `DeepslateMC.jar` from the URL you provided.
- Adjust variables `JAR` and `MEMORY` if needed before importing to Pelican.

Startup command:

java -Xms128M -XX:MaxRAMPercentage=95.0 -Dterminal.jline=false -Dterminal.ansi=true -jar {{JAR}}
