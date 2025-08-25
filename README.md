# Prime Fold Theory

**Prime Fold Theory (PFT)** is a theory-first framework built on a **Structural Recursive Field (SRF)** with two operational modes:
- **Persistence** — transport/coherence of structure
- **Collapse** — thresholded release events

The framework tracks an invariance ledger **m = Φ τ̄** (fold density × truncated Fold-Time) between threshold events.  
This repository hosts the versioned papers, notes, and artifacts for PFT.

---

## Quick Links

- 📄 **Module I — Framework (PDF):** [`paper/module1/Mod1v2.pdf`](paper/module1/Mod1v2.pdf)  
- 🧪 **LaTeX source:** [`paper/module1/Mod1v2.tex`](paper/module1/Mod1v2.tex)  
- 🪐 **Original equation (Apr 2025) — Quaoar module:** [`quaoar_fold_complete_with_figures.pdf`](quaoar_fold_complete_with_figures.pdf)

> These are **relative links** and work immediately on GitHub.  
> Public site links (primefoldtheory.org) can be added once Pages finishes rebuilding.

---

## What’s in Module I (Aug 2025 revision)

- Core quantities: **Fold Density (Φ), Fold-Time (τ̄), Threshold (κ)**  
- **Duality as a structural mechanism** (persistence ↔ collapse)  
- **Law of Structural Invariance**: conservation of *m* between events with flux accounting  
- **PSP → SRF genesis** (pre-structural potential evolving into the SRF substrate)  
- **Wave as the simplest fold** (organizing claim, not an axiom)  
- Candidate **field equations** for SRF  
- Conceptual applications only (e.g., Quaoar ring stability, double-slit, capillarity)

**Status:** Theory-first paper. No experiments or sims included here; those land in later modules.

---

## Provenance of the Original Ansatz

The **earliest public record** of the original field ansatz appears in the **Quaoar module (Apr 2025)**.  
**Module I (Aug 2025)** uses a **gated/truncated** revision.

**Cite in text:** “See the Quaoar module for the original ansatz; this paper uses the August 2025 revised, gated form.”

- Original (Apr 2025): [`quaoar_fold_complete_with_figures.pdf`](quaoar_fold_complete_with_figures.pdf)  
- Current framework: [`paper/module1/Mod1v2.pdf`](paper/module1/Mod1v2.pdf)

---

## Build Locally (LaTeX)

```bash
cd paper/module1
latexmk -pdf Mod1v2.tex
# or: pdflatex Mod1v2.tex && pdflatex Mod1v2.tex
okular Mod1v2.pdf &
