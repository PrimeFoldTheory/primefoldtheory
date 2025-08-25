Perfect—here’s a **clean, drop-in `README.md`** that keeps your style, fixes the math/formatting weirdness, and makes the Quaoar provenance crystal clear. Just paste this over your current README.

````markdown
# Prime Fold Theory

A theory-first framework proposing a **Structural Recursive Field (SRF)** with two modes—**persistence** (transport/coherence) and **collapse** (thresholded release)—organized by an invariance ledger \( m = \Phi\,\bar{\tau} \). This repo hosts versioned modules (papers, notes, and artifacts).

> **Status:** Module I (framework) ready; applications are conceptual only. Experiments/sims ship in later modules.

---

## Modules

- **Module I — Framework (Aug 2025)**  
  Core theory paper: SRF substrate, invariance of \(m\), hazard/reset logic, duality, PSP→SRF genesis, and candidate field equations.  
  **PDF:** `paper/module1/Mod1v2.pdf` • **TeX:** `paper/module1/Mod1v2.tex`

- **Module IV — QUAOAR.01 (conceptual audit)**  
  Ring stability as a standing fold pattern; recursive boundaries and thresholding.  
  **PDF (site):** https://primefoldtheory.org/paper/quaoar_fold_complete_with_figures.pdf

---

## 🧭 Original equation — provenance (read first)

The **earliest public record of the original field ansatz** appears in **Module IV (Quaoar)**.  
That **“April 2025 original”** form predates the **August 2025 revision** used in Module I.

- **Source of record (original equation, April 2025):**  
  QUAOAR.01 — Testing Recursive Boundaries (PDF)  
  https://primefoldtheory.org/paper/quaoar_fold_complete_with_figures.pdf

- **Current framework (August 2025 revision):**  
  **Module I — Framework (PDF):** `paper/module1/Mod1v2.pdf`  
  **TeX:** `paper/module1/Mod1v2.tex`

**How to cite in text:**  
“See Module IV (Quaoar) for the original ansatz; this paper uses the August 2025 revised, gated form.”

> This README will continue to point to the **April 2025 snapshot** as the canonical source of the original form.

---

## 📂 Repository Contents

> Paths may vary depending on where you’ve placed the files. Update these bullets if your layout differs.

- `paper/module1/Mod1v2.tex` — Module I LaTeX source  
- `paper/module1/Mod1v2.pdf` — Module I compiled PDF

**Quaoar artifacts (examples):**
- `quaoar_fold_complete_with_figures.tex` — LaTeX source  
- `quaoar_fold_complete_with_figures.bib` — BibTeX references  
- `quaoar_fold_complete_with_figures.pdf` — Compiled paper (see site link above)  
- `attempt_1_sim.png` → `attempt_4_sim.png` — Simulation outputs  
- `fold_shell_sweep.png` — Final system comparison sweep  
- `fold_shell_sweep_overlay.png` — Annotated overlay visualization

- `LICENSE` — Custom license and usage terms

---

## 🛠️ Build locally (LaTeX)

```bash
# example: build Module I
cd paper/module1
latexmk -pdf Mod1v2.tex

# or minimal
pdflatex Mod1v2.tex && pdflatex Mod1v2.tex

# view (choose your viewer)
okular Mod1v2.pdf &
````

**Notes**

* Avoid math in section **titles/headings** (prevents `hyperref` warnings in the PDF).
* For arXiv, either include an inline `thebibliography` or run BibTeX and commit the generated `.bbl`.
* Filenames: ASCII only, no spaces.

---

## ⚖️ License

© 2025 Sean Sowden — All rights reserved.
This work is governed by a custom license pending formal release.

Redistribution is permitted for:

* Academic review
* Citation with attribution
* Endorsement requests

Public reuse, derivative works, or commercial applications are prohibited until the framework is formally released.
A [Creative Commons Attribution 4.0 License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) will apply upon release.

See [`LICENSE`](./LICENSE) for full terms.

---

## 📣 arXiv Endorsement Invitation

This module is prepared for submission to arXiv under the `physics.space-ph` archive.
If you are an arXiv author in this category and believe this work is of interest, please consider endorsing it.

📄 View the Quaoar paper (site): [https://primefoldtheory.org/paper/quaoar\_fold\_complete\_with\_figures.pdf](https://primefoldtheory.org/paper/quaoar_fold_complete_with_figures.pdf)

---

## 📬 Contact

**Email:** [Sean@PrimeFoldTheory.org](mailto:Sean@PrimeFoldTheory.org)
**Project Site:** [https://primefoldtheory.org](https://primefoldtheory.org)

```

If your Module I files live somewhere else, just tweak those two paths near the top. Want me to add a tiny “How to contribute” or a `CITATION.cff` later?
::contentReference[oaicite:0]{index=0}
```
