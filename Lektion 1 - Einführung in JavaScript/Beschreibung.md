
# Lektion 1: Einführung in JavaScript

## Was ist JavaScript?

JavaScript ist eine vielseitige Programmiersprache, die in modernen Webseiten verwendet wird, um Interaktivität und Dynamik zu ermöglichen. Es wird häufig in Verbindung mit HTML und CSS genutzt und gilt als eine der Kerntechnologien des Webs.

### Wichtige Eigenschaften:
- **Dynamisch:** Kann zur Laufzeit verändert werden.
- **Plattformunabhängig:** Läuft in jedem modernen Browser ohne zusätzliche Software.
- **Vielseitig:** Kann sowohl im Frontend als auch im Backend eingesetzt werden (z. B. mit Node.js).

### Einsatzgebiete:
- **Frontend:** Dynamische Webseiten, Animationen, Formvalidierung.
- **Backend:** Serverseitige Programmierung mit Node.js.
- **Andere:** Spiele, Desktop-Apps, mobile Apps.

---

## Ein erstes Programm

Das folgende Programm gibt "Hallo, Welt!" in der Konsole aus:

```javascript
console.log("Hallo, Welt!");
```

### Erklärung:
- `console.log`: Gibt Text in der Konsole des Browsers aus.
- `"Hallo, Welt!"`: Ein String, der ausgegeben wird.

### Schritt-für-Schritt-Anleitung:
1. Öffne die Entwicklerkonsole deines Browsers (z. B. F12 in Chrome).
2. Gib den obigen Code ein und drücke Enter.
3. Beobachte, wie "Hallo, Welt!" in der Konsole erscheint.

---

## JavaScript in HTML einbetten

Um JavaScript in HTML zu verwenden, kannst du das `<script>`-Tag nutzen.

### Beispiel:
```html
<!DOCTYPE html>
<html>
<head>
    <title>Erstes JavaScript</title>
</head>
<body>
    <h1>Willkommen</h1>
    <script>
        console.log("JavaScript ist aktiviert!");
    </script>
</body>
</html>
```

### Übung:
1. Erstelle eine HTML-Datei mit obigem Code.
2. Öffne die Datei in deinem Browser und überprüfe die Konsole.
3. Füge weiteren Code hinzu, z. B. eine weitere Konsolenausgabe.

---

## Interaktivität mit JavaScript

JavaScript ermöglicht es, Webseiten interaktiv zu gestalten. Ein einfaches Beispiel:

```html
<!DOCTYPE html>
<html>
<body>
    <p id="text">Dies ist ein interaktives Beispiel.</p>
    <button onclick="document.getElementById('text').innerHTML = 'Text wurde geändert!'">Klick mich</button>
</body>
</html>
```

### Erklärung:
- `onclick`: Ein Event, das ausgelöst wird, wenn der Button geklickt wird.
- `document.getElementById`: Zugriff auf ein HTML-Element über seine ID.
- `.innerHTML`: Ändert den Inhalt des Elements.

### Übung:
1. Erstelle eine HTML-Datei mit dem obigen Code.
2. Experimentiere mit verschiedenen Texten und IDs.
3. Versuche, mehrere Buttons mit unterschiedlichen Funktionen hinzuzufügen.

---

## Zusammenfassung

In dieser Lektion hast du gelernt:
1. Was JavaScript ist und wofür es verwendet wird.
2. Wie du JavaScript in einer Webseite einbettest.
3. Ein einfaches interaktives Beispiel.

---

**Tipp:** Besuche [MDN Web Docs](https://developer.mozilla.org/de/docs/Web/JavaScript) für weitere Informationen und Ressourcen.
