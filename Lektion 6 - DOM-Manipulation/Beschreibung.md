
# Lektion 6: DOM-Manipulation

## Was ist der DOM?

Das Document Object Model (DOM) stellt die Struktur einer HTML-Seite als Baumstruktur dar. Mit JavaScript können wir den DOM manipulieren.

### Elemente auswählen
```javascript
let element = document.getElementById("demo");
```

### Inhalte ändern
```javascript
element.innerHTML = "Neuer Inhalt";
```

## Events

Beispiel für ein Klick-Event:
```javascript
document.getElementById("button").addEventListener("click", () => {
    alert("Button wurde geklickt!");
});
```

## Übung

1. Erstelle eine HTML-Seite mit einem Button.
2. Schreibe ein Skript, das bei einem Klick auf den Button den Text auf der Seite ändert.
