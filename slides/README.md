# Slides

This directory is organized as a small Quarto project.

- `src/`: lecture source files in Quarto (`.qmd`)
- `assets/img/`: shared images used in the lectures
- `output/`: rendered slide decks (`.pdf`) and other generated artifacts

To render all slides from the repository root:

```powershell
quarto render slides
```

To render a single lecture:

```powershell
quarto render slides/src/lecture3.qmd
```
