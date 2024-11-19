
# Lektion 2: Variablen und Datentypen

## Variablen in JavaScript

Variablen sind Container, um Werte zu speichern. In JavaScript gibt es drei Möglichkeiten, Variablen zu deklarieren:

- `var` (veraltet, verwenden Sie lieber `let` oder `const`)
- `let` (variabel)
- `const` (konstant)

### Beispiel

```javascript
let name = "Max";
const alter = 25;

console.log(name);  // Ausgabe: Max
console.log(alter); // Ausgabe: 25
```

## Datentypen

JavaScript hat verschiedene Datentypen:

- **Strings**: Zeichenketten (z. B. `"Hallo"`)
- **Numbers**: Zahlen (z. B. `42`)
- **Booleans**: Wahrheitswerte (`true`, `false`)
- **undefined**: Nicht initialisierte Variablen
- **null**: Absichtlicher leerer Wert

### Beispiel

```javascript
let text = "Hallo, Welt!";
let zahl = 42;
let istWahr = true;

console.log(typeof text); // Ausgabe: string
console.log(typeof zahl); // Ausgabe: number
console.log(typeof istWahr); // Ausgabe: boolean
```

## Übung

1. Erstelle Variablen für Name, Alter und ob du JavaScript magst.
2. Gib die Werte und deren Typen in der Konsole aus.
3. Was passiert, wenn du `const` erneut zuweist?
