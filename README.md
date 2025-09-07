# Prime Fold Theory — Research Modules

**Author:** Sean Sowden  
**Website:** [primefoldtheory.org](https://primefoldtheory.org)  

Prime Fold Theory (PFT) reinterprets structural dynamics through three primitives:  
- **Fold Density (Φ)** — local structural loading  
- **Fold-Time (τ̄)** — tension accumulator with threshold reset  
- **Threshold (κ)** — local collapse bound  

The **Law of Structural Invariance** asserts conservation of the product Φτ̄ between events, 
with resets at threshold crossings. This repo hosts the modular paper series that formalizes, 
tests, and applies this framework.

---

## 📖 Modules

### [Module 1 — Core Theory](./Module1/Mod1v2.pdf)
Defines the Fold primitives (Φ, τ̄, κ), states the invariance law, introduces the Structural Recursive Field (SRF), and frames the math program.  
*Type: Theory-first, conceptual groundwork.*

---

### [Module 2.1 — Cross-System Simulation](./Module2.1/Mod2p1.pdf)
Stress-tests fold-time invariance across two toy systems (SRF lattice, quake toy), multiple dimensions, and parameter sweeps.  
Results: normalized τ̄ cycles are invariant across systems, dimensions, and conditions.  
*Type: Simulation study.*

---

### [Module 2.2 — Mathematical Well-Posedness](./Module2.2/Mod2p2.pdf)
Proves the “Big Five” theorems:  
- Positivity  
- Existence & Uniqueness  
- Budget Closure  
- Reset Locality  
- Anti-Zeno  

Includes a numerical blueprint and a minimal reference solver with audit checks.  
Artifacts:  
- `fold_solver_1d.py` — reference solver  
- `demo_plots.py` — plotting script  
- `README_mod2p2_scripts.md` — usage notes  
*Type: Mathematical foundation.*

---

### [Module 5 — Quaoar: First Observable Fold-Shell Anomaly](./Module5/Module5.pdf)
Applies Fold Gravity to Quaoar’s ring system beyond the Roche limit.  
Result: ring location matches predicted fold-shell boundary; extends to Haumea and Chariklo.  
*Type: Empirical application.*

---

## 🔗 Resources
- Website: [primefoldtheory.org](https://primefoldtheory.org)  
- Contact: sean@primefoldtheory.org  

---

## 📌 License
© 2025 Sean Sowden. Licensed under **CC BY–NC 4.0**.  
You are free to share and adapt the work with attribution, for non-commercial purposes.  
See [LICENSE](https://creativecommons.org/licenses/by-nc/4.0/) for details.
