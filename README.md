#  Interaktive 3D-Karte - Empanadas

Eine interaktive elektronische Karte zur Förderung des Empanada-Verkaufsstands eines Freundes, mit modernem Design und digitalen Funktionen, um Kunden anzuziehen und zu informieren.

##  Beschreibung

Dieses Projekt präsentiert eine interaktive 3D-Karte mit zwei Seiten (Vorder- und Rückseite), die in 3D-Rotation betrachtet werden können. Die Benutzeroberfläche ermöglicht es Kunden, das Menü auf immersive und moderne Weise zu konsultieren, mit der Möglichkeit, die Bilder für die Offline-Ansicht herunterzuladen.

##  Funktionen

- **Automatische 3D-Rotation**: Start-Animation mit 1,7 vollständigen Umdrehungen
- **Touch- und Maus-Interaktion**: Ziehen Sie die Karte, um sie manuell zu drehen
- **Vollbildansicht**: Klicken Sie auf eine Seite, um sie zu vergrößern und Details zu sehen
- **Download-Funktion**: Schaltfläche zum Herunterladen beider Kartenseiten im PNG-Format
- **Modernes Design**: Elegante Benutzeroberfläche mit subtilen Verläufen und flüssigen Animationen
- **Responsive**: Kompatibel mit Desktop und Mobile

##  Verwendung

### Lokale Installation

1. Klonen oder laden Sie das Projekt herunter
2. Öffnen Sie `index.html` in einem modernen Webbrowser
3. Keine Abhängigkeiten oder Server erforderlich!

### Web-Deployment

Sie können dieses Projekt auf jeder statischen Hosting-Plattform hosten:
- GitHub Pages
- Netlify
- Vercel
- Jeder klassische Webserver

##  Projektstruktur

```
CARTE/
├── index.html      # Hauptseite mit 3D-Oberfläche
├── carte1.jpg      # Bild der Kartenvorderseite
├── carte2.jpg      # Bild der Kartenrückseite
└── README.md       # Dokumentation
```

##  Anpassung

### Bilder ändern

Ersetzen Sie einfach `carte1.jpg` und `carte2.jpg` durch Ihre eigenen Menübilder.

### Start-Animation ändern

In `index.html`, Zeile 125:
```javascript
let totalRotations = 360 * 1.7; // Anzahl der Umdrehungen (1.7 = 1,7 Umdrehungen)
let duration = 800; // Dauer in Millisekunden
```

### Farben anpassen

Ändern Sie den Hintergrundverlauf (Zeile 9):
```css
background: linear-gradient(135deg, #ece9e6, #ffffff, #ffe5c5 80%);
```

## 🛠️ Verwendete Technologien

- HTML5
- CSS3 (Animationen, 3D-Transformationen, Flexbox)
- Vanilla JavaScript (keine Frameworks)
- Canvas API (für Bild-Downloads)

##  Anwendungsfälle

- Empanada-Stand auf einem Markt
- Food Truck
- Restaurant
- Veranstaltungen und Festivals
- Teilen in sozialen Medien

##  Projektziel

Eine interaktive elektronische Karte zur Förderung des Empanada-Verkaufsstands eines Freundes, mit modernem Design und digitalen Funktionen, um Kunden anzuziehen und zu informieren.

---



