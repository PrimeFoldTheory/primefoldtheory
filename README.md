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

*(Relative links work immediately on GitHub. Public site links will match once Pages rebuilds.)*

---

## Module I (Aug 2025 revision) — What’s inside

- Core quantities: **Fold Density (Φ), Fold-Time (τ̄), Threshold (κ)**
- **Duality as a structural mechanism** (persistence ↔ collapse)
- **Law of Structural Invariance**: conservation of *m* between events with flux accounting
- **PSP → SRF** genesis; **wave as the simplest fold** (organizing claim, not an axiom)
- Candidate **field equations** for SRF
- **Conceptual applications only** (Quaoar ring stability, double-slit, capillarity)

**Status:** Theory-first paper. No experiments or sims included here; those land in later modules.

---

## Module II — Recursive Boundaries in EEG Systems

### 📄 Module 2.1: Cross-System Simulation of Fold-Time Invariance
- [PDF](paper/module2/module2.1/mod2p1.pdf)  
- [LaTeX source](paper/module2/module2.1/mod2p1.tex)  
- **Status**: Complete, arXiv-ready. Simulates SRF vs quake toy to test invariance.

### ⏳ Module 2.2: EEG Application
- Placeholder (in preparation).  
- Will test invariance using human EEG recordings.

### ⏳ Module 2.3: Extensions
- Placeholder (planned).  
- Expands EEG analysis and recursive boundaries to broader biological data.

---

## Provenance of the Original Ansatz

The earliest public record of the original field ansatz appears in the **Quaoar module (Apr 2025)**.  
**Module I (Aug 2025)** uses a **gated/truncated** revision.

**Cite in text:** “See the Quaoar module for the original ansatz; this paper uses the August 2025 revised, gated form.”

- Original (Apr 2025): [`quaoar_fold_complete_with_figures.pdf`](quaoar_fold_complete_with_figures.pdf)  
- Current framework: [`paper/module1/Mod1v2.pdf`](paper/module1/Mod1v2.pdf)

---

License

© 2025 Sean Sowden. All rights reserved until formal release.
If a LICENSE file is present, its terms govern.

Contact

Email: Sean@PrimeFoldTheory.org
Site: https://primefoldtheory.org

## Build Locally (LaTeX)

```bash
cd paper/module1
latexmk -pdf Mod1v2.tex
# or: pdflatex Mod1v2.tex && pdflatex Mod1v2.tex
okular Mod1v2.pdf &
