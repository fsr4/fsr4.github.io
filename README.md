# fsr4.github.io
![deploy](https://github.com/fsr4/fsr4.github.io/workflows/deploy/badge.svg)

Webseite des Fachschaftsrat 4 der HTW Berlin

## Aufbau der Website

### _includes
Enthält HTML-Code-Snippets, die einen eigenständigen Teil der Website abbilden (z.B. Events, Members, ...)

### _layout
Enthält HTML-Code-Snippets, die die Struktur der Website abbilden. Diese können als Vorlage für neue Seiten verwendet werden. 

### collections
Enthält Daten für die Webseite im Markdown-Format wie Mitglieder oder Veranstaltungen. Diese werden dann in den entsperchenden Bereichen der Seite gerendert.

### assets
Hier können Dateien abgelegt werden, die auf der Website eingebunden werden sollen (z.B. Bilder, Stylesheets, ...).

## Lokale Installation

ACHTUNG: Um das Projekt unter Windows testen zu können, muss zuerst Ruby installiert werden (siehe [ruby-lang.org](https://www.ruby-lang.org/en/))

- Projekt von GitHub klonen
- Terminal im Projekt-Root-Ordner öffnen
- `bundle install` ausführen

Um die Website lokal zu testen, kann nach der Installation `bundle exec jekyll serve` im Terminal ausgeführt werden
