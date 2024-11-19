
# Lektion 8: Asynchronität und Promises

## Warum Asynchronität?

Manchmal muss Code warten, z. B. auf Daten von einer API.

### Beispiel für einen Timer:
```javascript
setTimeout(() => {
    console.log("Fertig!");
}, 1000);
```

## Promises

Promises sind Objekte, die zukünftige Werte repräsentieren.

### Beispiel:
```javascript
fetch("https://api.example.com")
    .then(response => response.json())
    .then(data => console.log(data));
```

## Übung

1. Schreibe ein Programm, das Daten von einer API lädt und in der Konsole ausgibt.
2. Verwende `async` und `await`, um die gleiche Aufgabe umzusetzen.
