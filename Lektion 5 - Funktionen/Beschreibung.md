
# Lektion 5: Funktionen

## Was sind Funktionen?

Funktionen sind wiederverwendbare Blöcke von Code, die eine Aufgabe ausführen. Sie können Parameter annehmen und Werte zurückgeben.

### Funktionsdeklaration:
```javascript
function sagHallo(name) {
    console.log(`Hallo, ${name}!`);
}
sagHallo("Max");
```

## Arrow Functions

Eine kürzere Syntax für Funktionen.

### Beispiel:
```javascript
const addiere = (a, b) => a + b;
console.log(addiere(5, 3)); // 8
```

## Übung

1. Schreibe eine Funktion, die das Quadrat einer Zahl berechnet.
2. Erstelle eine Arrow Function, die zwei Strings verbindet.
