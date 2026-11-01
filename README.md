# GravioLOG Public Dispo

- `dispo/` – Weiterleitung: GravioLOG Public Dispo läuft jetzt hinter Lizenzprüfung unter https://gravio-public-dispo.sevens7-ch.workers.dev/ (ein hier schon eingetragener Freischaltcode wird mitgenommen)
- `index.html` – Link-Seite: öffnet den Auftrag auf dem Android-Handy in GravioLOG Public (`graviopublic://auftrag`)
- `freischalten/` – Link-Seite: trägt den Freischaltcode in GravioLOG Public ein (`graviopublic://freischalten`)
- `code/` – Link-Seite für Freischaltcode-Anfragen aus der App: öffnet GravioLOG Public Code und trägt Geräte-Nummer
  und Fahrer ein (`graviopubliccode://anfrage?d=…&n=…`). Enthält keinen Schlüssel.

Aufträge sind verschlüsselt (AES-256-GCM, eigener Schlüssel, getrennt von Gravio). Die Daten stehen nur hinter dem `#`
und werden nie an diesen Server übertragen. Diese Dateien werden erzeugt; der Quelltext liegt nicht in diesem Repository.

© 2026 Christian Haake. Alle Rechte vorbehalten.
