#Aufgabe
# Git und GitHub - HTML und CSS Beispiel
Dieses Repository enthält ein einfaches HTML-Dokument, das grundlegende Informationen über Git und GitHub präsentiert. Zusätzlich enthält es CSS-Styling, um das Erscheinungsbild der Webseite anzupassen.

## Inhaltsverzeichnis

- [Über das HTML-Dokument](#über-das-html-dokument)
- [Über das CSS-Styling](#über-das-css-styling)
- [Über den JavaScript-Code](#über-den-javascript-code)
- [Verwendung](#verwendung)
- [Lizenz](#lizenz)

## Über das HTML-Dokument

Das HTML-Dokument ist eine einfache Webseite, die Informationen über Git und GitHub bereitstellt. Es enthält die folgenden Elemente:

- `<!DOCTYPE html>`: Deklariert den Dokumenttyp als HTML5.
- `<html>`: Das Wurzelelement des Dokuments.
- `<head>`: Enthält Metadaten wie die Zeichencodierung und den Seitentitel.
- `<meta charset="UTF-8">`: Legt die Zeichencodierung auf UTF-8 fest.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Legt die Ansichtsgröße auf die Breite des Geräts und die Anfangsvergrößerungsfaktor auf 1 fest.
- `<link rel="stylesheet" href="styles.css">`: Verlinkt die externe CSS-Datei "styles.css" für das Styling der Webseite.
- `<title>Git und GitHub</title>`: Setzt den Seitentitel auf "Git und GitHub".
- `<body>`: Der Hauptinhalt der Webseite.
- `<header>`: Der Kopfbereich der Webseite mit der Überschrift "Git und GitHub".
- `<section>`: Ein Abschnitt mit Erklärungen und Links.
- `<h2>`: Eine Unterüberschrift innerhalb eines Abschnitts.
- `<p>`: Ein Absatz für Text.
- `<a href="URL" target="_blank">Text</a>`: Ein Link, der in einem neuen Tab geöffnet wird.
- `<footer>`: Der Fußbereich der Webseite mit dem Copyright-Hinweis.

## Über das CSS-Styling

Das CSS-Styling ist verantwortlich für das Erscheinungsbild der Webseite. Hier sind einige der verwendeten Stilregeln:

- `body`: Legt die Schriftart, Hintergrundfarbe und den Rand fest.
- `header`: Definiert das Styling des Kopfbereichs mit Hintergrundfarbe und Textfarbe.
- `h1`: Setzt das Styling für die Überschrift im Kopfbereich.
- `.content`: Definiert das Styling für den Hauptinhalt mit Begrenzung, Hintergrundfarbe und Schatten.
- `a`: Legt die Farbe und die Textdekoration für Links fest.
- `footer`: Definiert das Styling für den Fußbereich mit Hintergrundfarbe und Textfarbe.

## Über den JavaScript-Code

Der JavaScript-Code in diesem Beispiel ist einfach und zeigt die Verwendung von Event-Handling. Hier ist eine kurze Erklärung:

- `script.js`: Diese JavaScript-Datei enthält den Code für die Interaktion mit der Webseite.
- `function handleTitleClick() { ... }`: Dies ist eine Funktion, die aufgerufen wird, wenn der Titel (H1-Element) geklickt wird. Sie zeigt eine Benachrichtigung an.
- `const titleElement = document.querySelector("header h1");`: Dieser Code wählt das H1-Element im Header-Bereich aus.
- `titleElement.addEventListener("click", handleTitleClick);`: Hier wird ein Event-Listener hinzugefügt, der auf einen Klick auf das H1-Element reagiert und die `handleTitleClick`-Funktion aufruft.

## Verwendung

Sie können dieses HTML-Dokument und das CSS-Styling als Grundlage für Ihre eigene Webseite verwenden. Passen Sie den Inhalt und das Styling nach Ihren Bedürfnissen an. Der JavaScript-Code kann erweitert werden, um weitere Interaktionen auf der Webseite zu implementieren.

## Lizenz

Dieses HTML-Dokument, das CSS-Styling und der JavaScript-Code stehen unter der MIT-Lizenz. Weitere Informationen finden Sie in der `LICENSE`-Datei.


