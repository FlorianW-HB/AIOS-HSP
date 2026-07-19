# AIOS-HSP

Monorepo für den Aufbau eines modularen AIOS für HSP RECHT und HSP STEUER.

## Zielbild

- gemeinsame Kernbausteine zentral halten
- HSP RECHT und HSP STEUER getrennt betreiben können
- Agenten, Prompts, SOPs, Vorlagen und Wissen sauber versionieren
- spätere Erweiterung um weitere Gesellschaften ohne Umbau ermöglichen

## Erste Struktur

- `aios/core` – gemeinsame Grundlagen
- `aios/shared` – gemeinsam genutzte Bausteine
- `aios/hsp-recht` – gesellschaftsspezifische Inhalte für HSP RECHT
- `aios/hsp-steuer` – gesellschaftsspezifische Inhalte für HSP STEUER
- `docs` – Architektur, Leitlinien und Arbeitsdokumente

## Nächste Schritte

1. Kernarchitektur festziehen
2. Agentenrollen definieren
3. Prompt- und SOP-Struktur anlegen
4. Wissensbasis je Gesellschaft trennen
5. erste Arbeitsabläufe dokumentieren
