# AIOS Core Manifest

## Zweck
AIOS ist das gemeinsame Betriebssystem fuer die Kanzleien HSP RECHT und HSP STEUER.

## Leitprinzipien
- Gemeinsame Basis, getrennte Fachlogiken.
- Keine Vermischung von Gesellschafts- oder Mandantenkontexten ohne ausdrueckliche Zuordnung.
- Jeder Agent bekommt einen klaren Auftrag, klare Ausgaben und klaren Freigabeweg.
- Entscheidungen mit Aussenwirkung werden immer vor Versand zur Pruefung vorgelegt.

## Zielstruktur
- `aios/core`: Regeln, Standards, Konventionen, Kontrolllogik
- `aios/shared`: gemeinsame Bausteine wie Personas, Vorlagen, Sprache, Stil
- `aios/hsp-recht`: rechtsspezifische Agenten, Prozesse, Vorlagen
- `aios/hsp-steuer`: steuerrechtsspezifische Agenten, Prozesse, Vorlagen
- `docs`: Architektur, Betrieb, Roadmap

## Trennregel
Alles, was nur eine Gesellschaft betrifft, gehoert ausschliesslich in den jeweiligen Bereich.
Alles, was beides betrifft, gehoert in `aios/shared` oder `aios/core`.
