
# Lektion 8: Asynchronität und Promises

## Warum Asynchronität?

Manchmal führt JavaScript Code aus, der auf eine externe Quelle wartet (z. B. eine API). Ohne Asynchronität würde der gesamte Code pausieren, bis die Anfrage abgeschlossen ist.

---

## Callback-Funktionen

Eine Callback-Funktion wird als Argument an eine andere Funktion übergeben.

### Beispiel:
```javascript
setTimeout(() => {
    console.log("Fertig!");
}, 1000);
```

### Erklärung:
- `setTimeout` führt den Code nach einer Verzögerung (hier 1 Sekunde) aus.

---

## Promises

Ein Promise ist ein Objekt, das einen zukünftigen Wert repräsentiert.

### Beispiel:
```javascript
let promise = new Promise((resolve, reject) => {
    let erfolg = true;
    if (erfolg) {
        resolve("Alles hat funktioniert!");
    } else {
        reject("Etwas ist schiefgelaufen.");
    }
});

promise
    .then((nachricht) => console.log(nachricht))
    .catch((fehler) => console.error(fehler));
```

---

## `async` und `await`

Mit `async` und `await` kann asynchroner Code wie synchroner Code geschrieben werden.

### Beispiel:
```javascript
async function ladeDaten() {
    try {
        let antwort = await fetch("https://api.example.com/daten");
        let daten = await antwort.json();
        console.log(daten);
    } catch (fehler) {
        console.error("Fehler:", fehler);
    }
}
ladeDaten();
```

---

## Übung

1. Implementiere ein Promise, das eine Erfolgsmeldung nach 2 Sekunden anzeigt.
2. Schreibe eine Funktion, die Daten von einer öffentlichen API lädt und in der Konsole ausgibt.
