
# Lektion 4: Steuerstrukturen

## Bedingungen

Mit `if`, `else` und `else if` können Entscheidungen getroffen werden.

### Syntax:
```javascript
if (Bedingung) {
    // Code wird ausgeführt, wenn die Bedingung wahr ist
} else if (weitereBedingung) {
    // Code wird ausgeführt, wenn weitereBedingung wahr ist
} else {
    // Code wird ausgeführt, wenn keine Bedingung wahr ist
}
```

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

---

## `switch`-Anweisung

Prüft mehrere Fälle und führt den passenden Code aus.

### Beispiel:
```javascript
let tag = "Montag";

switch (tag) {
    case "Montag":
        console.log("Neue Woche, neues Glück!");
        break;
    case "Freitag":
        console.log("Fast Wochenende!");
        break;
    default:
        console.log("Ein ganz normaler Tag.");
}
```

---

## Schleifen

### `for`-Schleife
Wird verwendet, wenn die Anzahl der Wiederholungen bekannt ist.
```javascript
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

### `while`-Schleife
Wird verwendet, wenn die Wiederholungsbedingung flexibel ist.
```javascript
let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}
```

### `do-while`-Schleife
Führt den Code mindestens einmal aus, bevor die Bedingung geprüft wird.
```javascript
let i = 0;
do {
    console.log(i);
    i++;
} while (i < 5);
```

---

## Übung

1. Schreibe eine Schleife, die die Zahlen von 1 bis 10 ausgibt.
2. Schreibe ein Programm, das mit `switch` den Wochentag aus einer Zahl bestimmt.
