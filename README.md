# Patch Maker

A browser tool for building stage input lists (patch sheets).

**Live:** https://jaylenjinx.github.io/patch-maker/

- Sections with their own colours (Drums, Playback, Vocals…)
- Input and node numbers update as you add, remove or drag rows
- A row left empty becomes a spare, so channel breaks are one click
- Colour-coded drop boxes, with **Reletter boxes** to renumber each box in channel order
- Export a print-ready PDF (one A4 page), a PNG or a CSV; save and import lists as `.json`
- Mic, stand and stage-position suggestions as you type

Lists are saved in your browser (localStorage). Use **Save file** to back a list up or move it to another computer.

It's a single `index.html` with no build step. Preview locally with `python3 -m http.server` and open http://localhost:8000.

Deployed to GitHub Pages by `.github/workflows/pages.yml` on every push to `main`.
