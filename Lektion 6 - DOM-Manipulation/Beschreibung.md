
# Lektion 6: DOM-Manipulation

## Einführung in das DOM

Das Document Object Model (DOM) repräsentiert die Struktur einer Webseite als Baumdiagramm.

---

## Elemente auswählen

### Methoden:
- `getElementById`:
  ```javascript
  let element = document.getElementById("demo");
  ```
- `querySelector`:
  ```javascript
  let element = document.querySelector(".klasse");
  ```

---

## Inhalte ändern

### Beispiel:
```javascript
let element = document.getElementById("demo");
element.innerHTML = "Neuer Text";
```

---

## Übung

1. Erstelle eine HTML-Seite mit einem Button.
2. Implementiere ein Skript, das bei einem Klick den Inhalt eines `<p>`-Elements ändert.
