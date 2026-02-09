🥚 DeepslateMC Egg

Ein Pterodactyl / Pelican Egg zur automatisierten Installation von DeepslateMC Servern.

Dieses Repository enthält die Egg-Definitionen für das DeepslateMC-Serverprojekt. Es ermöglicht dir, mit dem Pterodactyl- oder Pelican-Panel direkt einen DeepslateMC-Server bereitzustellen, ohne manuelle Downloads oder Konfigurationen.

📌 Übersicht

Mit diesem Egg kannst du:

Einen DeepslateMC Server einfach über dein Panel über ein Click-to-Deploy-System starten.

Automatische Installation der benötigten Serverdateien konfigurieren.

Startup-Parameter anpassen, um RAM, Version oder weitere Optionen dynamisch zu steuern.

Das Setup für Paper, Purpur oder andere kompatible Forks erweitern (falls unterstützt).

🚀 Features

✔ Unterstützt als Pterodactyl-Egg
✔ Enthält Pelican-Egg-Konfiguration
✔ Einfach konfigurierbar
✔ Läuft out-of-the-box mit automatischem Download
✔ Open-Source unter MIT-Lizenz

📦 Inhalt des Repositories
Datei	Zweck
pterodactyl-egg	Egg-Definition für das Pterodactyl Panel
pelican-egg	Optional: Egg-Konfiguration für Pelican Panel
README.md	Diese Dokumentation
🛠 Installation
Für Pterodactyl Panel

Öffne dein Pterodactyl-Admininterface.

Gehe zu Nests → Import Egg.

Lade die Datei pterodactyl-egg hoch.

Erstelle einen neuen Server und wähle das DeepslateMC Egg aus.

Konfiguriere Ressourcen (RAM, CPU, Storage).

Starte den Server.

Für Pelican Panel

Importiere die Datei pelican-egg über die Pelican-UI.

Fülle die erforderlichen Platzhalter (z. B. Download-URL, Startup-Command) aus.

Fertig!

⚙️ Konfiguration

Passe innerhalb des Panels folgende Werte nach Bedarf an:

Einstellung	Bedeutung
Version/Branch	Welche Version von DeepslateMC installiert wird
Startup Command	JVM-Parameter und Startscript
Environment Vars	z. B. SERVER_JARFILE, JAR_VERSION
❓ FAQ

F: Was ist DeepslateMC?
A: DeepslateMC ist eine alternative Minecraft-Serversoftware mit Zusatzfunktionen, die viele typische Plugin-Features ersetzt oder ergänzt.

F: Unterstützt das Egg Plugins?
A: Ja — wie bei jedem Minecraft-Server kannst du Plugins nach dem ersten Start hinzufügen.

🎓 Entwicklung

Wenn du das Egg erweitern willst:

Forke dieses Repository.

Passe die Egg-Configs an (z. B. bessere Defaults, Multi-Version-Support).

Öffne einen Pull-Request.

🧡 Mitmachen

Beiträge sind willkommen! Sei es Bugfixes, Verbesserungen oder neue Features für das Egg.

📜 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert.
Siehe LICENSE
 für Details.
