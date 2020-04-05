# fsr4.github.io
Webseite des Fachschaftsrat 4 der HTW Berlin

## Aufbau der Website

### _includes
Enthält HTML-Code-Snippets, die einen eigenständigen Teil der Website abbilden (z.B. Events-Section, Sidebar, ...)

### _layout
Enthält HTML-Code-Snippets, die die Struktur der Website abbilden. Diese können als Vorlage für neue Seiten verwendet werden. (Beispiel: Siehe impressum.md)

### collections
Enthält Daten für die Webseite im Markdown-Format wie Mitglieder oder Veranstaltungen. Diese werden dann in den entsperchenden Bereichen der Seite gerendert.

### assets
Hier können Dateien abgelegt werden, die auf der Website eingebunden werden sollen (z.B. Bilder, Stylesheets, ...).

## Lokale Installation

ACHTUNG: Es muss Ruby (siehe [ruby-lang.org](https://www.ruby-lang.org/en/)) und Jekyll (siehe [jekyllrb.com](https://jekyllrb.com/docs/installation/)) installiert werden 

Um die Website lokal zu testen, kann nach der Installation aus dem geklonten Projektordner `jekyll serve` im Terminal ausgeführt werden.
