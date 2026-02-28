# Why Hierarchical Attention Works

**Project hub (all papers / updates):** https://ybing2093-ops.github.io/

This repository hosts the PDF and a source package for **Why Hierarchical Attention Works**, a *fixed-slice* diagnostic view of when hierarchical endpoints are sufficient under a declared reporting package \(V\).

---

## What this work does

We formalize a **package-conditioned** criterion for endpoint sufficiency.

- Fix a declared package  
  \[
  V=(\mathcal I,\varepsilon,\mathcal Q,\mathcal C),
  \]
  where \(\mathcal C\subseteq\mathcal H\) is the evaluation domain, \(\varepsilon\) is a reporting threshold, and \(\mathcal I\) declares the interface (endpoint map, reportable discrepancy readout, and admissible reconstruction family).

- Given an endpoint map \(\mathrm{End}:\mathcal H\to\mathcal E\), define **within-endpoint fiber** variation:
  - fiber diameter \(\mathrm{Diam}_D(e;\mathcal C)\)
  - global gap \(\mathrm{Gap}_D(\mathrm{End};\mathcal C)=\sup_e \mathrm{Diam}_D(e;\mathcal C)\)

- Main statements (under the licensing conditions declared by \(V\)):
  1. **Refinement monotonicity:** refining endpoints does not increase the gap.
  2. **Pinsker bridge (when KL is licensed):** KL-gaps upper bound TV-gaps.
  3. **Fixed-slice residual vs gap:** a minimax reconstruction residual is sandwiched by the gap (up to constants).

**Scope note.** This paper is strictly *fixed-slice / within-endpoint* (fiber-based). It does not use endpoint–path (scale-chain) objects.

---

## Files

- **Paper (PDF):** `Why_Hierarchical_Attention_Works.pdf`
- **Source package (zip):** `Why_Hierarchical_Attention_Works.zip`  
  Contains:
  - `main.tex`
  - `refs.bib` (and `main.bbl`, if included)
  - figure PDFs and the Python scripts used to generate them

---

