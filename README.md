# Software Inc – Deutsche Lokalisierung

Eine vollständige deutsche Übersetzung (100 %) für das Aufbau-/Wirtschaftsspiel **Software Inc**.

## Inhalt

| Datei | Inhalt |
|-------|--------|
| `UI.tyd` | Gesamte Benutzeroberfläche (Menüs, Fenster, Tooltips, Spalten, Hinweise) |
| `Tutorial.tyd` | Alle Tutorials |
| `Software.tyd` | Software-Typen, Kategorien und Features |
| `Furniture.tyd` | Möbel und Einrichtung |
| `Articles.tyd` | Presse-/Testbericht-Texte |
| `Achievements.tyd` | Erfolge |
| `Tasks.tyd` | Aufgaben/Belohnungen |
| `Traits.tyd` | Mitarbeiter-Eigenschaften |
| `meta.tyd` | Sprachpaket-Metadaten |

## Stil

- Durchgängig informelle Anrede („du")
- Branchenübliche Anglizismen beibehalten, wo natürlich (Feature, Build, Release, Server, Bug, Update, Patch, Deal, IP, Publisher, Dev …)
- Begriffe konsistent zu den UI-Elementen (z. B. hervorgehobene Tutorial-Begriffe entsprechen den echten Button-/Fensternamen)

## Installation

1. Diesen Ordner als `Deutsch` in das Lokalisierungs-Verzeichnis des Spiels kopieren:
   ```
   <Software-Inc-Installationsordner>/Localization/Deutsch/
   ```
2. Spiel starten und im Sprachmenü **Deutsch/German** auswählen.

> Die Dateien liegen im **TyD-Format** (das vom Spiel bevorzugte Format).

## Bekannte Einschränkungen

Einige Texte lassen sich nicht über Sprachdateien übersetzen, da sie im Spielcode fest hinterlegt sind:

- Manche Tabellen-Spaltenköpfe (vom Spiel als „non-localized" gesetzt)
- Die allerersten Hinweis-Benachrichtigungen, falls sie vor dem Laden der Übersetzung erzeugt wurden (neue Hinweise erscheinen deutsch)

## Mitwirken

Korrekturen und Verbesserungen sind willkommen – gerne per Issue oder Pull Request.
