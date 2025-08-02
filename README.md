# 🐍 Lush Line

Ein modernes Snake-Spiel mit sanften Pastellfarben und minimalistischem Design, entwickelt mit React, TypeScript und TailwindCSS.

## ✨ Features

- **Sanfte Animationen**: Die Schlange gleitet flüssig über das Spielfeld
- **Pastellfarben**: Ästhetisch ansprechende Farbpalette
- **Responsive Design**: Funktioniert auf Desktop und Mobile
- **Moderne UI**: Glassmorphism-Effekte und sanfte Hover-Animationen
- **Keyboard & Touch Controls**: Pfeiltasten, WASD oder Touch-Steuerung
- **Progressive Speed**: Das Spiel wird mit steigendem Score schneller

## 🎨 Design

### Farbpalette
- **Hintergrund**: `#EDEDED` (Sanftes Grau)
- **Schlange**: `#B2E2B8` (Pastellgrün)
- **Futter**: `#F4B6B6` (Pastellrosa)
- **Akzent**: `#F6D58E` (Pastellgelb)

### Typografie
- **Hauptschrift**: Poppins (Google Fonts)
- **Fallback**: Inter, System Fonts

## 🚀 Installation & Start

### Voraussetzungen
- Node.js (Version 16 oder höher)
- npm oder yarn

### Installation
```bash
# Dependencies installieren
npm install

# Entwicklungsserver starten
npm start

# Für Production Build
npm run build
```

### Lokale Entwicklung
```bash
cd lush-line
npm install
npm start
```

Das Spiel öffnet sich automatisch unter `http://localhost:3000`

## 🎮 Spielanleitung

### Steuerung
- **Pfeiltasten** oder **WASD**: Schlange bewegen
- **Leertaste**: Spiel starten/neu starten
- **Touch-Steuerung**: Auf mobile Geräten verfügbar

### Ziel
- Sammle die roten Punkte (Futter)
- Werde so lang wie möglich
- Vermeide Kollisionen mit Wänden oder dir selbst
- Das Spiel wird mit jedem Punkt schneller

## 🏗️ Projektstruktur

```
lush-line/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── GameBoard.tsx      # Canvas-basiertes Spielfeld
│   │   ├── ScoreBoard.tsx     # Punkteanzeige
│   │   ├── StartButton.tsx    # Start/Neustart Button
│   │   └── Controls.tsx       # Touch-Steuerung
│   ├── hooks/
│   │   └── useGame.ts         # Spiellogik Hook
│   ├── types/
│   │   └── game.ts           # TypeScript Typen
│   ├── App.tsx               # Hauptkomponente
│   ├── index.tsx             # App Entry Point
│   └── index.css             # TailwindCSS + Custom Styles
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── README.md
```

## 🛠️ Technologie-Stack

- **React 18**: Moderne React mit Hooks
- **TypeScript**: Typsicherheit und bessere DX
- **TailwindCSS**: Utility-first CSS Framework
- **Canvas API**: Flüssige 2D-Grafiken
- **Custom Hooks**: Saubere Spiellogik-Trennung

## 🎯 Erweiterungsmöglichkeiten

Das Projekt ist so strukturiert, dass es einfach erweitert werden kann:

### Geplante Features
- [ ] Multiplayer-Modus mit WebSockets
- [ ] Verschiedene Schwierigkeitsgrade
- [ ] Power-ups und Spezialeffekte
- [ ] Highscore-System
- [ ] Verschiedene Spielfeld-Größen
- [ ] Sound-Effekte und Musik

### Technische Erweiterungen
- [ ] PWA (Progressive Web App)
- [ ] Offline-Unterstützung
- [ ] Leaderboard-API
- [ ] Social Features

## 🐛 Bekannte Issues

- Canvas `roundRect` wird nicht in allen Browsern unterstützt (Fallback implementiert)
- Touch-Steuerung auf sehr kleinen Bildschirmen könnte optimiert werden

## 📱 Browser-Kompatibilität

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 🤝 Beitragen

1. Fork das Repository
2. Erstelle einen Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit deine Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

## 📄 Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Siehe `LICENSE` für Details.

## 🙏 Danksagungen

- Google Fonts für die schönen Schriftarten
- TailwindCSS für das großartige CSS-Framework
- React Team für das fantastische Framework

---

**Viel Spaß beim Spielen! 🎮✨** 