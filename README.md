# The harmonic leg — Module XV

Standalone interactive extract of Module XV, "The harmonic leg", from the Chronowave Dynamics Temporal Engine: a single-file compendium of 17 interactive modules about the author's temporal framework. The full compendium, its manual and its edit log are in [chronowave-compendium](https://github.com/Ajuntanaga/chronowave-compendium). The module's own heading on the page reads: "One qubit, strung between τ|0⟩ and t|1⟩".

## Use it

Download or clone this repository, then open [`Module_XV_Harmonic_Leg.html`](Module_XV_Harmonic_Leg.html) from disk in a current browser (GitHub only shows its source). There is no build step and nothing to install. Math (KaTeX 0.16.9) and fonts load from cdnjs and Google Fonts, so equations and typography need a connection.

## Files

| File | What it is |
|---|---|
| [`Module_XV_Harmonic_Leg.html`](Module_XV_Harmonic_Leg.html) | The module: one page with the shared styles, this module's section and the script statements it needs. |
| [`Module_XV_Manual.md`](Module_XV_Manual.md) | This module's part of the compendium's plain-text manual (extracted from rev b90 and hand-patched, so it may lag the page). |

The other two files are this README and a `.gitignore`.

## Where it comes from

Made on 2026-11-14 from rev b91 of the compendium page (commit `6cf22d4` of chronowave-compendium) by the scripts in the `tools/split` folder of that repository (added in later commits). The section markup, the styles and the script statements are copied from the page without change. What differs is the page title and description, a short header and footer line and small stand-ins for the parts of other modules that this module reads (see the limits below).

## Checks and limits

- A scripted headless-Chromium test loaded the page, moved every slider and select, clicked every button, sent pointer and wheel events to every canvas and sent key events to the document: 79 actions (the count includes 38 fixed key and window events), 1 canvas, no uncaught exception and no console error. The page has no selects. It is a smoke test: this extract was not compared with the original module for identical behaviour, and nothing here has had an independent review.
- The leg, its fine angle, the step and fine modes, the az1 and az2 rims, Ground flip, the voice and the chart (a double-click or double-tap on the cross-section chart is the home key) are this module's own and work here; the listening and visual behaviour was read from the code, not judged by ear.
- The lattice of Module IV is replaced by a fixed copy of its start-up state: the identity scale {0, 2, 3, 4, 6, 8, 10} and the root at 261.63 Hz (middle C).
- So the active scale cannot be changed (az1 and az2 always use the interval sets of the identity scale; in the compendium they follow the scale picked on the lattice), and the root pitch stays at middle C (no lattice root slider, no just-intonation tuning).
- Stepping the leg does not sound through the lattice, collapsing a state on the lattice does not move the leg, and Ground flip does not flash the lattice's ground states, because there is no lattice here to link to.
- The framework is the author's own and still in progress; Module XVII of the compendium (also a repository of its own, [chronowave-verdicts-and-rulings](https://github.com/Ajuntanaga/chronowave-verdicts-and-rulings)) carries the page's own verdicts and open rulings.
- No license: all rights are reserved by default, beyond viewing and forking on GitHub; a license is the author's decision.
