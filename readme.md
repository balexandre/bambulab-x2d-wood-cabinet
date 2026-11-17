# Bambu Lab X2D – wood shell & stand

A parametric 3D draft (three.js, single `index.html`) of a wooden shell and steel-legged stand for a Bambu Lab X2D with an external AMS 2 Pro and AMS HT.

**Live model:** https://balexandre.github.io/bambulab-x2d-wood-cabinet/

## Inspiration

The look is inspired by the [Prusa Signature Oak](https://www.prusa3d.com/p/prusa-signature-oak/): a slim wooden box that sits flush around the printer, on thin black steel legs with a small wooden shelf between them.

## What the draft covers

- **Two build modes**
  - *Flush wood shell* – sides, top and back hug the printer; the X2D's own door is the front. The top board and the whole hood lift off the base on brass pins for maintenance.
  - *Table only* – just the stand, with a shallow (4–6 mm) chamfered recess, or four foot recesses, so the printer can't slide.
- **Stand** – splayed Ø25 black steel legs and a solid wood lower shelf.
- **Materials** – choice of veneer wood (thermally modified ash, iroko, sapele, oak) over birch ply or sealed MR-MDF.
- **AMS placement** – on top or on a side shelf / printed side bracket, both outside the printer.
- **Filament feed** – PTFE runs at the back via the Filament Track Switch and the left/right nozzle hub.
- **Purge waste** – magnetic printed catcher behind the printer, a side chute to a table-edge catcher, or (shell) a duct down into a bin on the lower shelf.
- **Airflow & cables** – back cut open around the X2D's rear fan and intake; cable notch open at the bottom so the hood lifts clear; optional future exhaust duct.
- **Outputs** – live checks, overall dimensions, cut list (copy as CSV), panel cut-out positions and a hardware list.

## Status

This is a concept draft. Printer, AMS and rear-feature positions are estimates from photos – measure your own printer and AMS units and enter the real values before cutting anything.

## Run locally

Open `index.html` through any static server, for example:

```bash
python3 -m http.server 8080
```
