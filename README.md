# CASCB Summer School 2026

Slides for a 90-minute talk at the CASCB Summer School 2026:
**"Collective Behavior: From Digital Traces to Generative Agents"**

Built with [Quarto](https://quarto.org) / reveal.js, styled in the
University of Konstanz corporate design (Seeblau `#59C7EB`, official logo on the
cover). Each content slide carries a citation footer so the audience can see
what is published.

## Build

```bash
quarto render index.qmd     # produces index.html
quarto preview index.qmd    # live-reloading preview
```

Open `index.html` in a browser. Press `S` for speaker notes, `F` for
fullscreen, `E`/`?print-pdf` then browser-print for a PDF export.

## Files

- `index.qmd` — the presentation source
- `konstanz.scss` — University of Konstanz reveal.js theme
- `assets/UniKonstanz_Logo.png` — official logo (cover slide)
- `assets/footer.html` — per-slide citation-footer script
- `figures/` — slide figures

## Structure (≈36 content slides)

1. **Introduction to Computational Social Science** — digital / computerized / generative; the hype cycle; complexity
2. **Collective emotions on social media**
   - The micro–macro gap (ABM of collective emotions — Schweitzer & Garcia, *EPJ B* 2010)
   - Microscopic measurement: **LEIA** (Aroyehun et al., *EPJ Data Science* 2023) — incl. LEIA-vs-humans (unpublished, C. Metz MSc thesis)
   - Macroscopic measurement: social media macroscopes (Pellert et al., *Sci. Rep.* 2022; Garcia et al., arXiv:2107.13236; WHR 2022)
   - The Paris attacks case (Garcia & Rimé, *Psychological Science* 2019)
3. **Generative agents** — WHAT-IF; the Collective Turing Test (Bouleimen et al., *Sci. Rep.* 2026); AI4Social+
4. **AI agents** — conformity (arXiv:2601.05384); coordination (arXiv:2409.02822); collective misalignment (arXiv:2605.10721; Schroeder et al., *Science* 2026); Moltbook (arXiv:2602.09270)
5. **Summary**

Source material was drawn from earlier decks under `../OldPresentations/`.
