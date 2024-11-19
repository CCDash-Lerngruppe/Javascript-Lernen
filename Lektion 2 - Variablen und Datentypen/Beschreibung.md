
# Lektion 2: Variablen und Datentypen

## Einführung in Variablen

Variablen sind benannte Speicherplätze, die Daten speichern. In JavaScript gibt es drei Schlüsselwörter zum Deklarieren von Variablen:
1. `var` (veraltet, sollte vermieden werden)
2. `let` (empfohlen für veränderliche Werte)
3. `const` (für unveränderliche Werte)

### Beispiele:
```javascript
let name = "Max";
const alter = 25;
var stadt = "Hamburg"; // Nicht empfohlen
```

### Best Practices:
- Verwende `let` für Variablen, die sich ändern können.
- Verwende `const`, wenn der Wert nicht verändert werden soll.

---

## Datentypen

JavaScript hat verschiedene Datentypen. Diese lassen sich in zwei Kategorien einteilen:
1. **Primitive Datentypen:** Strings, Numbers, Booleans, `undefined`, `null`, `Symbol`, `BigInt`.
2. **Objektdatentypen:** Arrays, Objekte, Funktionen.

### Primitive Datentypen:
- **String:** Text, eingeschlossen in Anführungszeichen.
  ```javascript
  let text = "Hallo, Welt!";
  ```
- **Number:** Ganzzahlen oder Dezimalzahlen.
  ```javascript
  let zahl = 42;
  ```
- **Boolean:** Wahrheitswerte.
  ```javascript
  let istWahr = true;
  ```
- **`undefined` und `null`:**
  ```javascript
  let nichtDefiniert;
  let leer = null;
  ```

---

## Dynamische Typisierung

JavaScript ist dynamisch typisiert, d. h. der Typ einer Variablen kann sich ändern.

### Beispiel:
```javascript
let daten = 42;       // Number
daten = "Text";       // Jetzt ein String
```

---

## Übung

1. Deklariere Variablen für deinen Namen, dein Alter und deine Lieblingsstadt.
2. Gib die Werte und deren Typ in der Konsole aus.
3. Experimentiere mit `let` und `const`, indem du Werte neu zuweist.

**Zusatzübung:** Schreibe ein Programm, das zwei Zahlen addiert und das Ergebnis ausgibt.
