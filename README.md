# IU LaTeX Structured Template (Overleaf-ready)

This repository provides a clean and structured LaTeX template for academic papers at [IU International University](https://www.iu.de/), such as essays, term papers, or advanced workbooks.  
The template is optimized for easy use in [Overleaf](https://www.overleaf.com/), while keeping a modular folder structure that allows larger or more complex documents to stay organized.

## Origin
This template is based on the project [markushaug/iu-latex-template](https://github.com/markushaug/iu-latex-template), but has been cleaned, reduced, and adapted by me (@lockenkoepflein).

## What's different?
- Clean, modular structure (`main.tex`, `chapters/`, `pages/`), suitable for both short and long papers.
- No developer tools like Docker or VS Code configuration.
- Can be compiled with **LuaLaTeX (recommended for best font and Unicode support)** or **PDFLaTeX (with adjusted font settings)**.

## Usage in Overleaf
1. Download the repository as ZIP:
   - Click **Code → Download ZIP**.
2. Extract the ZIP archive locally
3. Upload all files to a new project in [Overleaf](https://www.overleaf.com/).
4. In Overleaf → **Settings → Compiler: select LuaLaTeX** (recommended) or PDFLaTeX (if you have adjusted the font settings accordingly).
5. Compile the document (`main.tex`).

Optional:  
If you want to use a bibliography (`references.bib`):
- Make sure to select **Biber** as backend in Overleaf settings.
- Then simply **Recompile** (Overleaf will handle everything automatically).

## License
MIT – see [LICENSE](LICENSE).  
Based on the original project [markushaug/iu-latex-template](https://github.com/markushaug/iu-latex-template).
