# IU LaTeX Clean Template

Dieses Repository enthält ein minimalistisches LaTeX-Template für wissenschaftliche Arbeiten an der [IU Internationale Hochschule](https://www.iu.de/), wie z. B. Hausarbeiten, Essays oder kleinere Forschungsberichte.

Die Vorlage basiert auf dem Projekt [markushaug/iu-latex-template](https://github.com/markushaug/iu-latex-template), wurde jedoch von mir (Becci) vereinfacht, bereinigt und für generische Verwendungen angepasst.  

> **Hinweis:** Diese Version ist **kein offizielles IU-Template** und steht in keinem Zusammenhang mit der IU.  
> Sie wurde von Studierenden erstellt und dient nur als unterstützende Vorlage.

## Änderungen gegenüber dem Original
- Entfernt: Bachelor-/Master-spezifische Kapitel, Anhänge und Vorlagen.
- Bereinigte Projektstruktur.
- Vereinfachte Präambel.
- Leichtgewichtige Vorlage für schnelle Nutzung in Overleaf oder lokal.

## Nutzung
1. Repository clonen oder als ZIP herunterladen.
2. In Overleaf importieren **oder** lokal mit LuaHBTeX (TeX Live 2022+) kompilieren:
    ```bash
    lualatex template.tex
    ```
3. Bei Verwendung einer `.bib`-Datei:
    ```bash
    biber template
    ```

## Lizenz
MIT – siehe [LICENSE](LICENSE).  
Basierend auf dem ursprünglichen Projekt [markushaug/iu-latex-template](https://github.com/markushaug/iu-latex-template).
