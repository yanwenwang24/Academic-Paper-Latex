# Academic Paper LaTeX Template

A clean, modular LaTeX template for academic manuscripts.

## Structure

- **`paper.tex`**: Main entry point.
- **`sections/`**: Contains individual chapters (e.g., Introduction, Method).
- **`materials/`**: Dedicated directory for figures and tables.
- **`library.bib`**: Bibliography file.

## Usage

1. Edit content in `sections/`.
2. Update metadata (Title, Author) in `paper.tex`.
3. Compile using `latexmk`:

```bash
latexmk -pdf paper.tex
```
