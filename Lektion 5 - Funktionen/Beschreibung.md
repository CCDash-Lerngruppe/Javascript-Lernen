
# Lektion 5: Funktionen

## Was sind Funktionen?

Funktionen sind Blöcke von wiederverwendbarem Code. Sie nehmen Eingaben (Parameter) entgegen, führen Berechnungen aus und geben Ergebnisse zurück.

### Syntax:
```javascript
function nameDerFunktion(parameter1, parameter2) {
    // Codeblock
    return ergebnis;
}
```

### Beispiel:
```javascript
function addiere(a, b) {
    return a + b;
}
console.log(addiere(3, 5)); // 8
```

---

## Arrow Functions

Eine kürzere Schreibweise für Funktionen.

### Beispiel:
```javascript
const multipliziere = (a, b) => a * b;
console.log(multipliziere(4, 5)); // 20
```

---

## Übung

1. Schreibe eine Funktion, die prüft, ob eine Zahl gerade oder ungerade ist.
2. Implementiere eine Funktion, die den Umfang eines Kreises berechnet.
