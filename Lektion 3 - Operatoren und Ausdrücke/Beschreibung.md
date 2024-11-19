
# Lektion 3: Operatoren und Ausdrücke

## Arithmetische Operatoren

JavaScript unterstützt grundlegende mathematische Operatoren:
- Addition: `+`
- Subtraktion: `-`
- Multiplikation: `*`
- Division: `/`
- Modulus (Rest): `%`

### Beispiel:
```javascript
let a = 10;
let b = 3;

console.log(a + b); // Ausgabe: 13
console.log(a % b); // Ausgabe: 1
```

## Vergleichsoperatoren

Vergleichsoperatoren werden verwendet, um Werte zu vergleichen:
- Gleichheit: `==` (Typ wird nicht geprüft), `===` (Typ wird geprüft)
- Ungleichheit: `!=`, `!==`
- Größer/Kleiner: `>`, `<`, `>=`, `<=`

### Beispiel:
```javascript
console.log(5 == "5");  // true
console.log(5 === "5"); // false
```

## Logische Operatoren

- UND (`&&`): Alle Bedingungen müssen wahr sein.
- ODER (`||`): Mindestens eine Bedingung muss wahr sein.
- NICHT (`!`): Negiert den Wahrheitswert.

### Beispiel:
```javascript
let a = true;
let b = false;

console.log(a && b); // false
console.log(a || b); // true
console.log(!a);     // false
```

## Übung

1. Schreibe ein Programm, das prüft, ob eine Zahl gerade oder ungerade ist.
2. Experimentiere mit den Vergleichs- und logischen Operatoren.
