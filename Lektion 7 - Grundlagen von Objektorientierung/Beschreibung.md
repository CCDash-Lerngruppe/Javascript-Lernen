
# Lektion 7: Grundlagen von Objektorientierung

## Einführung in Objekte

Ein Objekt ist eine Sammlung von Eigenschaften und Methoden.

### Beispiel:
```javascript
const auto = {
    marke: "BMW",
    modell: "X5",
    beschleunigen() {
        console.log("Das Auto beschleunigt.");
    }
};
auto.beschleunigen();
```

---

## Klassen

Klassen sind Blaupausen für Objekte.

### Beispiel:
```javascript
class Rechteck {
    constructor(breite, hoehe) {
        this.breite = breite;
        this.hoehe = hoehe;
    }
    flaeche() {
        return this.breite * this.hoehe;
    }
}
```

---

## Übung

1. Erstelle eine Klasse `Kreis`, die den Radius speichert und die Fläche berechnet.
