
# Lektion 1: Einführung in JavaScript

## Was ist JavaScript?

JavaScript ist eine Skriptsprache, die in Webseiten verwendet wird, um Interaktivität zu ermöglichen. Es gehört zu den drei Kerntechnologien des Webs (HTML, CSS, JavaScript) und wird in Frontend- und Backend-Entwicklung eingesetzt.

### Vorteile von JavaScript

- Interaktivität und dynamische Inhalte
- Unterstützung in allen modernen Browsern
- Vielseitig einsetzbar (z. B. auch in Backend-Entwicklung mit Node.js)

---

## Ein erstes Programm

Ein einfacher "Hallo, Welt!"-Ausdruck in der Konsole:

```javascript
console.log("Hallo, Welt!");
```

### Übung: Konsolenausgabe

1. Öffne die Entwicklerkonsole deines Browsers (z. B. F12 in Chrome).
2. Gib `console.log("Hallo, Welt!");` ein.
3. Was wird angezeigt?

---

## JavaScript in HTML einbetten

Interaktives HTML-Beispiel mit JavaScript:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Interaktivität mit JavaScript</title>
</head>
<body>
    <h1>Einführung in JavaScript</h1>
    <p id="text">Dies ist ein Beispiel.</p>
    <button onclick="document.getElementById('text').innerHTML = 'Hallo, Welt!'">Klick mich</button>
</body>
</html>
```

### Übung: Interaktiver Button

1. Erstelle eine HTML-Datei mit dem obigen Code.
2. Öffne die Datei in deinem Browser und klicke auf den Button.
3. Beobachte, was passiert.
