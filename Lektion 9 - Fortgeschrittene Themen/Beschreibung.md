
# Lektion 9: Fortgeschrittene Themen

## Module

Verwenden Sie `import` und `export`, um Code zu organisieren.

### Beispiel:
**datei1.js**
```javascript
export const sagHallo = () => console.log("Hallo!");
```

**datei2.js**
```javascript
import { sagHallo } from './datei1.js';
sagHallo();
```

## Fehlerbehandlung

Verwenden Sie `try`/`catch`, um Fehler abzufangen.

### Beispiel:
```javascript
try {
    JSON.parse("ungültig");
} catch (error) {
    console.log("Fehler:", error.message);
}
```

## Übung

1. Schreibe ein Modul, das eine mathematische Funktion exportiert.
2. Implementiere ein Skript, das eine JSON-Datei lädt und Fehler abfängt.
