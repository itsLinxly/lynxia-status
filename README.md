# Lynxia Status

Eine moderne und schöne Status-Seite für Lynxia Services.

## Features

✨ **Modernes Design** - Saubere, zeitgemäße Benutzeroberfläche  
📱 **Responsive** - Optimiert für Desktop, Tablet und Mobile  
🎨 **Schöne Animationen** - Sanfte Übergänge und Hover-Effekte  
⚡ **Echtzeit-Updates** - Automatische Aktualisierung der Status-Informationen  
📊 **Uptime-Statistiken** - Verfügbarkeit und Performance-Metriken  
🔔 **Vorfalls-Historie** - Übersicht über vergangene Ereignisse  

## Verwendung

Öffnen Sie einfach die `index.html` Datei in einem Browser oder hosten Sie diese auf einem Webserver.

### Lokale Vorschau

```bash
# Mit Python 3
python -m http.server 8000

# Mit Node.js (npx)
npx serve

# Dann öffnen Sie http://localhost:8000 im Browser
```

## Anpassung

### Services konfigurieren

Bearbeiten Sie das `services` Array in der `index.html`:

```javascript
const services = [
    {
        name: 'Website',
        description: 'Haupt-Website und Landing Page',
        status: 'operational' // operational, degraded, down
    },
    // Weitere Services hinzufügen...
];
```

### Farben anpassen

Ändern Sie die CSS-Variablen im `:root` Selektor:

```css
:root {
    --primary-color: #3b82f6;
    --success-color: #10b981;
    --warning-color: #f59e0b;
    --error-color: #ef4444;
    /* ... */
}
```

## Status-Typen

- **operational** (Betriebsbereit) - ✓ Grün
- **degraded** (Eingeschränkt) - ⚡ Orange
- **down** (Nicht verfügbar) - ⚠ Rot

## Deployment

### GitHub Pages

1. Aktivieren Sie GitHub Pages in den Repository-Einstellungen
2. Wählen Sie den `main` Branch als Quelle
3. Die Status-Seite ist dann unter `https://itslinxly.github.io/lynxia-status/` verfügbar

### Netlify / Vercel

Verbinden Sie einfach Ihr Repository und die Seite wird automatisch deployed.

## Lizenz

© 2026 Lynxia. Alle Rechte vorbehalten.
