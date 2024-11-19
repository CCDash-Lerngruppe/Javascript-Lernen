
# Lektion 3: Operatoren und Ausdrücke

## Arithmetische Operatoren

Diese Operatoren werden für mathematische Berechnungen verwendet:
- `+` (Addition)
- `-` (Subtraktion)
- `*` (Multiplikation)
- `/` (Division)
- `%` (Modulus, Rest einer Division)

### Beispiel:
```javascript
let a = 10;
let b = 3;

console.log(a + b); // 13
console.log(a % b); // 1
```

---

## Vergleichsoperatoren

Vergleichsoperatoren vergleichen Werte und geben einen Boolean zurück (`true` oder `false`):
- `==` (Gleichheit, ignoriert Typen)
- `===` (Strikte Gleichheit)
- `!=` (Ungleichheit)
- `!==` (Strikte Ungleichheit)
- `>`, `<`, `>=`, `<=`

### Beispiel:
```javascript
console.log(5 == "5");  // true
console.log(5 === "5"); // false
```

---

## Logische Operatoren

Verwende logische Operatoren, um Bedingungen zu kombinieren:
- `&&` (UND)
- `||` (ODER)
- `!` (NICHT)

### Beispiel:
```javascript
let x = true;
let y = false;

console.log(x && y); // false
console.log(x || y); // true
console.log(!x);     // false
```

---

## Übung

1. Schreibe ein Programm, das überprüft, ob eine Zahl gerade oder ungerade ist.
2. Experimentiere mit verschiedenen Vergleichs- und logischen Operatoren.
