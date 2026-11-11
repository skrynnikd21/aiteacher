# AI Teacher – Website

Öffentliche Projektseite der Diplomarbeit **AI Teacher** (HTL Wien West, 5AHITN, 2026/27):
**https://skrynnikd21.github.io/aiteacher/**

Die Seite stellt das Projekt vor und hat eine Demo zum Ausprobieren. Online antwortet die Demo mit
**vorbereiteten Antworten** – die echte KI (Gemini mit den Unterrichtsunterlagen über den MCP-Server)
läuft nur lokal, weil der API-Key nicht ins Internet darf.

## Aktualisieren

Die Datei `index.html` ist eine Kopie von `cloud/CloudBackend/wwwroot/index.html` aus dem
(privaten) Projekt-Repository. Nach Änderungen dort:

1. `index.html` (und bei Bedarf `fonts/`) hierher kopieren.
2. In GitHub Desktop committen und **Push** – nach 1–2 Minuten ist die Seite aktuell.

Die Seite erkennt selbst, ob sie auf GitHub Pages läuft (Online-Vorschau) oder vom Backend am
Laptop ausgeliefert wird (Live-Demo).

Schrift: Inter (SIL Open Font License 1.1, siehe `fonts/LICENSE-Inter.txt`).
