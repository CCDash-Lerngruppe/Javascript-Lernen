
# Lektion 10: Projektarbeit - To-Do-App

## Ziel

Erstelle eine interaktive To-Do-App, die folgende Funktionen bietet:
1. Aufgaben hinzufügen.
2. Aufgaben als erledigt markieren.
3. Aufgaben löschen.

---

## HTML-Grundgerüst

```html
<!DOCTYPE html>
<html>
<head>
    <title>To-Do-App</title>
</head>
<body>
    <h1>To-Do-Liste</h1>
    <input type="text" id="aufgabe" placeholder="Neue Aufgabe">
    <button id="hinzufügen">Hinzufügen</button>
    <ul id="liste"></ul>

    <script src="app.js"></script>
</body>
</html>
```

---

## Logik in `app.js`

### Beispielcode:
```javascript
document.getElementById("hinzufügen").addEventListener("click", () => {
    const aufgabe = document.getElementById("aufgabe").value;
    if (aufgabe) {
        const li = document.createElement("li");
        li.textContent = aufgabe;
        document.getElementById("liste").appendChild(li);
        document.getElementById("aufgabe").value = "";
        
        // Aufgabe löschen
        li.addEventListener("click", () => li.remove());
    }
});
```

---

## Erweiterungsideen

1. Speichere Aufgaben im lokalen Speicher (localStorage).
2. Füge eine Checkbox hinzu, um Aufgaben als erledigt zu markieren.

---

## Übung

1. Implementiere den Beispielcode und teste die App.
2. Füge eine Erweiterung hinzu (z. B. lokale Speicherung oder Sortierfunktionen).
