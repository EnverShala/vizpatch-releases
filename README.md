# vizpatch-releases

Öffentlicher Versions-Index für [Vizpatch](https://vizionists.com).

`latest.json` enthält ausschließlich die Nummer der jeweils aktuellen
Vizpatch-Version. Eine laufende Vizpatch-Installation liest die Datei, um zu
erkennen, ob ein Update vorliegt — ohne Zugangsdaten und ohne Zugriff auf
das (private) Produkt-Repository.

```json
{ "version": "v1.15.0", "released": "2026-07-26" }
```

Hier liegt kein Quellcode und kein Installationspaket. Gepflegt wird die Datei
automatisch von `scripts/release.sh` beim Anlegen eines Releases.
