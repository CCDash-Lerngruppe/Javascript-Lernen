
# Lektion 4: Steuerstrukturen

## Bedingungen

Mit `if`, `else` und `else if` können Sie Bedingungen überprüfen.

### Beispiel:
```javascript
let zahl = 10;

if (zahl > 0) {
    console.log("Die Zahl ist positiv.");
} else if (zahl < 0) {
    console.log("Die Zahl ist negativ.");
} else {
    console.log("Die Zahl ist null.");
}
```

## `switch`-Anweisung

Eine kompakte Möglichkeit, mehrere Fälle zu prüfen.

### Beispiel:
```javascript
let farbe = "rot";

switch (farbe) {
    case "rot":
        console.log("Stop!");
        break;
    case "grün":
        console.log("Go!");
        break;
    default:
        console.log("Unbekannte Farbe.");
}
```

## Schleifen

### `for`-Schleife
```javascript
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

### `while`-Schleife
```javascript
let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}
```

## Übung

1. Schreibe eine Schleife, die die Zahlen von 1 bis 10 ausgibt.
2. Schreibe ein Programm, das mit `switch` den Wochentag aus einer Zahl bestimmt.
