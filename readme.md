# HEMS - Home Energy Management System

![Version](https://img.shields.io/badge/version-0.1-blue)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-2025+-41BDF5)

## Ziel

HEMS ist ein modulares Home Energy Management System für Home Assistant.

Im Gegensatz zu klassischen PV-Überschussladungen betrachtet HEMS das komplette Energiesystem eines Hauses.

## Funktionen

- PV-Überschussladen
- Netzladen
- Dynamische Stromregelung
- Automatische 1-/3-Phasenumschaltung
- Unterstützung mehrerer Fahrzeuge
- Priorisierung von Fahrzeugen
- Vorbereitung für Batteriespeicher
- Vorbereitung für dynamische Strompreise

## Hardware (erste Version)

- Home Assistant OS
- Shelly 3EM
- go-e Charger
- Tesla
- SonnenBatterie

## Roadmap

### Version 0.1
- Foundation

### Version 0.2
- Charging Manager

### Version 0.3
- Power Manager

### Version 0.4
- Phase Manager

### Version 0.5
- Vehicle Manager

### Version 0.6
- Battery Manager

### Version 1.0
- Stable Release

## Projektstruktur

```
src/
    package/
    config/
    helpers/
    templates/
    scripts/
    automations/
    dashboard/
```

## Lizenz

MIT License
