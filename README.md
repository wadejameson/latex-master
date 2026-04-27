# Masterarbeit (LaTeX)

Dieses Projekt ist für die Masterarbeit in LaTeX eingerichtet.

## Lokal mit Dev Container arbeiten

1. Repository in VS Code öffnen
2. **Dev Containers: Reopen in Container** ausführen
3. PDF bauen:

```bash
latexmk -pdf -interaction=nonstopmode Thesis/thesis_main.tex
```

Ergebnis: `Thesis/thesis_main.pdf`

## CI Pipeline

Bei jedem Push auf `master` baut GitHub Actions automatisch die PDF und lädt sie als Artefakt hoch.
