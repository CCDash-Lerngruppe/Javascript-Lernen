
# Lektion 9: Fortgeschrittene Themen

## Module

Mit Modulen können Funktionen und Variablen in andere Dateien exportiert und importiert werden.

### Beispiel:
**datei1.js**
```javascript
export const sagHallo = () => console.log("Hallo, Welt!");
```

**datei2.js**
```javascript
import { sagHallo } from './datei1.js';
sagHallo();
```

---

## Fehlerbehandlung

Verwende `try`/`catch`, um Fehler im Code zu behandeln.

### Beispiel:
```javascript
try {
    JSON.parse("ungültig");
} catch (fehler) {
    console.error("Fehler:", fehler.message);
}
```

---

## Ein Blick auf Frameworks

JavaScript-Frameworks wie **React**, **Vue.js** oder **Angular** vereinfachen die Entwicklung moderner Anwendungen.

- **React:** Komponentenbasiertes UI-Framework.
- **Vue.js:** Fortschrittliches Framework für Benutzeroberflächen.
- **Angular:** Komplettes Framework für Web-Anwendungen.

---

## Übung

1. Schreibe ein Modul, das eine einfache Funktion exportiert und importiere es in einer anderen Datei.
2. Simuliere einen JSON-Fehler und fange ihn mit `try`/`catch` ab.
