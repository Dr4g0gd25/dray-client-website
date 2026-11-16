# DRAY Update-Hosting

Dieser Ordner ist der statische HTTPS-Hosting-Pfad fuer den DRAY Auto-Updater.

Geplante Basisadresse:

`https://dr4g0gd25.github.io/dray-client-website/dray`

Wichtig: Signierte `latest.json`-Manifeste und Release-Dateien werden erst durch `npm run release:publish` im DRAY-Client-Projekt erzeugt und anschliessend hier veroeffentlicht. Keine privaten Signaturschluessel in dieses Repository hochladen.

Struktur:

- `stable/` – stabile Releases
- `beta/` – Beta-Releases
