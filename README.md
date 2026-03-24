# Open PC

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Status: In Progress](https://img.shields.io/badge/Status-In%20Progress-yellow.svg)

## 📖 Über das Projekt

Open PC ist ein Bildungsprojekt, das Kindern auf spielerische Weise vermittelt, was ein Computer ist und wie seine Komponenten zusammenarbeiten. Mithilfe von 3D-gedruckten PC-Modellen und der Tiptoi-Integration können Kinder interaktiv lernen, welche Teile zu einem PC gehören und worauf man beim Zusammenbau achten muss.

---

## 🎯 Ziele

- Kinder im Grundschulalter spielerisch mit PC-Hardware vertraut machen
- Verständnis für PC-Komponenten und deren Zusammenspiel fördern
- Kostenlose, offene IT-Bildungsressourcen bereitstellen
- Einfach umsetzbar und reproduzierbar für alle

---

## 📁 Repository-Struktur

```
open-pc/
├── README.md               
├── CONTRIBUTING.md         
├── LICENSE                 
├── 3d-models/              
│   ├── gehaeuse/
│   ├── mainboard/
│   ├── cpu/
│   ├── ram/
│   ├── netzteil/
│   └── README.md
├── tiptoi/                
│   ├── audio/              
│   ├── scripts/            
│   └── README.md
├── docs/                   
│   ├── aufbauanleitung.md
│   ├── komponenten.md
│   └── bilder/
```

---

## 🚀 Installation

### Voraussetzungen

- 3D-Drucker
- Tiptoi-Stift

### Aufbau

1. Repository klonen:
   ```bash
   git clone https://github.com/MischaBarm/Open-PC.git
   cd open-pc
   ```

2. 3D-Modelle aus dem Ordner `3d-models/` drucken

3. Tiptoi-Dateien aus dem Ordner `tiptoi/` auf den Stift übertragen

4. Aufbauanleitung unter `docs/aufbauanleitung.md` folgen


## 🤝 Beitragen

Wir freuen uns über Beiträge! Bitte lies zuerst [CONTRIBUTING.md](CONTRIBUTING.md).

1. Fork erstellen
2. Feature-Branch anlegen: `git checkout -b feature/mein-feature`
3. Änderungen committen: `git commit -m 'feat: Beschreibung'`
4. Branch pushen: `git push origin feature/mein-feature`
5. Pull Request öffnen
