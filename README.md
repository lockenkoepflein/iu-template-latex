# IU LaTeX Template (Overleaf-ready)

Dieses Repository enthält ein minimalistisches LaTeX-Template für wissenschaftliche Arbeiten an der [IU Internationale Hochschule](https://www.iu.de/), wie z. B. Hausarbeiten, Fallstudien oder Advanced Workbooks.  
Die Vorlage wurde optimiert für die einfache Verwendung in [Overleaf](https://www.overleaf.com/).

## Ursprung
Diese Vorlage basiert auf dem Projekt [markushaug/iu-latex-template](https://github.com/markushaug/iu-latex-template), wurde jedoch von mir (@lokenkoepflein) stark reduziert und angepasst.

## Was ist anders?
- Reduziertes Template.
- Vereinfachte Projektstruktur.
- Keine Entwickler-Tools wie Docker oder VS Code Konfigurationen mehr enthalten.
- Kompatibel mit LuaHBTeX (empfohlen von der IU, kann in Overleaf eingestellt werden).

## Nutzung in Overleaf
1. Lade das Repository als ZIP herunter:
   - Klicke auf **Code → Download ZIP**.
2. Entpacke die ZIP-Datei lokal.
3. Lade alle Dateien in ein neues Projekt bei [Overleaf](https://www.overleaf.com/).
4. **In Overleaf → Settings → Compiler: LuaLaTeX auswählen**.
5. Kompiliere das Dokument (`template.tex`).

Optional:  
Wenn du ein Literaturverzeichnis verwendest (`references.bib`):
- Stelle sicher, dass Overleaf **Biber** als Backend verwendet.
- Nutze dann die `recompile` Funktion in Overleaf (läuft automatisch durch).

## Lizenz
MIT – siehe [LICENSE](LICENSE).  
Basierend auf dem ursprünglichen Projekt [markushaug/iu-latex-template](https://github.com/markushaug/iu-latex-template).
