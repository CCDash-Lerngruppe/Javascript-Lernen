
# Lektion 7: Grundlagen von Objektorientierung

## Was sind Objekte?

Objekte sind Sammlungen von Eigenschaften und Methoden.

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

## Klassen

Mit ES6 wurden Klassen eingeführt.

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
let meinRechteck = new Rechteck(5, 10);
console.log(meinRechteck.flaeche());
```

## Übung

1. Erstelle ein Objekt, das ein Buch beschreibt (Titel, Autor, Jahr).
2. Implementiere eine Klasse `Kreis`, die den Radius speichert und die Fläche berechnet.
